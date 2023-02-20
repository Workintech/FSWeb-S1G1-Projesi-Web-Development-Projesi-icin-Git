## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir? 
   Git, Açık Kaynak Dağıtılmış Sürüm Kontrol Sistemi(Open Source Distributed Version Control System)'dir.

2. Git ile GitHub arasında ne fark var?
   Git bir versiyon kontrol sistemidir. GitHub ise bu versiyon kontrol sistemi ile kullandığımız projeleri depolayabildiğimiz bir portal diyebiliriz.

3. Neden bir branch oluşturuyoruz?
   Branch, üzerinde çalışılan kaynak kodun bir kopyasını oluşturarak geliştirmelerin orijinal koddan bağımsız olarak ilerlemesini sağlamak için kullanılır.

4. Pull Request'in amacı nedir?
   Pull Request ile; Fork ettiğimiz bir projenin üzerinde çalışıp, projede yaptığımız değişiklikleri, projenin sahibine göndererek kısaca: "ben projede değişiklikleri yaptım, sen de bu bu değişiklikleri onayla ve projene Merge et, ben de katkı sağlamış olayım" diyerek projeye faydalı katkılar sağlanması amaçlanmaktadır. 

5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
    git checkout 'BranchName' yani örneğe uygulayacak olursak; "git checkout main".

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
    Git Fetch ve Git Pull arasındaki temel fark; Git Fetch’in kaynaktan en yeni meta veri bilgilerini geri yüklemek için yerel git’inizi gösteren komut olmasıdır. Herhangi bir dosya aktarmaz. Daha çok değişikliklerin mevcut olup olmadığını bulmak için verileri incelemek gibidir, oysa Git Pull tüm değişiklikleri deponuza çekmekle birlikte aynı şeyi yapar.
    Git Merge yani Merging ise, en basit anlamda herhangi bir brach'de yaptığımız değişiklikleri master branch'imiz ile birleştirme veya master branch'e entegre etme işlemidir.

7. Merge conflict nedir?
   İki kişinin aynı dosyayı ve aynı satırı değiştirmesi durumunda, Git otomatik olarak bu değişiklikleri Merge edemezse bu durumda Merge Conflict yani çakışma ortaya çıkar. 

8. Merge conflict'i nasıl çözeriz?
   Merge Conflict (çakışma) ortaya çıkması durumunda, çakışmalarını çözmek için gereken adımları azaltabilecek birkaç adım vardır.
   1) Çakışan bir dosyayı çözmenin en kolay yolu dosyayı açıp gerekli değişiklikleri yapmaktır.
   2) Dosyayı düzenledikten sonra, yeni birleştirilmiş içeriği hazırlamak için birleştirilmiş içeriği gösterecek bir komut eklemek için git'i kullanabiliriz.
   3) Son adım, git commit komutunun yardımıyla yeni bir taahhüt oluşturmaktır.
   4) Git, birleştirmeyi sonlandırmak için yeni bir birleştirme taahhüdü oluşturacaktır.
   5) Çakışmaları çözmede önemli bir rol oynayabilecek Git komutlarına bakmak gerekirse; 
      - git log --merge
      - git diff 
      - git checkout 
      - git reset --mixed 
      - git merge --abort
      - git reset