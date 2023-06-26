# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
   Git, açık kaynaklı dağıtılmış sürüm kontrol sistemidir. Kontrol sistemi olması Git'in bir içerik izleyicisi olduğu anlamına gelir. Sürüm kontrol sistemi olması ile projeleri oluşturan kullanıcılar tarafından yapılan güncellemeleri kayıt altına alır ver bu güncellemerlin kronolojik sıraya göre takip edilmesini sağlar. Dağıtılmış süsürm kontrol sistemi ise, kod dosyalarının git'te yani merkezi bir sunucada dapolanması ve bu dosyaların kullanıcılar tarafından kopyalanabilmesi demektir.
2. Git ile GitHub arasında ne fark var?
   Git, dosyaların verisyon kontrollerini, depolanmasını ve birden fazla kullanıcının ana bir dosya üzerinde çalışabilmesini sağlarken GithUb, Git tabanlı dosyaların depolanmasını sağlar ve başka kullanıcılar ile paylaşılmasını sağlar.
3. Neden bir branch oluşturuyoruz?
   Hali hazırda çalışan ana bir branchimiz varken bu çalışan versiyon etkilenmeden ana branch'e yeni bir özellik eklemek ve bu özelliği test etmek için yeni bir branch oluştururuz. Bu yeni branc'de testleri tamamladıktan sonra merge ile ana branch'e yeni branch'de hazırladığımız yeni özelliği ekleriz.
4. Pull Request'in amacı nedir?
   Pull request, proje sahibin proje sahibi üzerinde yaptığımız değişiklikleri görmesini ve gözden geçirip birleştirmesini talep etmemizi sağlar.
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
   Bir branch'den diğerine geçmek için git checkout branch ismi komutunu kullanırız. git checkput main yaparak kendi ismimizin olduğu branch'den ana branch'e geçmiş oluruz.
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
   1.Git Fetch:uzaktaki bir deponun dosyalarını, anlık görüntülerini ve referanslarını yerel deponuza indiren bir komuttur. Bu komut, yerel deponuzun mevcut çalışma durumunu güncellemeden uzaktaki verileri indirir, çalışmanızı olduğu gibi bırakır.
   2.Git Merge: Bu komut yeni açılan branch'de yapılan değişikliklerin ana branch'e eklenmesini sağlar.
   3.Git Pull: Eğer dosyada başka bir kullanıcının yaptığı bir değişiklik varsa bunu kendi bilgisayarımıza çekmemizi sağlar. Bu komut uzaktaki bir depodan verileri getirip indirirken yerel depoyu getirilen verilerle eşleşecek şekilde günceller.
   Bu komutlar arasındaki fark ise git pull komutu git fetch ile git merge komutunun birleşimidir.
7. Merge conflict nedir?
   İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır. Buna da merge conflict denir.
8. Merge conflict'i nasıl çözeriz?
   Merge conflict olmaması için konfigürasyon ayarı yapmak gerekir bunun için de git config -- global rerere.enabled true yazarız. Bu git'in bize merge ettiğimizde olası iki adet birleştime yapmasını sağlar. Bizde bu birleştirmeleri kontrol edip birini seçerek bunun üzerinden devam edebiliriz.
