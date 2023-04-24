# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir? 
Open Source Distributed Version Control System
Versiyonlama bir çok çalışanı olan ekiplerde işlevsel oluyor. Tüm developerlar kendi branch'ında çalışıyor.
2. Git ile GitHub arasında ne fark var?
Github git hizmeti veren kar amacı güden bir cloud hizmetidir
3. Neden bir branch oluşturuyoruz?
Proje üzerinde asıl dosyaları bozmadan çalışabilmek için branch olusturuyoruz
4. Pull Request'in amacı nedir?
Remote'daki değişikliği kendi localime çekebilmek için kullanılıyor
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout main branch
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch uzaktaki bir deponun dosyalarını yerel deponuza indiren bir komuttur. Yerel deponuzun mevcut çalışma durumunu güncellemeden uzaktaki verileri indirir.
git pull  uzaktaki bir depodan verileri getirip indirirken yerel depoyu getirilen verilerle eşleşecek şekilde günceller.
git merge herhangi bir brach'de yaptığımız değişiklikleri master branch'imiz ile birleştirme veya master branch'e entegre etme işlemidir.
Git Pull = Git Fetch + Git Merge

7. Merge conflict nedir?
Git depolama sisteminde bir çatışma olarak tanımlanır. aynı dosyalarda farklı kullanıcılar çalışırsa conflict olabilir. 
8. Merge conflict'i nasıl çözeriz?
Kullanıcının dosyayı açması çakışmalı yeri bularak manuel olarak çakışmayı çözmesi ve ondan sonra tekrar merge etmesi gerekir. Çakışma komut satırı aracılığıyla da çözülebilir.