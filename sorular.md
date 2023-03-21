# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Git, bir versiyon kontrol sistemi yazılımıdır. Yazılım geliştirme süreçlerinde, özellikle de ekip halinde çalışıldığında, kodun değiştirilmesini, takibini ve paylaşımını kolaylaştırmak için kullanılır.
2. Git ile GitHub arasında ne fark var?
Git, bir versiyon kontrol sistemi yazılımıdır. Yazılım geliştirme süreçlerinde, özellikle de ekip halinde çalışıldığında, kodun değiştirilmesini, takibini ve paylaşımını kolaylaştırmak için kullanılır. Git, kodun farklı versiyonlarını, değişikliklerini, geri alınmalarını ve kollarını (branches) takip etmenizi sağlar.
GitHub ise, git tabanlı bir web tabanlı bir kod barındırma platformudur. Git ile geliştirilen projeleri GitHub'a yükleyerek, projelerinizi düzenleyebilir, paylaşabilir ve işbirliği yapabilirsiniz. Ayrıca, GitHub, projelerinizi halka açık veya özel olarak paylaşmanıza olanak tanır. GitHub, geliştiricilerin bir araya gelerek açık kaynaklı projeler geliştirmelerine de olanak sağlar.

3. Neden bir branch oluşturuyoruz?
Bir proje geliştirirken, birden fazla geliştiricinin aynı anda çalışması veya farklı özellikler veya hataları ele almak için farklı sürümler üzerinde çalışmak gerekebilir. Bu durumlarda, her bir sürüm veya özellik için ayrı bir "branch" oluşturmak faydalı olabilir.

Branch'ler, projenin ana kaynağından ayrılan, bağımsız bir kopyadır. Bu şekilde geliştiriciler, kendi branch'leri üzerinde çalışarak, ana kaynak dosyalarının zarar görmeden farklı özellikler veya hatalar üzerinde çalışabilirler.

4. Pull Request'in amacı nedir?
Bir yazılım projesinde kaynak kodunun bir branch'ten diğerine taşınması için geliştiricilerin birbirlerine talepte bulunmasına olanak tanıyan bir işlemdir.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout -main branch

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
"git fetch" komutu, bir Git depo sunucusundan değişiklikleri indirir, ancak yerel çalışma alanını güncelleştirmez. Yani, sunucudaki son değişiklikleri görüntülemek için kullanılır, ancak yerel dosyalar üzerinde herhangi bir değişiklik yapmaz.
Fetch işlemi, "git pull" işleminden farklıdır. Git pull, fetch işlemini de yapar, ancak ardından yerel branch ile remote branch'ı birleştirir. Bu nedenle, Git pull işlemi, yerel branch'ı güncelleştirirken, fetch işlemi sadece remote branch'ı güncelleştirir.
"git merge" komutu, farklı Git branch'lerini birleştirmek için kullanılan bir komuttur.

7. Merge conflict nedir?
 Git merge işlemi sırasında karşılaşılan bir sorundur. Bir merge işlemi yapılırken, farklı branch'lerde yapılan değişikliklerin aynı dosyada çakışması durumunda bir merge conflict oluşur. Bu durumda, Git hangi değişikliklerin korunacağını bilemez ve bir hata mesajı görüntüler.

8. Merge conflict'i nasıl çözeriz?
Merge conflict'in çözülmesi, çakışan değişikliklerin nasıl birleştirileceğine bağlıdır. Git, farklı araçlar kullanarak merge conflict'i çözmek için yardımcı olur. Çakışan dosyalar açılır ve değişiklikler gözden geçirilir. Geliştiriciler, hangi değişikliklerin korunacağına ve hangilerinin reddedileceğine karar verirler.