# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

Git kısaca kodlar için oluşturulan bir versiyon kontrol sistemidir.

2. Git ile GitHub arasında ne fark var?

Git ve Github temel olarak aynı mantıkla çalışan sistemlerdir. GitHub Bulut tabanlı bir git sağlayıcısıdır.

3. Neden bir branch oluşturuyoruz?

Çalışacağımız kodun doğrudan üzerinde çalışmak doğru olmaz(Çalışan bir sisteme müdahale etmek gibidir.). Bizde bir kopyasını oluşturup kendimiz sistemi aksatmadan üzerinde çalışmak için branch oluştururuz.


4. Pull Request'in amacı nedir?

Branch oluşturup kod üzerindeki hatalar veya iyileştirmeleri tekrarda uzaktaki bağlantıya göndermektir.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?



6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

pull komutu merge ve fetch in birleşimi şeklindedir.ama değişiklikleri göstermektedir.
fetch komutu uzaktaki bir kodu locale taşır.ve kodu incelemek içindir.
pull komutu fetch ile aynı şekilde çalışır fakat, kendi kodlarınız burada aynı kod üzerinde çalışanlarla beraber çakışma ihtimali vardır.
merge ise başka bir branchteki değişiklikleri kendi branchınıza entegre etmek birleştirmek için kullanılır.

7. Merge conflict nedir?

iki kişi aynı dosyayı aynı satırı değiştirince git merge edemezse bu sorun oluşur.

8. Merge conflict'i nasıl çözeriz?

iki kişi çalıştığını düşünürsek aynı dosya aynı satır üzerinde çakışmayı beraber çözmeleri gerekir. çözüldükten sonra merge işlemine devam edilir.

melih güçlü