## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
Git yazılım üretiminde kullanılan versiyon kontrol sistemidir. Projemizde adım adım versiyonları
kopyalarını alarak ilerdeki ihtiyaçlarımıza göre dönüş sağlamamıza olanak sağlar.
2. Git ile GitHub arasında ne fark var?
Git versiyon kontrol sistemidir. GitHub ise projeleri depolayabildiğimiz bir servisidir.
3. Neden bir branch oluşturuyoruz?
Bazı değişikler projemizde negatif sonuçlar doğurabilir bu sebep ile branch kullanrak projemizin
anlık halini bozulmamısını sağlıyoruz. 
4. Pull Request'in amacı nedir?
Projede yapılan yenilik veya katkıların açık projeye sunulmasıdır.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
"git branch" ile branch kontrol ederim
"git checkout main" ile main branch geçiş yaparım
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
"git merge" : Farklı branchdeki değişikleri kendi branchimze entegre etmek içindir.
"git fetch" : Başka bir sunucunun projesindeki veriyi localimize indirmek içindir
"git pull"  : "git merge" ve "git fetch" komutlarını tek komutla yapar yani kaydeder
ve entegre eder.
7. Merge conflict nedir?
2 kişi aynı dosyayı ve aynı satırı değiştirirse git otomatik olarak entegre edemez bu 
sebep ile çakışma ortaya çıkar
8. Merge conflict'i nasıl çözeriz?
Bu durumda çakışma yaşayan kişi gerekirse ekipteki diğer kişi ile beraber 
oturup çakışmayı çözdükten sonra merge işlemine devam etmelidir.