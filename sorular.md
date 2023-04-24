# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Açık Kaynak Dağıtılmış Sürüm Kontrol Sistemi(Open Source Distributed Version Control System)'dir


2. Git ile GitHub arasında ne fark var?

Git Açık Kaynak Dağıtılmış Sürüm Kontrol Sistemi GitHub ise bu sistemin bulut üzerinde depolamasını sağlayan bir yapı.
3. Neden bir branch oluşturuyoruz?

Yapacağımız değişiklikleri master branch bozmadan,kendimize ait bir çalışma alanı oluştururak tam olarak tamamlayıp test ettikten sonra master brancha ekleyebilmek için.

4. Pull Request'in amacı nedir?

Güncellediğimiz veya geliştirdiğimiz sistemi main brancha dahil etmek için talep gönderme işlemi.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

git merge 

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

git fetch: bulut sistemi üzerinden local bilgisayarımıza veri indirdiğimiz komuttur. indirilen bilgileri güncellemeden bırakır.
git merge: local bilgisayarımızdaki branchimizi master branchta birleştirme komutu.
git pull: bulut sistemi üzerinden local bilgisayarımıza veri indirdiğimiz komuttur. Çalışmanın bilgisayarınızdaki verilerle güncellemesini yapar.

7. Merge conflict nedir?
iki kişinin aynı kod dizisi üzerinde çalışmalarını yaptıktan sonra master brancha entegre ederken verilerin kodların çakışmasıdır. 

8. Merge conflict'i nasıl çözeriz?
Master Brancha merge etmeden önce git pull ile son çalışmaları alır düzeltmeler ve güncellemer üzerinde çalışmaları devam ettirir çakışma giderilince master brancha ekleme yaparız.
 
