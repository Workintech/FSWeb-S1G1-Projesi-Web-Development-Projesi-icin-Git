## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz.

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
   Açık kaynak dağıtılmış sürüm kontrol sistemidir.
2. Git ile GitHub arasında ne fark var?
   Git, bir projenin bir çok kişi ile aynı anda yapılabilmesini sağlar. Github ise projelerimizin depolandığı uzak sunucudur.
3. Neden bir branch oluşturuyoruz?
   Branch oluşturmak kullanıcıya çalıştığı projenin farklı versiyonlarına erişmesini sağlar. Kullanıcı, projesine bir yenilik eklemek istediğinde projenin o anki halini bozmamak için branch kullanabilir.
4. Pull Request'in amacı nedir?
   Forklama işleminden sonra yaptığımız değişikleri geliştiriciye atabiliriz.Bu duruma pull request denir. Geliştirici bu değişiklikleri mantıklı bulup bunları uygulayabilir.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
   git checkout komutunu kullanıyoruz. git checkout dedikten sonra gitmek istediğimiz branch adımızı yazmamız yeterli.
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
   git fetch, “yerel depomu uzaktaki deponun içeriğine güncelle” anlamına gelir.
   git merge, işlemi başka bir branch'deki değişiklikleri üzerinde çalıştığınız kendi branch'inize entegre etme işlemidir.
   git pull, bir deponun yerel sürümünü remote olarak güncellemek için kullanılan bir git komutudur.
7. Merge conflict nedir?
   İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır. Bu durumda çakışma yaşayan kişi gerekirse ekipteki diğer kişi ile beraber oturup çakışmayı çözdükten sonra merge işlemine devam etmelidir.
8. Merge conflict'i nasıl çözeriz?
   Bu durumda çakışma yaşayan kişi gerekirse ekipteki diğer kişi ile beraber oturup çakışmayı çözdükten sonra merge işlemine devam etmelidir.
