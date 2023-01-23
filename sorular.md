## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
Git, yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol sistemidir. Git sayesinde yapacağımız projelerin adım adım versiyonlarının kopyalarını alarak daha sonra ihtiyaç duyduğumuzda aldığımız kopyalara yani versiyonlara kolayca dönebiliyoruz.
2. Git ile GitHub arasında ne fark var?
Git, bir sürüm kontrol sistemidir, Github ise, Git kullanan projeler için bir depolama servisidir.
3. Neden bir branch oluşturuyoruz?
 Branch oluşturmak kullanıcıya çalıştığı projenin farklı versiyonlarına erişmesini sağlar. Kullanıcı, projesine bir yenilik eklemek istediğinde, yaptığı değişiklik projenin çalışmasını olumsuz etkileyebilir. Bu gibi durumlarda projemizin o anki halini bozmamak için branch kullanabiliriz.
4. Pull Request'in amacı nedir?
Pull request talebi, temelde branch'dan sorumlu kişiden kodumuzu eklemesini istemektir. Ayrıca o kişinin kodda tam olarak neyi değiştirdiğimizi görmesine de yardımcı olur.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
git checkout "Gitmek istediğimiz branch ismi" komutuyla gidebiliriz.Örnek üzerinden gidecek olursak ; git checkout main komutuyla main branch'ine geçeriz.
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch, “yerel depomu uzaktaki deponun içeriğine güncelle” anlamına gelir.
Git'de merge işlemi başka bir branch'deki değişiklikleri üzerinde çalıştığınız kendi branch'inize entegre etme işlemidir. Git merge işlemi sırasında değişikliklerin çoğunu bizim için otomatik olarak entegre eder.
Uzak depoda bulunan tüm değişiklikleri yerel çalışma dizinine birleştirmek için git pull komutu kullanılır.
7. Merge conflict nedir?
İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır.
8. Merge conflict'i nasıl çözeriz?
Bu durumda çakışma yaşayan kişi gerekirse ekipteki diğer kişi ile beraber oturup çakışmayı çözdükten sonra merge işlemine devam etmelidir.