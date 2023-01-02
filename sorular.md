## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
Git, yazılım geliştirmede kullanılan bir versiyon kontrol sistemidir. Git, projelerde yapılan değişikliklerin kaydedilmesine ve ihtiyaç duyulduğunda kolaylıkla erişilebilmesine olanak sağlar
2. Git ile GitHub arasında ne fark var?
Git kod geçmişinin yönetilmesi takip edilmesine olanak sağlayan bir versiyon kontrol sistemidir, GitHub ise  Git depolarını yönetmeye yarayan bulut tabanlı bir sistemdir paylaşım olanağı sağlar.
3. Neden bir branch oluşturuyoruz? 
Git projemizde değişiklik yapmak istediğimiz kısımları ana projeyi değiştirmeden ayrı bir yerde değiştirme olanağı sunduğu için branch özelliğini kullanıyoruz. Branch özelliği projelerin karışık ve anlaşılmaz hale gelmesini önlüyor. 
4. Pull Request'in amacı nedir?
Değişiklik yaptığımız bir dosyayı ana proje ile paylaşmak için kullanılır. Yaptığımız değişiklikleri diğer kullanıcılar görebilir.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
git checkout -main branch
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
Git fetch kendi repomuzda değişiklikleri görme ve düzenleme imkanı verir ve veriler git dizininde güncellenir. Git merge ise birlikte çalışma için branchlerin birleştirildiği bir adımdır. Git pull komutu yapılan değişiklikleri kendi repomuzdan ana repoya direkt olarak getirir ve bu esnada çatışma ihtimalleri ortaya çıkabilir.
7. Merge conflict nedir?
Bir dosyanın aynı satırında birbiriyle çakışan bir değişiklik yapıldığında veya bir dosya üzerinde çalışılırken başka biri tarafından bu dosya silindiğinde bu durum ortaya çıkar.
8. Merge conflict'i nasıl çözeriz?
Dosyayı düzenledikten sonra, yeni birleştirilmiş içeriği hazırlamak için git add a komutunu kullanabiliriz. Son adım, git commit komutunun yardımıyla yeni bir commit oluşturmaktır.