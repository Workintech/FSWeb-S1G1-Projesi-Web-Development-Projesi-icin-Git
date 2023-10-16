## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
1- Git, yazılım geliştirme süreçlerinde kullanılan, hız odaklı, dağıtık çalışan bir sürüm kontrol ve kaynak kod yönetim sistemidir.
2. Git ile GitHub arasında ne fark var? 
2- Git bir versiyon kontrol sistemidir. GitHub ise bu versiyon kontrol sistemi ile kullandığımız projeleri depolayabildiğimiz bir portaldır.
3. Neden bir branch oluşturuyoruz? 
3- Branch oluşturmak kullanıcıya çalıştığı projenin farklı versiyonlarına erişmesini sağlar. Kullanıcı, projesine bir yenilik eklemek istediğinde, yaptığı değişiklik projenin çalışmasını olumsuz etkileyebilir. Bu gibi durumlarda projemizin o anki halini bozmamak için branch kullanabiliriz.
4. Pull Request'in amacı nedir?
4- Pull request,proje üzerinde bizim tarafımıznda yapılan yeni değişiklerin,asıl projeye aktarılması için söylenen istektir.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
5- $ git checkout <branch_name> komutu ile diğer branch'e geçiş yapabiliriz.
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
6- Git fetch'i kullandığımızda, uzak depodan local çalışma branchimize değişiklikleri commit etmeden ekleriz. Git pull'dan farklı olarak fetching, değişiklikleri local brancheşubenize göndermeden önce gözden geçirmemize olanak tanır. 
Git pull,uzak sunucudaki repository'de değişikliğe uğramış ya da yeni eklenmiş dosyalar varsa bunları indirir ve yereldeki repository ile birleştirir.
Git Merge,Git'de merge işlemi başka bir branch'deki değişiklikleri üzerinde çalıştığınız kendi branch'inize entegre etme işlemidir. Git merge işlemi sırasında değişikliklerin çoğunu sizin için otomatik olarak entegre eder.
7. Merge conflict nedir?
7- Merge conflit,iki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır.
8. Merge conflict'i nasıl çözeriz?
8- Başka satır değişikliklerinden kaynaklanan bir merge conflit'i çözmek için, farklı branchlerden hangi değişikliklerin yeni bir commit'e dahil edileceğini seçmeliyiz.Bu branchleri birleştirmeden önce bu merge conflit'i yeni bir commitle çözmemiz gerekir
