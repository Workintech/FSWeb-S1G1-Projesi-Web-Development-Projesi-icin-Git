# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

 Yazılım geliştirme sürecinde kullanılan bir versiyon kontrol sistemidir.

2. Git ile GitHub arasında ne fark var?

 Git proje yaparken projenin istediğimiz versiyonuna ulaşmamızı, değişikler yapmamızı sağlayan bir araçtır.
 GitHub ise projelerin depolandığı,farklı projelere erişim sağlayabildiğimiz bir sunucudur. 

3. Neden bir branch oluşturuyoruz?

 Çalıştığımız projede değişiklik yapmak istediğimizde yaptığımız değişikliğin projenin  o anki halini etkilemesini istemedğimizde yeni branch oluşturabiliriz.

4. Pull Request'in amacı nedir?

 Fork ettiğimiz bir proje üzerinde çalışıp, yaptığımız değişiklikleri proje sahiblerinin görmesi için pull request kullanılması gerekir.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
 git-checkout 'gitmek istediğimiz branch'. main branch'e geçmek için git checkout main komutunu kullanabilirim.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

 git fetch remote depodaki değişiklikleri local depoya indirir ama uygulamaz.
 git merge başka branchlerde yapılan değişklikleri birleştirmek istediğimizde kullanılır.
 git pull remote depodaki değişiklikleri local depoya indirip uygular. git pull= git fetch+ git merge diyebiliriz.
  
7. Merge conflict nedir?
 Aynı proje üzerinde çalışan birden fazla kişinin aynı dosyayı ve aynı satırı değiştirmesi ile merge edilemezse veya bir kişi bir dosya üzerinde çalışırken diğer kişi dosyayı silmesi ile
 çakışma sorundur.

8. Merge conflict'i nasıl çözeriz?
 ilk yapmamız gereken çakışmanın neden olduğunu bulmaktır. git status konumunu kullanarak entegre edilen dosyaları görebiliriz.
 Eğer problem birden fazla kişinin aynı dosya aynı satırda değişiklik yapması ise değişiklik yapan kişilerin hangi değişkliğin geçerli olacağına karar vermesi gerekir.
 Eğer problem bir kişinin dosya üzerinde çalışırken diğer kişinin o dosyayı silmesi ise git status konumunu kullanarak silinen dosyayı görüntüledikten sonra silinen dosya geri alınmak istenirse git add konumu kullanılarak dosya eklenebilir. Dosyayı silmek isteyen kişi git rm kullanarak dosyayı silebilir ve değişiklikler commit edilebilir.  
