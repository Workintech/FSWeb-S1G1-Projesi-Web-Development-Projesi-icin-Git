# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

Git, yazılım geliştirme süreçlerinde kullanılan, hız odaklı, dağıtık çalışan bir sürüm kontrol ve kaynak kod 
yönetim sistemidir.

2. Git ile GitHub arasında ne fark var?

Git kodlarımızı yazabildiğimiz ve kod geçmişiniz takip edebildiğimiz bir sistem iken,
Github, Git üzerindeki repolarımızı yönetmemizi kolaylaştıran bulut tabanlı bir servistir.

3. Neden bir branch oluşturuyoruz?

Grup haline çalışırken ana dosyayı değiştirmeden belli parçalar üzerinde kendimiz çalışabilelim diye.

4. Pull Request'in amacı nedir?

Pull request, ana projedeki repomuzun güncellenmesini sağlar.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? 
Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

$ git checkout main

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

git getch,: Hedef branch'taki commitleri kendi local branchimize çeker ve saklar, otomatik olarak branchleri merge'lemez.
git pull: Hedef branch'taki commitleri kendi local branchimize çeker ve otomatik olaran branchleri birleştirir.
git merge: Bütün çatallanmış branchleri tek bir branch haline getirir.

7. Merge conflict nedir?

 İki farklı branchte aynı dosya ve satır üzerinde değişim yapılmışsa, git bunları merge edemeyebilir ve bu durumda kullanıcıya
 hangi yolla devam etmek istediğini sorar.

8. Merge conflict'i nasıl çözeriz?

Değişimi yapan bireyler bir araya getirilir ki ve kodun nasıl olması gerektiğine karar verilir daha sonra tek bir kodla yola devam edilir. 