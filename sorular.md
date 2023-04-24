# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
 Açık kaynak kodlu bir versiyon kontrol sistemidir.
2. Git ile GitHub arasında ne fark var?
 GitHub Git temelli bir paylaşım sistemidir.
3. Neden bir branch oluşturuyoruz?
 Yapacağımız geliştirme veya yenilik main branchte sorun oluşturmamamsı için yeni bir branch açıp orda yazıyoruz.Testleri yapıldıktan sonra main branche merge ediyoruz.
4. Pull Request'in amacı nedir?
 Branch oluşturarak yaptığımız dğişiklikleri proje sahibine göndeririz.Proje sahibi kontrol sağlayıp onay verdiği durumda main branche ekleyebilir.
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
 git checkout main
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
 git fetch komutu ile uzak sunucudaki branchlerin bilgilerini lokalimize indirebiliriz. git merge ile farklı branch olarak yaptığımız değişiklikleri main branche eklemiş oluruz. git pull komutu ile projenin en güncel halini çekmek için kullanabiliriz.
7. Merge conflict nedir?
 İki branch aynı dosyalarda değişiklik yapıp merge etmek istediğinde karşılaştığımız sorundur.
8. Merge conflict'i nasıl çözeriz?
 Çakışma yaşanan branchler tespit edilip çakışmanın çözülmesi gerekir.Ekip çalışması yapılabilinir gerekli durumlarda.