## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
2. Git ile GitHub arasında ne fark var?
3. Neden bir branch oluşturuyoruz? 
4. Pull Request'in amacı nedir?
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
7. Merge conflict nedir?
8. Merge conflict'i nasıl çözeriz?

Cevaplar
1.Git, bir versiyon kontrol sistemidir. Projenin kaynak kodlarının değişikliklerini takip etmek, 
farklı sürümlerini oluşturmak ve yönetmek için kullanılır.
2.GitHub, Git'in barındırma hizmetidir. Git'te oluşturulan projelerin uzaktaki bir sunucuda depolanmasını sağlar ve proje paylaşımı, 
işbirliği ve takım çalışması için kullanılır.
3.Branch, projenin ana kaynak kodundan farklı bir yol izlemek istediğinizde oluşturulur. 
Örneğin, yeni bir özellik eklemek veya bir hata düzeltmek için, 
ana kodu değiştirmeden önce bir branch oluşturarak, 
değişiklikleri ayrı bir alanda yapabilirsiniz. 
Bu, birden fazla kişinin aynı projede çalışması durumunda özellikle faydalıdır.
4.Pull Request, GitHub gibi barındırma hizmetlerinde, 
bir branch'teki değişikliklerin ana kod tabanına birleştirilmesi isteğidir. 
Başka bir deyişle, bir kişi bir branch'te değişiklik yapar ve bu değişiklikleri ana koda entegre etmek istediğinde, 
bir Pull Request oluşturur. Bu, diğer kullanıcıların bu değişiklikleri incelemesine, 
tartışmasına ve onaylamasına olanak tanır.
5.'git checkout main' komutunu kullanarak ADINIZ-SOYADINIZ branch'inden main branch'ine geçebilirsiniz.
6.'git fetch', uzak depodaki (remote) değişiklikleri lokal depoya kopyalar ancak yerel dosyaları güncellemez.
 'git merge', farklı branch'lerdeki değişiklikleri birleştirir. 'git pull', uzaktaki değişiklikleri çeker (fetch) ve
 yerel dosyaları günceller (merge).
 Yani, 'git pull' aslında 'git fetch' ve 'git merge' işlemlerinin birleşimini yapar.
7.Merge conflict, farklı branch'lerde aynı dosyayı değiştirip kaydettiğinizde veya bir dosya silindiğinde ortaya çıkar.
 Bu, Git'in hangi değişiklikleri birleştireceğine karar verememesi nedeniyle oluşur. 
Git, bir conflict olduğunda, hangi dosyalarda conflict olduğunu size bildirir.
8.Merge conflict'i çözmek için, Git'in conflict olduğu dosyaları işaretleyen özel işaretleyicileri
 kullanarak değişiklikleri birleştirmeniz gerekir. Değişiklikleri birleştirirken, hangi değişikliğin
 korunacağını seçmeniz ve tüm işaretleyicileri kaldırmanız gerekebilir. Daha sonra, değişiklikleri
 kaydedip, bir commit oluşturmanız ve conflict çözüldüğünde Pull Request'i birleştirmemiz gerekir.