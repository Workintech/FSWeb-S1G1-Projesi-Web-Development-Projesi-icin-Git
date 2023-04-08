# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Git, açık kaynak kodlu bir versiyon kontrol sistemidir. Yazılım geliştirme süreçlerinde kullanılır ve birden fazla kişi tarafından aynı projenin üzerinde çalışılmasına olanak sağlar. Git, kodun farklı sürümlerinin saklanmasına, yönetilmesine, karşılaştırılmasına ve birleştirilmesine olanak tanır. Bu özellikleri sayesinde, yazılım geliştirme ekibi üyeleri arasında verimli bir işbirliği sağlar ve kod değişikliklerinin takibi ve yönetimi kolaylaşır.

2. Git ile GitHub arasında ne fark var?
Git, projelerin farklı sürümlerini yönetmek ve değişikliklerin takibini yapmak için kullanılan bir versiyon kontrol sistemi olarak kullanılır. Git, kullanıcıların projelerindeki herhangi bir dosyanın geçmişine gitmelerine, belirli bir sürümü geri yüklemelerine veya farklı sürümleri birleştirmelerine izin verir. Git ayrıca, merkezi bir sunucuya bağımlı olmaksızın, dağıtık bir yapıda çalışır.

GitHub, Git'in barındırma hizmeti olarak kullanılır. Kullanıcılar, GitHub'a kaydolarak, Git projelerini çevrimiçi olarak barındırabilirler. GitHub, kullanıcılara kodlarını depolamalarına, işbirliği yapmalarına, sorunları yönetmelerine ve projelerini diğer kullanıcılarla paylaşmalarına izin verir. Ayrıca, açık kaynak projeleri için bir platform olarak kullanılan GitHub, milyonlarca açık kaynak projeye ev sahipliği yapmaktadır.

3. Neden bir branch oluşturuyoruz?
Paralel Çalışma: Çok sayıda insanın aynı projede çalıştığı durumlarda, herkesin aynı ana kodu üzerinde çalışması mümkün olmayabilir. Bu nedenle, her biri kendi dallarında (branch) çalışabilir ve sonunda hepsi birleştirilir.

Güvenlik: Ana kodda yapılacak değişiklikler, projeyi etkileyebilir ve hatta çalışmayı durdurabilir. Bu nedenle, bir "branch" oluşturarak, değişiklikleri test etmek ve gerekirse geri almak mümkün olur.

Versiyonlama: Projenin farklı versiyonlarını yönetmek için "branch"lar oluşturulabilir. Her bir versiyon farklı bir "branch" üzerinde yapılır ve sonunda birleştirilir.

Deneme: Yeni bir özellik veya değişiklik eklemek istediğinizde, önce bir "branch" oluşturarak değişikliği test edebilirsiniz. Eğer olumlu sonuç alırsanız, ana kod ile birleştirebilirsiniz.

4. Pull Request'in amacı nedir?
Pull Request, açık kaynaklı yazılım geliştirme sürecinde bir değişikliğin (örneğin yeni bir özellik ekleme veya hata düzeltme) ana kod tabanına entegrasyonu için bir öneri mekanizmasıdır.

Genellikle bir Pull Request, bir yazılım geliştiricisi tarafından oluşturulur ve diğer geliştiriclerin incelemesi için sunulur. Bu inceleme süreci, kodun kalitesini artırmaya ve kod tabanına eklenmeden önce hataları veya uyumsuzlukları belirlemeye yardımcı olur.

Ayrıca Pull Request, açık kaynaklı projelerde geliştiriciler arasındaki işbirliğini kolaylaştırır. Bir geliştirici, kod tabanına katkıda bulunmak istediğinde, bir Pull Request oluşturarak diğer geliştiricilerin incelemesi ve geri bildirimleriyle birlikte değişikliği daha kolay bir şekilde entegre edebilir. Bu, bir proje üzerinde çalışan geliştiricilerin işbirliği yapmalarını ve proje için daha yüksek kaliteli kod oluşturmalarını sağlar.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
Git'te bir branchten diğerine geçmek için git checkout komutu kullanılır. Eğer isim-soyisim branch'inde çalışıyorsanız ve main branch'ine geçmek istiyorsanız git checkout main komutunu kullanabilirsiniz. Bu komut, main branch'ine geçiş yapmanızı sağlayacaktır.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch komutu, uzak bir depodaki (remote repository) tüm değişiklikleri yerel depoya indirir, ancak bu değişiklikleri yereldeki mevcut çalışma kopyasına birleştirmez. Yani, git fetch işlemi ile uzak depodaki son durumun bir kopyası elde edersiniz, ancak mevcut çalışma kopyanız aynı kalır. Bu, diğer kullanıcıların uzak depoda yaptıkları değişiklikleri görmek istediğiniz ancak kendi çalışmalarınızda herhangi bir değişiklik yapmadığınız zamanlarda kullanışlıdır.

