# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

1. Git, yazılım geliştirme sürçlerinde kullanılan bir versiyon kontrol sistemidir. Yaptığımız projeleri adım adım izleyebilir, kopyalayabilir ve ihtiyaç duyduğumuzda eski versiyonlara kolayca dönebiliriz.

2. Git ile GitHub arasında ne fark var?

2. Git bir version kontrol  sistemi, Github ise bu kontrol sistemi ile projeleri depolayabildiğimiz yer diyebiliriz. 

3. Neden bir branch oluşturuyoruz?

3. Çalıştığımız projenin farklı versiyonlarına ulaşmak için branch oluştururuz. 

4. Pull Request'in amacı nedir?

4. Fork ettiğimiz bir proje üzerinde , yaptığımız değişiklikler ile proje sahibine katkı sağlamaktır. 

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

5. git checkout master

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

6. Git Fetch: Kodu uzak depodan yerel depoya çeken bir komut
   Git Pull: Uzak depoda yakın zamanda yapılan değişiklikleri indiren ve bunları yerel bir depoda birleştiren bir komut. 
   Git Merge: Başka bir branchdeki değişiklikleri üzerine çalıştığımız kendi branchimize entegre işlemidir. 

7. Merge conflict nedir?

7. İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda çakışma oluşur. 

8. Merge conflict'i nasıl çözeriz?

8. Araştırdığım çözümlerden birisi: 
   Conflict gerçekleştikten sonra: 
   git reset HEAD~1 (yaptığımız değişiklikleri geri alıyoruz) 
   git commit -m "Çakışma giderildi"
   git push --force
