# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. 
Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. 
Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

git bir versiyon kontrol sistemidir.
yapılan bir proje ya da yazılımda girilen yeni bir satırı ya da güncellemeyi kontrol edebildiğimiz yanlış bir işlem yaptığımızda bir önceki duruma dönebildiğimiz 
bir yazılım arayüzüdür . ayrıca proje üzerinde yaptığımız ve yapılan her değişikliği ne zamn yapıldığını ,kim tarafından yapıldığını ve ne değişiklik yapıldığını 
görebildiğimiz bir platformdur.

2. Git ile GitHub arasında ne fark var?

git versiyon kontrol sistemidir github ise bir depo yani database diyebileceğimiz bir yerdir yeni gelişmelerin ve kütüphanelerin paylaşıldığı bir global alandır 
insanlar buradan kendisi için bir çözüm yolu bulabilirler sizin yazamadığınız ya da çözüm bulamadığınız bir kodu burada bulabilirsiniz.

3. Neden bir branch oluşturuyoruz?

branch yani kopya oluşturmamızın sebebi bir çok kişinin kod üzerinde oynama yapabilmesine ve herhangi bir hatada eski koda çalışan kodu ekleyip devam etmemize olanak
sağlaması açısından branch önemlidir.

4. Pull Request'in amacı nedir?

pull request kopyası alınan kodda yapılan değişikliği kodun ana sahibi olan kişiye yapılan değişikliği bildirme ve ekleme isteğidir. yani diyelim ki bir projede 10 kişi
çalışıyor ve bir değişiklik yaptı ve eklemek istiyor istemciye bunu ileterek istemcinin bu kodda nasıl bir değişiklik yaptığını görmesini sağlayıp kodu işletmesidir.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
(git checkout main) yazarak ana seçili istemciye geçebilirsiniz. 

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

git fetch:yerel depomda bulunan içeriği uzaktaki depoda bulunan veriyle güncelle
git merge:kopya üzerinde yaptığımız değişikliği asıl veri ile birleştirme ya da entegre etme yani tam haline getirme işlemi
git pull:uzakta bulunan depodaki değişmiş verileri alarak asıl çalışma halinde bulunan veri ile birleştirmek


7. Merge conflict nedir? 
iki kişi aynı dosyada aynı satırı değiştirmeye kalkarsa buna çakışma denir ve git hangi veriyi alacağını anlayamaz iki kişi oturup veriyi 
düzenler ve sisteme entegre etmeye devam eder

8. Merge conflict'i nasıl çözeriz?
kullanıcı değişiklik yaptığı dosyayı açmalı ve birbirine ters olan sıkıntılı kısımları bulmalı ve manuel olarak yazarak düzeltmelidir ve sonra merge yani 
birleştirme işlemine devam etmelidir.
