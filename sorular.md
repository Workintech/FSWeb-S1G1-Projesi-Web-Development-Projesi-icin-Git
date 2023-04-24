# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

Git, açık kaynak kodlu bir versiyon kontrol sistemidir. Geliştiricilerin proje kaynak kodunu takip etmelerine, farklı sürümler üzerinde çalışmalarına, değişiklikleri geri alabilmelerine ve projeleri yönetmelerine olanak sağlar. Git'in en büyük avantajlarından biri, dağıtık bir yapıya sahip olmasıdır. Bu, her kullanıcının yerel bir kopya üzerinde çalışabileceği ve daha sonra diğer kullanıcılarla senkronize edebileceği anlamına gelir. Git, dünya çapındaki birçok büyük proje tarafından kullanılmaktadır ve yazılım geliştirme süreçlerinde önemli bir rol oynamaktadır.

2. Git ile GitHub arasında ne fark var?

Git ve GitHub arasında temel bir fark vardır. Git, bir versiyon kontrol sistemidir ve yerel bilgisayarınızda dosya ve kod değişikliklerinin takip edilmesine, geri alınmasına ve senkronize edilmesine olanak tanır. GitHub ise, Git üzerinde barındırılan bir bulut tabanlı hizmettir. GitHub, birçok farklı kullanıcının bir projede birlikte çalışmasını kolaylaştırır ve projelerin Git'te saklanmasını ve paylaşılmasını sağlar.

GitHub, kullanıcıların Git deposuna erişim sağlamalarına ve bu depoları diğer kullanıcılarla paylaşmalarına olanak tanır. Ayrıca, kullanıcılar açık kaynaklı projeler için katkıda bulunabilirler ve diğer kullanıcılar tarafından sağlanan açık kaynaklı kodları kullanabilirler.

Sonuç olarak, Git, yerel bilgisayarınızda kod yönetimi için kullanılan bir araçtır, GitHub ise Git'te saklanan projelerin paylaşılması ve işbirliği için kullanılan bir bulut tabanlı hizmettir.

3. Neden bir branch oluşturuyoruz?

Bir "branch" oluşturmak, bir projenin aynı anda farklı işlevlerinin veya özelliklerinin geliştirilmesine izin veren ve kod tabanının bölümlerinin ayrı bir kopyasını oluşturan Git'in temel özelliklerinden biridir.

Bir branch, kod tabanındaki mevcut kodu korurken, yeni özelliklerin veya değişikliklerin test edilmesine ve geliştirilmesine olanak tanır. Bir branch oluşturmak, farklı özelliklerin farklı zamanlarda geliştirilmesine ve test edilmesine izin vererek, projelerin daha düzenli bir şekilde yönetilmesine yardımcı olur.

Ayrıca, birden fazla geliştiricinin aynı anda çalıştığı projelerde, farklı branch'lerin oluşturulması, farklı ekiplerin ayrı ayrı çalışabilmesine izin verir. Bu şekilde, bir geliştirici diğer geliştiricilerin çalışmalarını etkilemeden, kendi branch'inde özelliklerin veya değişikliklerin geliştirilmesine devam edebilir.

Sonuç olarak, bir branch oluşturmak, kod tabanının korunmasına ve projenin daha düzenli bir şekilde yönetilmesine olanak sağlar ve aynı zamanda farklı ekiplerin ayrı ayrı çalışmalarını kolaylaştırır.

4. Pull Request'in amacı nedir?

"Pull Request", bir Git deposunda yapılan değişikliklerin ana kod tabanına birleştirilmesi için bir iş akışıdır. Pull Request, kod değişikliklerinin gözden geçirilmesi, onaylanması ve birleştirilmesi sürecini yönetir.

Bir Pull Request oluşturulduğunda, değişikliklerin ana kod tabanına birleştirilmeden önce gözden geçirilmesi ve onaylanması gereken bir dizi adım başlatılır. Pull Request oluşturan kişi, diğer geliştiricilerin değişiklikleri görüntülemesine, incelemesine ve yorumlamasına olanak tanıyan bir tartışma alanı sağlar.

