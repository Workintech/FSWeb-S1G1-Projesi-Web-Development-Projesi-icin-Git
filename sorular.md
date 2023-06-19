# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Git, Açık Kaynak Dağıtılmış Sürüm Kontrol Sistemi(Open Source Distributed Version Control System)'dir.
2. Git ile GitHub arasında ne fark var?
GitHub, bulut tabanlı bir git barındırma hizmeti sunan kâr amaçlı bir şirketken Git bu şirketin içinde bulunan bir sistemdir
3. Neden bir branch oluşturuyoruz?
 Üzerinde çalışılan kaynak kodun bir kopyasını oluşturarak geliştirmelerin orijinal koddan bağımsız olarak ilerlemesini sağlamak için.
4. Pull Request'in amacı nedir?
pull talebi, başlangıçta oluşturduğunuz "fork"a karşı, oluşturduğumuz branch ile karşılaştırma yapılması için oluşturulur.
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
cd komudu ile istenilen branche geçebiliriz. Bunun için cd .. ile geriye gidip oradan cd Main Branch e geçiş yapabiliriz.
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
Diğer kişiler tarafından yapılan yeni işleri almak için git fetch'i kullanırız. Merge ile çatallanmış bir geçmişi tekrar bir araya getiririz. git pull geçerli yerel çalışma branch’ını (o an için kullanılan branch’ı) günceller. Özet olarak git fetch ile yeni işleri alırken git merge ile birleştirme git pull ile güncellemesini, yeni işleri yüklenmesini yaparız. 
7. Merge conflict nedir?
2 kişinin aynı satırı veya aynı dosyayı değiştirirken git bunu otomatik olarak merge yani birleştirmesini yapamadığı için oluşan çakışma sorunudur.
8. Merge conflict'i nasıl çözeriz?
Çakışma yaşayan kişi gerekirse ekipteki diğer kişi ile beraber oturup çakışmayı çözdükten sonra merge işlemine devam etmelidir.