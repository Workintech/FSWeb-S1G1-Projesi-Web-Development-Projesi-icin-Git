## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
Git, Açık Kaynak Dağıtılmış Sürüm Kontrol Sistemi(Open Source Distributed Version Control System)'dir. Yani herkese açık kodların sunulduğu ve bu kodların başka yazılımcılar tarafından gelişirilebildiği yerdir.

2. Git ile GitHub arasında ne fark var?
Git bu kodların yazıldığı github ise depolandığı ve payalaşıldığı alan denebilir.
3. Neden bir branch oluşturuyoruz? 
 Üzerinde çalışılan kaynak kodun bir kopyasını oluşturarak geliştirmelerin orijinal koddan bağımsız olarak ilerlemesini sağlayabilmek için.
4. Pull Request'in amacı nedir?
Amaç kod üzerinde giderilen veya geliştirilen bir ayrıntının kodun asıl sahibine yapılan geri dönüşle mevcut yazılımı daha iyi hale getirmekir.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
git branch komutunu kullanırız.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
 git merge komutu, git branch tarafından oluşturulan bağımsız geliştirme satırlarını almanızı ve bunları tek bir branch'ta birleştirmenizi sağlar.
 git pull komutu, geliştirilen dosyanın son halini almamızı sağlar.
 git fetch, “yerel depomu uzaktaki deponun içeriğine güncelle” anlamına gelir.
7. Merge conflict nedir?
İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır. 
8. Merge conflict'i nasıl çözeriz?
Kodu yazan belli bir grup varsa bu arkadaşlarına kodun hangi satır ve sütununda çalışma yaptığını iletirse bu durum engellenmiş olur veya grubu yöneten yetkili baştan herkese ne yapması gerektiğini anlatır böylelikle karşıklık yaşanmaz.
