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
1.Git yazılım geliştirme süreçlerinde adım adım kodlama işlemleri yapılırken (geçmiş kodlara dönebilmeyi kolaylaştırmak için ) kullanılan bir versiyon kontrol sisteminde denir.
2.Git bir versiyon kontrol sistemi iken Git hub bu kodların yüklendiği bir cloud sistemidir.
3.Branch oluşturmak kullanıcıya çalıştığı projenin farklı versiyonlarına erişmesini sağlar. Kullanıcı, projesine bir yenilik eklemek istediğinde, yaptığı değişiklik projenin çalışmasını olumsuz etkileyebilir. Bu gibi durumlarda projemizin o anki halini bozmamak için branch kullanabiliriz.
4.Yazılım kodunu aldığımız kaynak kodda bizim tarafımızdan yapılan iyileştirmeyi yada düzeltmeyi ana kod ile birleştirilmesi için kaynağa sunulmasıdır.
5.git branch "geçmek istediğimiz branch adı"
6.git fetch = yerel depoyu uzak deponun içeriğini güncellemektir. Yani yerel depodaki dosyalarda bozulacak dosyalar yada değiştirdiğimiz dosyaları etkileyecek bir şey varsa get fetch yaparak çalışmamızı korumuş oluruz.
  git pull = uzak depodaki bilgileri local depomuza olduğu gibi güncelleyip tüm dosyaları uzak depodaki hali ile güncellemiş olur.
  git merge = başka bir branch'deki değişiklikleri üzerinde çalıştığımız kendi branch'inize entegre etme işlemidir.
7.Merge conflict=İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır. 
8.Bu durumda çakışma yaşayan kişi gerekirse ekipteki diğer kişi ile beraber oturup çakışmayı çözdükten sonra merge işlemine devam etmelidir