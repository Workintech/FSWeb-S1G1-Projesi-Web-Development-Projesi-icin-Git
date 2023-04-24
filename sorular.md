# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

Git, yazılım süreçlerinde kullandığımız versiyon kontrol sistemidir.

2. Git ile GitHub arasında ne fark var?

Git local bilgisayarımıza indirdiğimiz projenin versiyonlanmasını yapabilir ve internet dahi olmadan kullanabiliriz ve git hub a da ihtiyaç duymayız. Herhangi bir kayıt da gerektirmez.

Git hub ise,Git repository'lerinin cloud üzerinde saklandığı online bir servistir. Github'a kayıt olmanız gereklidir ve ek fayda olarak da başka kişilerin repository'lerine erişebilir ya da kendi repository'lerinize erişmelerini ve katkı sağlamalarını isteyebilirsiniz. Online bir servistir ve offline olarak kullanabilneniz mümkün değildir.

3. Neden bir branch oluşturuyoruz?

Ana proje üzerinde yapacağımız değişkliğin, eş zamanlı diğer kullanıcılar tarafından yapılan değişikliklerden etkilenmeden sağlıklı bir şekilde geçekleştirmek adına  kullanırız.

4. Pull Request'in amacı nedir?

Pull Request, temelde branch'dan sorumlu kişinin kodumuzu eklemesini istemek için kullanılır. Ayrıca o kişinin kodda tam olarak neyi değiştirdiğinizi görmesine de yardımcı olur.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

branchlar arası gezinmek için: git checkout "geçmek istediğimiz branch".

 main branch'a geçmek için: git checkout main


6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

git fetch: Bu komut remote’daki tüm commitleri local’e çeker. Fakat çekilen commitler remote branch’lar olarak depolanır, local olarak değil. Bu sayede local’deki kodla merge etmeden önce gözden geçirme şansı verir.

git pull: Bu komut, upstream’deki dosyaları çeker ve local’deki kodla direk birleştirir.

git merge: Farklı branch'lardaki çalışmalarımızı birleştirir.

git fetch ile git pull arasındaki ilişki; git pull=git fetch+ git pull


7. Merge conflict nedir?

 İki kişi aynı dosyayı ve aynı satırı değiştirmesi  ve git otomatik olarak merge edememesi durumunda conflict yani çakışma olacaktır. 

8. Merge conflict'i nasıl çözeriz?

Merge etmeden önce sırasıyla aşağıdaki komutları yazarak , gerekli kontrolleri yaparsak merge conflict in önüne geçme şansımız olabilir.
git add -A

git stash

git checkout master

git pull

git checkout profil-sayfasi

git rebase master

git stash apply
