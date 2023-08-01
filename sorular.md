# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

    Git, sürüm kontrol sistemidir. Sürüm kontrol sistemleri yazılım geliştirme süreçlerinde kod değişikliklerini takip etmek, yönetmek ve işbirliği yapmak için kullanılır.

2. Git ile GitHub arasında ne fark var?

    Git, sürüm kontol sistemidir ve yerel bilgisayarda çalışırken proje geçmişimizi yönetebiliriz. GitHub ise Git tabanlı bulut depolama ve işbirliği platformudur.

3. Neden bir branch oluşturuyoruz?

    Mevcut kod tabanından bağımsız bir çalışma alanı oluşturur ve kaynak kodların istenmeyen değişikliklerini önleriz ayrıca yeni bir özellik eklemek veya bir hatayı düzenlemek için oluşturulur. Bu da birden çok kişinin
    aynı anda farklı özellikler ve değişlikler üzerinde çalışmasına olanak sağlar.

4. Pull Request'in amacı nedir?

    Açık kaynaklı projelerde ve işbirliçi bir kod tabanı olan GitHub gibi platformlarda yapılan değişikliklerin ana projeye eklenmesinde kullanılır.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

    "git checkout ali-oguzhan-colak" şeklinde kullanabiliriz. 

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

    "git fetch" -> Uzak bir depodan değişiklikleri indirir, ancak çalışma dizininde veya çalışma kopyasında herhangi bir değişiklik yapmaz. Güncellemeleri ve değişiklikleri görüntülememizi sağlar ve yerelde olmanayan
    brachleri almamıza olanak sağlar.

    "git merge" -> İki farklı brachteki değişiklikleri bir araya getirmemizi sağlar. Çakışma olmazsa, birleştirme otomatik olarak gerçekleştirilir.

    "git pull" -> Yerel branchi uzak sunucudan güncel verilerle güncellemek için kullanılır. Yani önce uzak depodan değişiklikleri alır(fetch) ve sonra mevcut branchi güncel verilerle birleştirir(merge).
 
7. Merge conflict nedir?

    Farklı branchlerde aynı dosya üzerinde çakışan değişikliklerin olduğu durumlarda ortaya çıkar.

8. Merge conflict'i nasıl çözeriz?

    Çakışan dosyayı el ile düzeltme, değişiklikleri commit edip ve merge işlemini tamamlarız.
