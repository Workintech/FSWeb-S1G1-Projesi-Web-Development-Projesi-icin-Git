## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir? Git, kısa süre içerisinde yazılımcıların vazgeçilmezleri arasına giren bir sürüm/versiyon kontrol sistemidir.
2. Git ile GitHub arasında ne fark var?  Git, açık kaynaklı bir sürüm kontrol sistemidir ve Github, Git deposu için bir barındırma hizmetidir
3. Neden bir branch oluşturuyoruz? Branch oluşturmak kullanıcıya çalıştığı projenin farklı versiyonlarına erişmesini sağlar. Kullanıcı, projesine bir yenilik eklemek istediğinde, yaptığı değişiklik projenin çalışmasını olumsuz etkileyebilir. Bu gibi durumlarda projemizin o anki halini bozmamak için branch kullanabiliriz. 
4. Pull Request'in amacı nedir? Git'te bir çekme isteği onayı süreci, proje sorumlularının çalışmanızı gözden geçirmesini sağlamayı içerecektir; Bundan sonra yorum yapacaklar veya çekme isteğiniz onaylanırsa değişikliklerinizi doğrudan ana depoda birleştireceklerdir.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz. git checkout main
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız. git fetch remote branch için kullanlır. git pull ise local versiyonu remote ile update etmek için.git merge ise localda bulunan dosyaları birleştirmek için.
7. Merge conflict nedir?İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır. 
8. Merge conflict'i nasıl çözeriz?Bu durumda çakışma yaşayan kişi gerekirse ekipteki diğer kişi ile beraber oturup çakışmayı çözdükten sonra merge işlemine devam etmelidir.