git merge komutu, birleştirme işlemi yapar. Özellikle iki farklı dalı birleştirmek için kullanılır. git merge komutu, farklı bir dalda yapılan değişiklikleri mevcut dalınızla birleştirir ve sonucu yeni bir birleştirilmiş dal oluşturur.

git pull komutu ise git fetch ve git merge işlemlerini birleştirir. Yani, uzak depodaki değişiklikleri indirir (git fetch) ve bu değişiklikleri yerel çalışma kopyanızdaki değişikliklerle birleştirir (git merge). git pull, sıklıkla başka bir kullanıcının yaptığı değişiklikleri hızlı bir şekilde almak istediğiniz zamanlarda kullanılır.

Özetle, git fetch uzak depodaki değişiklikleri indirir ancak yerel çalışma kopyasına birleştirmez. git merge, farklı bir dalı mevcut dalınıza birleştirir. git pull ise git fetch ve git merge işlemlerini birleştirir ve uzak depodaki değişiklikleri indirir ve yerel çalışma kopyasına birleştirir.

7. Merge conflict nedir?
Bir yazılım projesinde birden fazla kişinin aynı dosyayı farklı şekillerde değiştirmesi sonucu ortaya çıkan bir durumdur. Bu durumda, sistem aynı dosyanın iki farklı sürümü olduğunu tespit eder ve hangi sürümün doğru olduğunu belirleyemez.

Bu durumda, kullanıcıların el ile dosyayı düzenlemesi ve çakışan bölümleri manuel olarak birleştirmesi gerekebilir. Bu işlem "çözme" olarak adlandırılır. Birleştirme çatışması, özellikle açık kaynaklı projelerde, birçok geliştiricinin aynı kod tabanını değiştirdiği durumlarda sık görülen bir durumdur.

Birleştirme çatışmalarını önlemek için, geliştiriciler sık sık kodlarını güncellemeli ve değişikliklerini yavaş yavaş gerçekleştirmelidirler. Ayrıca, çeşitli yazılım araçları da birleştirme çatışmalarını tespit etmek ve çözmek için kullanılabilir.

8. Merge conflict'i nasıl çözeriz?
Bir merge conflict, aynı dosyanın farklı sürümlerinin farklı dallarda değiştirildiği durumlarda ortaya çıkan bir durumdur. Bu durumda, git, değişiklikleri otomatik olarak birleştiremez ve bu nedenle çakışmalar meydana gelir.

Merge conflict çözmek için aşağıdaki adımları takip edebilirsiniz:

Git'in hangi dosyaları değiştiremediğini ve hangi çakışmaların meydana geldiğini belirlemek için "git status" komutunu kullanın.

Çakışmaları düzeltmek için dosyaları açın ve değişiklikleri manuel olarak birleştirin. Bu, değişiklikleri karşılaştırmak ve çakışmaları çözmek için bir metin editörü kullanabileceğiniz anlamına gelir.

Değişiklikleri birleştirdikten sonra, dosyaları kaydedin ve birleştirme sürecini tamamlamak için "git add" komutunu kullanın.

Ardından, birleştirme işlemini tamamlamak ve değişiklikleri uzak sunucuya göndermek için "git commit" komutunu kullanın.

Eğer gerekiyorsa, birleştirme işlemi sırasında yapılan değişiklikleri geri almak için "git merge --abort" komutunu kullanabilirsiniz.

Merge conflict'i çözmek, bazen zaman alabilir ve manuel olarak birleştirme gerektirir. Ancak bu, git'in veri bütünlüğünü korumak için yaptığı bir güvenlik önlemidir ve git'in sunduğu güçlü işbirliği özellikleri sayesinde, çoğu durumda çakışmaları başarıyla çözebilirsiniz.