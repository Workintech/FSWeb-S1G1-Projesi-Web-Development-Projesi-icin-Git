
# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Git, açık kaynak dağıtılmış sürüm kontrol sistemidir.
2. Git ile GitHub arasında ne fark var?
Github bulut tabanlı bir git barındırma hizmetidir.
3. Neden bir branch oluşturuyoruz?
Projenin ana kodundan kopyalanarak kodu bozmadan farkli özellikleri veya düzeltmeleri denemek için oluşturuyoruz.
4. Pull Request'in amacı nedir?
Yapılan değişikliklerin ana kodla birleştirmek için yapılan istek yapılması amacıyla kullanılır.
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout main
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch uzaktaki değişiklikleri getirir ve yerel branch'leri günceller, ancak yerelde değişiklik yapmaz.
git merge farklı branch'lerdeki değişiklikleri birleştirir ve yeni bir "merge commit" oluşturur.
git pull ise git fetch ve git merge komutlarını birleştirerek uzaktaki değişiklikleri çeker ve otomatik olarak yerel branch'e entegre eder.
7. Merge conflict nedir?
farklı branch'lerde aynı kod satırının farklı şekillerde değiştirildiği veya silindiği durumu ifade eder. 
8. Merge conflict'i nasıl çözeriz?
Git bu durumu otomatik olarak çözemez, geliştiricinin müdahalesini gerektirir. Geliştirici, çakışmayı elle çözerek değişiklikleri birleştirme yöntemini seçmelidir.
