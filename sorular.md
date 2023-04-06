# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
yazılım geliştirme süreçlerinde kullanılan sürüm kontrol sistemidir. Git sayesinde çalıştığımız projelerin versiyonlarını kopyalayarak daha sonra ki süreçlerde bir hata veya bir sorun ile karşılaştığımızda kopyasını aldığımız o versiyonuna geri dönebiliyoruz.
2. Git ile GitHub arasında ne fark var?
github ise Git'lerin tutulduğu web tabanlı veri depolama sistemidir. Bir proje üzerinde birden fazla kişi çalışmasına imkan tanımakta, Projenin ve kodların kaybolma sorununu önlemekte, projelerin platformda paylaşılmasıyla beraber bir çok kullanıcının projeye ve kod yazımına destek olabilmesini, hataları tespit edebilmesini sağlamaktadır.
3. Neden bir branch oluşturuyoruz?
Örneğin; bir bahçe peyzajı yapacağız. Bahçe'de çiçeklerin dikimi, dizaynını bir peyzaj mimarı yapacak, ışıklandırmasını bir elektrik ustası yapacak, bahçe mobilyaları ve aksesuarlarını mobilya ustası yapacaktır.
Ancak çalışacak kişilerin aynı anda çalışması mümkün değildir. Bu kapsamda bütün çalışacak kişilere bahçenin kopyasını veriyoruz ve bu kişiler ayrı ayrı bahçe üzerinde çalışabiliyor. Buna imkan tanıması branch olarak adlandırılmaktadır.
4. Pull Request'in amacı nedir?
Branch'ten sorumlu kişiye bir branch üzerinde yapılan değişikliklerin iletilmesi ve akabinde bu kişinin kodları kontrol edip ana branche merge etmesini sağlamaktadır.
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın? Ls komutuyla dosyaları listelerim. Git branch yazarak hangi branch'te olduğumu görürüm Eğer main branche değilsem git checkout main komutunu çalıştırırım
git checkout komutunu kullanırım.
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

Uzak bir depodaki değişiklikleri indirmeye ve değişiklikleri görmeye imkan tanır. - Git Fetch

Uzak bir depodaki bu değişiklikleri mevcut branch ile birleştirmeye imkan tanır. - Git Merg

Uzak bir depoda yapılan değişiklikleri almak ve mevcut branch arasındaki  farkları birleştirme işlemidir.  - Git Pull
Diğer bir deyiş ile Fetch ve Merge komutlarının yaptığı işlemi tek seferde yapmaktadır.

7. Merge conflict nedir?
Google üzerinden araştırmama göre; iki kişi aynı dosya üzerinde, aynı satırdaki değişiklik yaptığında git otomatik olarak merge etmezse değişikler çakışacaktır. Bu olay Merge Confliqqqqqqqqct olarak adlandırılır.
8. Merge conflict'i nasıl çözeriz?
bunu chatGPT ile araştırdım. Şu sonucu buldum.

Merge conflict, farklı branch'lerde yapılan değişikliklerin aynı dosya veya satırlarda birleştirilmesi sırasında ortaya çıkan bir durumdur. Bu durumda, Git, otomatik olarak birleştirme yapamaz ve çakışmaları belirtir. Bu çakışmaları çözmek için, şu adımları izleyebilirsiniz:

İlk olarak, hangi dosya veya satırlarda çakışmanın olduğunu belirlemek için "git status" komutunu kullanın.
Daha sonra, hangi branch'in birleştirileceğine karar verin. Birleştireceğiniz branch'i aktif hale getirin (checkout).
Ardından, düzenleyebileceğiniz dosyaların değişikliklerini görmek için "git diff" komutunu kullanın.
Değişikliklerinizi yapın ve kaydedin.
Değişiklikleri yaptıktan sonra, dosyaları staging area'ya ekleyin (git add).
Son olarak, değişiklikleri birleştirmek için "git merge" komutunu kullanın.
Eğer Git, çakışmaları otomatik olarak çözemezse, bir çakışma dosyası oluşturulur. Bu dosyalar, çakışmaları elle çözmenize olanak tanır. Çakışma dosyalarını elle çözmek için, şu adımları izleyebilirsiniz:

Çakışmaların olduğu dosyaları açın ve farklılıkları gösteren belirteçleri (<<<<<, ======, >>>>>) arasındaki kısımları inceleyin.
Farklılıkların her iki versiyonunu da birleştirecek şekilde değişiklikler yapın.
Değişiklikleri kaydedin ve staging area'ya ekleyin (git add).
Çakışma dosyasını silin.

