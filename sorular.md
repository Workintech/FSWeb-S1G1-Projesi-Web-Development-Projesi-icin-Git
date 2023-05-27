# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
   Git, yazılımcıların sıklıkla kullandığı kod yazma sürecindeki değişiklikleri tarihsel ve içerik olarak hafızada tutan bir sistemdir.
2. Git ile GitHub arasında ne fark var?
   Git doğrudan editör üzerinden versiyon çıktıları almamızı sağlarken Github ise aldığımız çıktıları internette depolayabilme ve paylaşabilme imkanı sağlayan bir bulut sistemidir.
3. Neden bir branch oluşturuyoruz?
   Branch oluşturmamızın temel nedeni bir projede birden fazla kişinin farklı geliştirmeler yapmasını ve bu geliştirmelerin çakışmasını önlemek içindir.
4. Pull Request'in amacı nedir?
   Bir proje üzerinde yaptığımız değişikliklerin kontrol edilmesi ve tartışılması için paylaşma sistemidir.
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
   checkout komutuyla bir branch den başka bir branch'e geçebiliriz. 'git checkout main' yazmam yeterli olacaktır.
6. `git fetch`, `git merge` ve `git pull` arasındaki farklılıkları açıklayınız. Bu komutlar ne yapar açıklayınız.
   git fetch: uzak bağlantı deposunda ki branchleri indirmemize yarar. git merge: branchleri birleştirmemize yarar. git pull: hem uzak depoda ki branchleri indirmeye hem de bu branchleri belirttiğimiz branchlerle birleştirmeye yarar. Yani pull komutu hem fetch hem de merge komutunu birleştirir.
7. Merge conflict nedir?
   Branchler üzerinde yapılan değişikliklerin çakışma durumudur.
8. Merge conflict'i nasıl çözeriz?
   Merge conflict olan bölüm tespit edildikten sonra çakışan yerler kaldırılır, ve son versiyonu hedef alınarak paylaşılır.
