# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
   Git yazılım geliştirme aşamasında kullanılan bir versiyon kontrol sistemidir. Yazılım yaparken sürekli değişim ve güncelleme yapılması gerekebilir. Git bu konuda yapılan değişikliklerin düzenli tutulmasına olanak tanır. Aynı zamanda bir projenin birden fazla insanla aynı anda yapılabilmesini sağlar.

2. Git ile GitHub arasında ne fark var?
   Git'in temel amacı bir projenin kodunu yönetmekken Githup bu kodları depolamaya ve paylaşmaya yarar. Git'de depolama ve işlemler yerel bilgisayar üzerinden yapılırken Githup'ta sunucu üzerinden yapılmaktadır. Ayrıca Git ücretsiz ancak Githup'ta kar amacı güdülmekte ve ücretli abonelik gerebilmektedir.

3. Neden bir branch oluşturuyoruz?
   Branch oluşturmak projenin farklı versiyonlarını oluşturur. Bir proje üzerinde değişiklik ya da güncelleme yapılmak istendiğinde orijinal olan kod yerine yeni bir yedek üzerinde geliştirme yapmak projenin ilk kaynak halini bozmamak için kullanılır. Projede olası bir hata çıkması halinde orijinal olan versiyona erişmeyi kolaylaştırır.

4. Pull Request'in amacı nedir?
   Git üzerinden birinin projesini fork edip bir branch içinde o proje için geliştirme yaptığımızı düşünelim. Pull request ile projenin sahibine değişiklikleri incelemek üzere gönderilen bir taleptir. Geliştimenin asıl projeye aktarılması için pull request atılır.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
   git checkout main yazarak master branch'e geçebiliriz.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
   Git fetch yaptığımız değişiklikleri yerel repoya getirir ama değişiklik yapmaz, incelemeye olanak tanır. Git merge yapılan değiişiklikleri master branch'e taşımaya olanak tanır yani birleştirir. Git pull ise bu değişiklikleri getirirken aynı zamanda birleştirir ve günceller.

7. Merge conflict nedir?
   Birden fazla kişi bir proje üzerinde çalışırken aynı dosya üzerinde çalışmalar yapıldığında bu dosyalar merge edilmek istendiğinde bir çakışma yaşanması durumudur.

8. Merge conflict'i nasıl çözeriz?
   Kodları inceleyerek hangisinin doğru olduğunu belirleyip onu tercih ederek problemi çözebiliriz.
