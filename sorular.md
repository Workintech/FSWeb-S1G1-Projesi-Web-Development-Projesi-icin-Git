# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Bir projeyi başka kullanıcıların görüntüleyebilmesine, değişiklikler yapabilmesine olanak sağlayabilen açık kaynak dağıtılmış sürüm kontrol sistemidir. 

2. Git ile GitHub arasında ne fark var?
GitHub kar amacı güden bulut tabanlı git barındıran bir şirkettir. Yani git bir sistem github ise bu sistemi içinde barındıran bulut tabanlı bir şirkettir. 

3. Neden bir branch oluşturuyoruz?
Ana brach üzerinde emin olmadan bir değişiklik yapılmamasını ve ana branch çalışmasının sürekliliğini sağlamak için oluştururuz.

4. Pull Request'in amacı nedir?
Proje üzerinde yapılan değişiklikleri proje sahibinin onayına sunup projeye eklemesini talep etmektir.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout komutudur. git checkout main ile geçiş yapabiliriz.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git merge : branch'leri tek bir branch'te birleştirmeyi sağlar.
git pull : remote'taki değişiklikleri local projeye almayı sağlar. otomatikmen merge yapar.
git fetch: remote'taki değişiklieri local projeye çeker fakat merge yapmaz.
Yani git fetch ile remote'taki güncellemeyi alırız fakat lokalde değişikliğe neden olmaz ama git pull direkt locale ekleme yaptığı için değişikliğe neden olur.

7. Merge conflict nedir?
İki kişi aynı dosya ve aynı satır üzerinde değişiklik yaparsa otomatik olarak merge yapılamaz. Bu çakışmaya merge conflict denir.

8. Merge conflict'i nasıl çözeriz?
git status komutu ile yapılan değişikliklere bakarız. Conflict olan değişikleri tespit ederiz. bu şekilde çatışan bölümler düzeltilerek tekrar merge edilir.


