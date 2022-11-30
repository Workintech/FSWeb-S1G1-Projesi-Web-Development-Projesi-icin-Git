## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
    versiyon kontrol sistemidir.
2. Git ile GitHub arasında ne fark var?
    Git versiyon kontrol sistemidir ve bir projenin birden fazla kişi ile yapılmasını sağlar.GitHub ise projelerin saklandığı uzak sunucudur.
3. Neden bir branch oluşturuyoruz? 
    Üzerinde çalışılan kaynak kodun bir kopyasını oluşturarak geliştirmelerin orijinal koddan bağımsız olarak ilerlemesini sağlayabiliriz. 
4. Pull Request'in amacı nedir?
    Örnek verecek olursak, master branch üzerinden checkout ettiğimiz bir başka branch üzerinde değişiklik yapıp, bu değişiklikleri master branch'e merge etmek istediğimiz zaman bir pull request oluştururuz ve o repoda çalışan herkesin değişiklikten haberi olur. İsteyen inceler, isteyen içeri alınmasını istemez, isteyen değişiklik talep eder vs.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
    git checkout 
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
    git fetch‘i herhangi bir zamanda refs/remotes/<remote>/ altındaki remote branch’inizi update etmek için kullanabiliriz.
    git pull‘u ise local bir branchi remote versiyona güncellemek için kullanırız.
    git merge işlemi başka bir branch'deki değişiklikleri üzerinde çalıştığınız kendi branch'inize entegre etme işlemidir.
7. Merge conflict nedir?
    İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır.
8. Merge conflict'i nasıl çözeriz?
    git status komutunu kullanırız ve hatanın nerede olduğunu bulup düzeltiriz.