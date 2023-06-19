# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir? Git açık kaynak dağıtılmış  sürüm kontrol sistemidir. Devam eden bir yazılım projesinde işler olduğu gibi devam ederken bir ya da birden fazla yazılımcı tarafından programı geliştirmeye olanak sağlayan bir programdır.


2. Git ile GitHub arasında ne fark var? Git local çalışma yapmayı sağlarken GitHub bu çalışmayı bulut gibi davranarak birden fazla kişiyle paylaşmamızı ve isteğe göre açık kaynak oluşturmamızı sağlar.

3. Neden bir branch oluşturuyoruz? Mevcut yazılıma gerekli değiştirmeyi yaparken oluşabilecek sorunlardan mevcut yazılımın etkilenmemesi için

4. Pull Request'in amacı nedir? Ortak yürüttüğümüz bir projede herhangi bir yazılımcı push komutu ile command ettiği değişiklikleri diğer yazılımcılara teslim eder, Onlar da pull request ile bunları kendi bilgisayarlarına çağırır.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın? git switch main 

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız. git fetch yerel depoyu uzaktaki deponun içeriğine günceller. git pull uzaktaki deponun değişikliklerini yerel depoya getirir. git merge, git branch ile bağımsızlaştırdığımız gelişme satırlarını almamızı ve bunları tek bir branchta birleştirmemizi sağlar.

7. Merge conflict nedir? iki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse  bu durumda çakışma olur ve buna merge conflict denir.

8. Merge conflict'i nasıl çözeriz? Çakışmayı yaşayan kişi ekipteki diğer kişi ile beraber oturup çakışmayı çözdükten ( ilgili satıra aynı kodu yazarak vs. )sonra merge işlemine devam etmelidir.
