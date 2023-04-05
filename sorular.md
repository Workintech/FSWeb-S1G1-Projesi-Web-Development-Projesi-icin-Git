# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

Cevap : Git, bir versiyon kontrol sistemidir.

2. Git ile GitHub arasında ne fark var?

Cevap : Git, bir versiyon kontrol sistemi yazılımıdır. Github ise web tabanlı depolama ve paylaşım platformudur. Github, git üzerine inşa edilmiş bir hizmettir.  

3. Neden bir branch oluşturuyoruz?

Cevap : 

a) Main branch'dan izole şekilde çalışmamızı sağlar.
b) Main branch'da yaptığımız değişiklikler projenin farklı alanlarını olumsuz etkileyebilir. Riski minimize etmek için main branch'dan bağımsız branch oluştururuz.
c) Yaptığımız değişiklikleri test etmek için kullanabiliriz.
d) Oluşturduğumuz branchlerle projenin geçmişine dönebiliriz. Eski bir branch'da saklanan değişiklikleri geri alabiliriz.

Özetle main branchı riske atmayacak şekilde proje içerisinde değişiklikler ve geliştirmeler yapmamızı sağlar.

4. Pull Request'in amacı nedir?

Cevap : Bir branch'da yaptığımız değişiklikleri main branch veya başka bir branch ile birleştirilmesi için yaptığımız bir istektir. Yaptığımız değişiklikler proje yöneticisi veya geliştiricilerin onayına sunulur.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

Cevap : 

ismailc@ICNB MINGW64 ~/Desktop/projects/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git (ismail-cehreli)
$ git checkout main
Switched to branch 'main'
ismailc@ICNB MINGW64 ~/Desktop/projects/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git (main)


6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

Cevap : 

git fetch : Uzak repository'deki bilgileri getirir ve bir referans olarak kaydeder.
git merge : Uzaktan gelen referans bilgilerini merge komutu ile istersek birleştirebiliriz.
git pull : Uzak repository'deki değişiklikleri indirir ve localdeki çalışma dizinimizdekilerle birleştirir ve çalışma alanımızı en güncmel hale getirir. Git fetch ve git merge komutunu tek seferde uygulamak istediğimizde git pull kullanırız.


7. Merge conflict nedir?

Cevap : 

Aynı dosya üzerinde iki yada daha fazla kişinin yaptığı değişikliklerin hangisinin doğru olduğunu git bilemez. Bu durumda merge conflict oluşur.

8. Merge conflict'i nasıl çözeriz?

Cevap : 

index.html adında bir dosya var. Ben ve ekip arkadaşım aynı satırı değiştirmeye çalıştık. Ben index.html dosyasındaki Hello World! saıtırını Hello Git! olarak değiştirdim fakat diğer ekip arkadaşımda bu satırı Hello Github! olarak değiştirdi. Ben yaptığım değişikliği commitleyerek main branch'e gönderdim. Diğer ekip arkadaşım ise aynı satırda yaptığı değişiklik sonrasında commitleyerek main branch'e gönderdi. Ekip arkadaşımın yaptığı değişikliği çekmek için git merge komutu kullandığımda aynı satırda değişiklik yaptığımız için hata alacağım. Çakışmayı tespit etmek için dosyayı açtığımda <<<head ile başlayan benim yaptığım değişiklikleri temsil eder, === ile başlayan ise ekip arkadaşımın yaptığı değişikliği temsil eder. Bu işaretler arasında tutmak istediğimize ekip arkadaşımla karar vermem gerekiyor. Benim yazdığım kod satırında mütabık kaldıysak ilgili alanı Hello Git! olarak düzenledikten sonra aşağıdaki komtu satırlarını uygularım

git aded .
git commit -m "Fixed merge problem"
git push origin main
