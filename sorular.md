# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
   <!-- * -->
   A1.Bir ana proje dosyası üzerinde değişiklik yapmak yerine git ile farklı kopyalar oluşturup değişiklikler yapıyoruz . Bu bize bir hata yaptığımızda ana (değiştirilmemiş) projeye geri dönüş yapmamızı sağlıyor . Yani bir nevi projelerimizin üzerinde risksiz şekilde değişiklik yapmamızı sağlar.
    <!-- * -->
2. Git ile GitHub arasında ne fark var?
   <!-- * -->
   A2.Git proje versiyonlarını kontrol ettiğimiz bir sistemdir . GitHub ise değişiklik yaptığımız veya oluşturduğumuz projeleri depoladığımız bir portaldır.
      <!-- * -->
3. Neden bir branch oluşturuyoruz?
   <!-- * -->
   A3.Branch ile orjinal koddan bağımsız olarak bir kopya oluşturup değişiklikleri buranın üzerinde yapıyoruz. Yaptığımız geliştirmedeki testleri tamamlayıp ana brancha yüklüyoruz . Böylece ana projeye dokunmadan karışıklığı önleyerek geliştirmemize olanak sağlıyor.
4. Pull Request'in amacı nedir?
   A4. Değişiklik yaptığımız bir başkasının projesine , yaptığımız değişiklikleri inceletmeye sunduğumuz taleptir.
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
   A5.branch değiştirmek için git checkout gitmek istediğimiz branch
   git checkout master ile main branch'ine geçeriz
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
   A6. git fetch ile lokal repomuza değişikleri getirir incelememize olanak sağlar ama değiştirmez .
   git pull bir deponun yerel sürümünü remote olarak indirmek ve güncellemek için kullanılır. git fetch den farkı güncelleme yapılabilir.
   git merge başka bir branch'deki değişiklikleri kendi branch'imize entegre etmemize yarar.
7. Merge conflict nedir?
   A7.Merge conflict aynı anda iki veya daha fazla kişinin aynı dosyayı ve aynı satırı değiştirip pushlamasıyla beraber ortaya çıkan çakışma problemidir.
8. Merge conflict'i nasıl çözeriz?
   A8.Çakışma hatası aldığımızda çakışan kısmı VSCode bize hata olarak döndürecek .Hata olan bölüme girdiğimizde çakışmaları sağ ve sol olarak iki pencerede görüyor olacağız , burda değişikliği onaylayacağımız taraftaki kutucuğa işaret koymamız gerekecek.Böylece kaydedip yüklenmesi gereken kodları remote a yollayabiliriz.
