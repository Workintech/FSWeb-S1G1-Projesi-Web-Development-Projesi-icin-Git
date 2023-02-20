## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?

Git, yazılım geliştirme sürecinde değişikliklerin yönetilmesi ve takip edilmesi için yaygın olarak kullanılan bir versiyon kontrol sistemi (version control system)dir. Linus Torvalds tarafından 2005 yılında geliştirilmiş ve açık kaynak lisansı altında dağıtılmaktadır

Git, tüm proje kodunu ve sürüm geçmişini depolayan "depo"ları oluşturma olanağı sağlar. Birden fazla geliştiricinin aynı projede çalışabilmesini ve diğerlerinin yaptığı değişiklikleri takip etmesini mümkün kılar. Geliştiriciler, Git'i ana dalın bağımsız olarak geliştirilip test edilebilen "dallar" oluşturmak için kullanabilirler. Değişiklikler tamamlandığında, dallar ana dala birleştirilebilir

Git, GitHub gibi Git depolarının barındırılabildiği ve kod üzerinde işbirliği yapılabildiği bir platformun da kullanımını sağlar. Popüler web siteleri ve yazılım projeleri arasında yer alan Git, güçlü özellikleri ve yaygın kullanımı sayesinde yazılım geliştirme sürecinde vazgeçilmez bir araç haline gelmiştir ve dünya genelinde birçok geliştirici tarafından kullanılmaktadır

2. Git ile GitHub arasında ne fark var?

Git ve GitHub farklı şeylerdir. Git, bir versiyon kontrol sistemi olarak kullanılan bir yazılımdır. GitHub ise, Git depolarını barındıran ve çevrimiçi bir kod barındırma ve işbirliği platformudur

3. Neden bir branch oluşturuyoruz? 

Bir branch oluşturmak, yazılım geliştirme sürecinde kodun bir kopyasını almak ve bağımsız olarak geliştirmek için kullanılır. Bu, geliştiricilerin ana dalda yapılan değişikliklerin ana kod tabanını etkilemesinden endişe etmeden yeni özellikler veya değişiklikler eklemelerine olanak tanır

4. Pull Request'in amacı nedir?

Pull Request, bir yazılım projesinde değişikliklerin yönetilmesi ve ana kod tabanına birleştirilmesi için kullanılan bir işlemdir. Bir geliştiricinin, kendi branch'inde yaptığı değişiklikleri ana dalda birleştirmek istediği zaman Pull Request oluşturabilir

5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.

Git'de, bir branch'ten diğerine geçmek için "git checkout" komutu kullanılır

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

git fetch: Uzak bir depodan değişiklikleri alır ve yerel Git depomuzda günceller. Ancak, bu komut, değişiklikleri yerel çalışma kopyamıza birleştirmez, yalnızca depodaki değişiklikleri yerel bir dalda takip etmemizi sağlar. Bu nedenle, bu komut, başka bir geliştiricinin yaptığı değişiklikleri görüntülemek ve yerel çalışma kopyasını güncellemek için kullanılır

git merge: Farklı Git dallarını birleştirir. Bu komut, bir veya daha fazla dalı birleştirerek, çalışma kopyasını, dalları birleştirirken değişiklikleri içerecek şekilde günceller. Örneğin, bir geliştirici, bir özellik dalında bir değişiklik yaptığında, bu değişiklik ana dal'a birleştirilmeden önce diğer geliştiriciler tarafından incelemeye alınabilir ve ana dal'da başka değişiklikler olduğunda, bu değişiklikler birleştirilerek uygun bir şekilde ana dal'a dahil edilebilir

git pull: Bu komut, git fetch ve git merge komutlarını birleştirir. Yani, uzaktaki değişiklikleri indirir ve yerel kopyayı güncellemek için yerel kopyayı değiştirir. Bu komut, uzaktaki değişiklikleri yerel kopyaya çekmek ve yerel kopyayı hızlı bir şekilde güncellemek için sıkça kullanılır

7. Merge conflict nedir?

Merge conflict, Git'te iki veya daha fazla değişiklikli dosyanın birleştirilirken karşılaşılan bir durumdur. Birleştirme işlemi sırasında, iki veya daha fazla farklı dalda yapılan değişikliklerin aynı satırları veya aynı dosyaları etkilemesi durumunda ortaya çıkabilir. Bu durumda, Git, iki farklı değişiklik arasında bir karar veremeyeceği için bir çakışma (conflict) oluşur

8. Merge conflict'i nasıl çözeriz?

Merge conflict'i çözmek için aşağıdaki adımları izleyebilirsiniz:

Çakışmayı belirleyin: Çakışmanın nerede olduğunu belirleyin ve hangi dosyaların çakıştığını kontrol edin.
Dosyaları açın: Çakışan dosyaları açın ve değişiklikleri inceleyin. Her bir değişikliği dikkatlice okuyun ve hangi değişikliğin tutulup hangisinin atılacağına karar verin.
Değişiklikleri düzenleyin: Dosyaları düzenleyin ve değişikliklerin doğru bir şekilde birleştirilmesini sağlayın. Hangi değişikliğin tutulacağına karar verirken, hangi değişikliğin daha önemli veya doğru olduğunu göz önünde bulundurun.
Değişiklikleri kaydedin: Değişiklikleri kaydedin ve değiştirilmiş dosyaları yeniden ekleyin. Bu, değişiklikleri depolamanıza ve commit etmenize olanak tanır.
Commit'i tamamlayın: Commit mesajınızı yazın ve değiştirilmiş dosyaları ana dala birleştirin

