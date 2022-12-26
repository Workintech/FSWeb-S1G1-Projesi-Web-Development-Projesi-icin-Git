## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
* Git bir versiyon kontrol sistemidir.
2. Git ile GitHub arasında ne fark var?
* Git, bir versiyon takip yazılımıdır (bkz: VCS Nedir ve Nasıl Kullanılır?). Lokal olarak bilgisayarda çalışır ve Github olmadan da Git'i kullanabilmek mümkündür. Git ile projelreinizin versiyonlamasını yapabilir ve bunu internete bile bağlanmadan kullanabilirsiniz. Herhangi bir kayıt işlemine ihtiyaç duymaz.Github ise Git repository'lerinin cloud üzerinde saklandığı online bir servistir. Github'a kayıt olmanız gereklidir ve ek fayda olarak da başka kişilerin repository'lerine erişebilir ya da kendi repository'lerinize erişmelerini ve katkı sağlamalarını isteyebilirsiniz. Online bir servistir ve offline olarak kullanabilneniz mümkün değildir.
3. Neden bir branch oluşturuyoruz?
* Branch, sadece projenizi değiştirirken ya da güncellerken eski halini korumak ile kalmıyor. Projenize bir versiyon çıkarttığınız zaman her yeni versiyon için repository oluşturmak yerine her bir versiyon için farklı branchler açabiliyoruz. Böylece versiyonları bir arada kolayca takip edebilir ve erişebiliyoruz.
4. Pull Request'in amacı nedir?
* Branch'dan sorumlu kişiden kodunuzu eklemesini istemektir
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
* "git branch" ile branchları listeleyip kullanmak istediğimizi "git checkout BRANCH-İSMİ" şeklinde aktif hale getirebiliyoruz.
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
* **git fetch** herhangi bir zamanda refs/remotes/<remote>/ altındaki remote branch’inizi update etmek için kullanabilirsiniz.
* **git pull** ile local bir branchi remote versiyona güncellemek için kullanırız.
* **git merge** Diğer işlemleri mevcut branchinize entegre etmek için sonrasında merge uygulanır.
7. Merge conflict nedir?
* İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır.
8. Merge conflict'i nasıl çözeriz?
* --
