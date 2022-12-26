## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
-> Git, yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol sistemidir.

2. Git ile GitHub arasında ne fark var?
->Git, bir versiyon takip yazılımıdır. Lokal olarak bilgisayarda çalışır ve Github olmadan da Git'i kullanabilmek mümkündür. Git ile projelerinizin versiyonlamasını yapabilir ve bunu internete bile bağlanmadan kullanabilirsiniz. Herhangi bir kayıt işlemine ihtiyaç duymaz.
Github ise Git repository'lerinin cloud üzerinde saklandığı online bir servistir. Github'a kayıt olmanız gereklidir ve ek fayda olarak da başka kişilerin repository'lerine erişebilir ya da kendi repository'lerinize erişmelerini ve katkı sağlamalarını isteyebilirsiniz. Online bir servistir ve offline olarak kullanabilmeniz mümkün değildir.

3. Neden bir branch oluşturuyoruz? 
-> Branch oluşturmak kullanıcıya çalıştığı projenin farklı versiyonlarına erişmesini sağlar. Kullanıcı, projesine bir yenilik eklemek istediğinde, yaptığı değişiklik projenin çalışmasını olumsuz etkileyebilir. Bu gibi durumlarda projemizin o anki halini bozmamak için branch kullanabiliriz. 

4. Pull Request'in amacı nedir?
-> Pull request olarak göndermenin anlamı; proje üzerinde değişiklik yaptım, sen de bu değişiklikleri onaylarak projeni merge et demek anlamına gelir.

5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
->Öncelikle hangi branchte çalıştığımızı görmek için git branch komutunu kullanabiliriz. Daha sonra eğer main branch'e geçeceksek git checkout main metodunu kullanabiliriz.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
-> git fetch‘i herhangi bir zamanda refs/remotes// altındaki remote branch’inizi update etmek için kullanabilirsiniz. Bu operasyon refs/heads altındaki lokal branchleri değiştirmez. Aynı zamanda üzerinde çalıştığınız kopyayı değiştirmeden işlem yapma açısından da güvenlidir. Hatta bazı programcılar git fetch için bir cron job oluşturup periyodik bir şekilde arkaplanda fetch çalıştırabilir. git pull ise local bir branchi remote versiyona güncellemek için kullanırız. Aynı zamanda diğer remote brachleri de update etmek için yararlıdır. git merge işlemi başka bir branch'deki değişiklikleri üzerinde çalıştığınız kendi branch'inize entegre etme işlemidir. Git merge işlemi sırasında değişikliklerin çoğunu sizin için otomatik olarak entegre eder

7. Merge conflict nedir?
-> Merge conflict; birden fazla kişi, aynı dosyada aynı satırı değiştirmeye çalıştığında ya da biri o dosyayı silmişken diğer(ler)inin düzenleme yaptığı gibi durumlarda oluşan çakışmalardır. Bu durumda git, merge işlemi(birleştirme işlemi) yapamaz, bir nevi hangisini merge edeceğini bilemediği için hata verir.

8. Merge conflict'i nasıl çözeriz?
-> Çakışma oluştuğunda ilk yapmanız gereken şey çakışmanın neden olduğunu anlamak olmalıdır. Örneğin takım arkadaşınız aynı dosyada sizin de değiştirdiğiniz bir satırı mı değiştirdi veya aynı dosyada bir satır mı sildi veya sizinle aynı isimli yeni bir dosya mı oluşturdu?
git status komutunu çalıştırdığınızda Git size branch'inizde entegre edilmemiş dosyalar olduğunu söyleyecektir. Bu durumda çakışma yaşayan kişi gerekirse ekipteki diğer kişi ile beraber oturup çakışmayı çözdükten sonra merge işlemine devam etmelidir.
