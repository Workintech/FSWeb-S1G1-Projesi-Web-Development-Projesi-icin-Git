# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
   -- Versiyon kontrol merkezidir

2. Git ile GitHub arasında ne fark var?
   -- Git versiyon kontrol merkeziyken Github verileri kodlari repolari depolayip paylasabildigimiz bir bulut sistemidir.

3. Neden bir branch oluşturuyoruz?
   -- Main dosya zarar gormesin bir nevi devre acarak ana akimi kesmemek amacli acilir.
4. Pull Request'in amacı nedir?
   -- Kod veya dosya hazir oldugunda karsi tarafa bunu localine cekmesi icin gonderilen bir istek veya degisiklik talebinde bulunurken kullanilan istektir.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
   -- git checkout -m 'branch isim veya main' seklinde.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

-- git fetch: yani olanlari ceker pcye fakat merge olmadan.
-- git merge: birden fazla branchi birlestirmek icin kullanilir.
-- git pull: repolari lokale cekmek icin kullanilir fetchten farki merge olur.

7. Merge conflict nedir?
   -- Birden fazla kullanicinin ayni anda yapmaya calistigi islemden kaynaklanan catismaya denir.github'a gore de Birleştirme çakışmaları, bir dosyanın aynı satırında farkli değişiklikler yapıldığında veya bir kişi bir dosyayı düzenlerken diğeri aynı dosyayı sildiğinde ortaya çıkar.

8. Merge conflict'i nasıl çözeriz?
   -- Haberlesme yontemi sagliklidir.
