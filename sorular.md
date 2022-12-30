## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.


Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
Git geliştirdiğimiz bir projenin üzerinde değişiklik yapmamızı sağlar.Aynı zamanda projeyi korur ve üzerinde rahat değişiklikler yapabiliriz.
2. Git ile GitHub arasında ne fark var?
GitHub yaptığımız projeleri paylaşmamızı sağlayan, bir projede birden çok kişinin ortaklaşa çalışmasını sağlayan bir araçtır.
3. Neden bir branch oluşturuyoruz? 
Branch bir projemizde yaptığımız değişiklik için farklı bir yol sunar.Yaptığımız değişiklikte projenin çalışması olumsuz etkilenir veya vazgeçersek ana projenin korunmasını sağlar.
4. Pull Request'in amacı nedir?
Projede yapılan değişikliklerin herkese paylaşılmasını sağlar.Eğer ortak yürütülen bir proje ise proje sahibinin veya diğer çalışanların onayı ile projeye aktarılır.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
git checkout.
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch uzak bir depodan gelen dosyaları yalnızca alır, birleştirmez ve mevcut projeye eklemez.Git merge komutu ise depodan alınan bu dosyaları kodları yerel depoda birleştirir.Git pull komutu ise bu iki komutun birleşimi olarak hem alır hem birleştirir.
7. Merge conflict nedir?
İki kişi aynı satırda ve yerde değişiklik yaparsa bu durumda çakışma olur. Bunda da conflict denir.
8. Merge conflict'i nasıl çözeriz?
Git status komutu ile branch'imizde entegre edilmemiş komutları görebiliriz.Daha sonra conflict olan dosyayı açarak çakışma olan satırları düzeltiriz.Daha sonra git commit işlemi ile conflict çözme işlemini tamamlarız.Elbette daha detaylı ve karmaşık çözümleri gerektiren durumlarla da karşılaşabiliriz fakat temel olarak bu şekilde de anlatılabilir.
