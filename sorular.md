# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
	C: Kodlardaki değişiklikleri takip eden versiyon kontrol sistemidir.
2. Git ile GitHub arasında ne fark var?
	C: Git versiyon kontrol sistemi, Github ise git depoları için sunucudur.
3. Neden bir branch oluşturuyoruz?
	C: Projemizin eski halini korumak için oluştururuz.
4. Pull Request'in amacı nedir?
	C: Kodlarda yaptığımız değişiklikleri diğer kullanıcıların kullanımına sunmak.
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
	C: git checkout 'isim-soyisim' 
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
	C: git fecth yerel depoya uzaktaki depoda değişikliklerin olduğunu söyler. git pull uzaktaki depodaki değişiklikleri yerel depoda da günceller. git merge ise üstteki branch ile birleştirme yapar.
7. Merge conflict nedir?
	C: Aynı anda, aynı satır birden fazla kullanıcı tarafında değiştirilirse conflict olacaktır.
8. Merge conflict'i nasıl çözeriz?
	C: git reset HEAD ile yapılan değişiklikler geri alınır.