Pull Request oluşturma, diğer geliştiricilerin değişiklikleri incelemesi ve onaylaması için bir fırsat sunar. Bu, yazılım kalitesinin artmasına ve hataların azaltılmasına yardımcı olabilir. Ayrıca, Pull Request iş akışı, kod değişikliklerinin açık bir şekilde belgelenmesini sağlar ve projeye katkı sağlayan geliştiricilerin tanınmasına olanak tanır.

Sonuç olarak, Pull Request iş akışı, kod değişikliklerinin gözden geçirilmesi, onaylanması ve ana kod tabanına birleştirilmesi sürecini yönetir ve yazılım kalitesini arttırmaya yardımcı olur.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

Git'te bir branch'ten diğerine geçmek için git checkout komutu kullanılır. isim-soyisim branch'inde çalışırken, main branch'ine geçmek için aşağıdaki komut kullanılabilir:

git checkout main

Bu komut, Git deposunda bulunan main branch'ine geçiş yapar ve mevcut çalışma ortamınızı main branch'inin son haline uygun hale getirir. Bu sayede, main branch'indeki son değişiklikleri görüntüleyebilir veya isim-soyisim branch'inde yaptığınız değişiklikleri main branch'ine birleştirebilirsiniz.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

git fetch komutu, depodaki en son durumu görmek ve uzak depodaki değişikliklerin lokalde görünür hale getirilmesini sağlamak için kullanılır. git merge komutu, farklı branch'lerde yapılan değişiklikleri birleştirir ve tek bir branch'e uygular. git pull komutu ise, git fetch ve git merge komutlarını birleştirerek kullanmanın kısa yoludur.

7. Merge conflict nedir?

Merge conflict, Git'te farklı branch'lerde yapılan değişikliklerin birleştirilmesi sırasında ortaya çıkan bir durumdur. Merge işlemi sırasında, farklı branch'lerde aynı dosyaların aynı satırlarında değişiklik yapılırsa, Git otomatik olarak bu değişiklikleri birleştiremez. Bu durumda, merge conflict meydana gelir.

Merge conflict, Git'in, birleştirilmek istenen dosyada birden fazla değişiklik olduğu için hangi değişikliği kullanacağını bilemediği durumlarda ortaya çıkar. Bu durumda, Git kullanıcıya, birleştirme işlemi sırasında hangi değişikliklerin korunacağına karar verme imkanı sağlar.

Merge conflict'i çözmek için, kullanıcıların Git deposunda bulunan dosyaları açarak değişiklikleri manuel olarak birleştirmesi gerekebilir. İki farklı değişikliğin aynı satırda yapılması durumunda, Git kullanıcının hangi değişikliği koruyacağına karar vermesini ister. Kullanıcı bu kararı verip, değişiklikleri kaydettiğinde, merge conflict çözülmüş olur.

8. Merge conflict'i nasıl çözeriz?

Öncelikle, hangi dosyada merge conflict olduğunu belirlemeniz gerekiyor. Bu bilgiyi, git status komutunu kullanarak öğrenebiliriz. Merge conflict olduğu dosyalar kırmızı renkte gösterilecektir.
Merge conflict'in olduğu dosyayı açılır ve conflict'in olduğu satırlar bulunur. Conflict'in olduğu satırlar, Git tarafından işaretlenir.

Bu işaretlemeler, benim branch'imdeki değişiklikleri (HEAD), diğer branch'teki değişikliklerle (other-branch) karşılaştırmak için kullanılır.

Conflict'in olduğu satırlarda, benim değişikliklerim ve diğer branch'teki değişiklikleri dikkate alarak, yeni bir değişiklik oluşturulur. Bu değişikliği, HEAD ve other-branch arasında birleştirdiğinizden emin olunmalı variable değerleri eşitlenmelidir.
Değişiklikler kaydedilir ve conflict'i çözmek için git add komutunu kullanarak değişiklikleri staged'a eklenir.
Son olarak, git commit komutu ile bir commit oluşturun ve commit mesajına, merge conflict'in çözüldüğünü belirtilir.
Merge işlemini tamamlamak için, oluşturduğunuz commit'i uzak sunucuya göndermek için git push komutunu kullanılır.
