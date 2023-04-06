# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Git, dağıtık bir versiyon kontrol sistemidir. Yazılım geliştirme sürecinde yapılan değişikliklerin takip edilmesine, eski versiyonlara geri dönülmesine ve ekip üyeleri arasında kodun paylaşılmasına olanak tanır.

2. Git ile GitHub arasında ne fark var?
Git, bilgisayarınızdaki yerel bir uygulama ve versiyon kontrol sistemidir. GitHub ise, Git projelerini barındıran ve paylaşmak, işbirliği yapmak için kullanılan web tabanlı bir platformdur. GitHub, Git ile oluşturulan depoların (repository) uzak sunucularda saklanmasına ve yönetilmesine yardımcı olur.

3. Neden bir branch oluşturuyoruz?
Bir branch oluşturmak, projenizde aynı anda farklı özellikler veya düzeltmeler üzerinde çalışmanıza olanak tanır. Böylece, ana projeden bağımsız olarak çalışıp, sonunda ana projeye (genellikle "main" veya "master" olarak adlandırılır) geri birleştirebilirsiniz.

4. Pull Request'in amacı nedir?
Pull Request (PR), bir branchte yapılan değişiklikleri başka bir branch ile birleştirmek istediğinizde kullanılır. PR, projenin diğer katılımcılarına değişiklikleri inceleme, tartışma ve onaylama fırsatı verir.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout oktay-demirhas

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch: Uzak depodan (repository) yerel depoya tüm değişiklikleri alır, ancak otomatik olarak birleştirmez.
git merge: İki farklı branch'i birleştirmeye yarar. Genellikle, git fetch ile alınan değişikliklerin mevcut branch ile birleştirilmesi için kullanılır.
git pull: git fetch ve git merge işlemlerini bir araya getirir. Uzak depodan değişiklikleri alır ve yerel branch ile otomatik olarak birleştirir.

7. Merge conflict nedir?
Merge conflict, iki farklı branch'teki aynı dosyanın aynı satırında yapılan değişikliklerin Git tarafından otomatik olarak birleştirilememesi durumudur. Bu durum, genellikle iki kullanıcının aynı kod parçasını farklı şekillerde düzenlemesi nedeniyle ortaya çıkar.

8. Merge conflict'i nasıl çözeriz?
Merge conflict'i çözmek için şu adımları izleyebilirsiniz:

1-git status komutu ile çakışan dosyaları tespit edin.
2-Çakışan dosyaları açın ve <<<<<<, ======, >>>>>> işaretlerinin arasındaki farklılıkları inceleyin.
3-İlgili kısımları düzenleyerek çakışan değişiklikleri manuel olarak birleştirin ve çakışma işaretlerini kaldırın.
4-Değişiklikleri kaydedin ve dosyayı kapatın.
5-Çakışmayı çözdüğünüz dosyaları git add komutu ile Git'in izlemesine ekleyin.
6-Çakışmaların çözüldüğünü belirtmek için git commit komutunu kullanın. İlgili commit mesajını yazarak işlemi tamamlayın.
7-Merge işlemini tamamlamak için git merge veya git rebase komutlarından birini kullanarak branch'leri birleştirin.
8-Yerel değişiklikleri uzak depoya (repository) göndermek için git push komutunu kullanın.