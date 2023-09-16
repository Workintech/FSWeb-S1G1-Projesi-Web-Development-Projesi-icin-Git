# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Git, Açık Kaynak Dağıtılmış Sürüm Kontrol Sistemi(Open Source Distributed Version Control System)'dir.
2. Git ile GitHub arasında ne fark var?
Git sürüm kontrol sistemidir,GİTHUB git dosyalarının barındırıldığı bulut tabanlı internet sitesidir.
3. Neden bir branch oluşturuyoruz?
Üzerinde çalışılan kaynak kodun bir kopyasını oluşturarak geliştirmelerin orijinal koddan bağımsız olarak ilerlemesini sağlamak için branch oluşturulur.
4. Pull Request'in amacı nedir?
Bir dalda yaptığınız değişikliği başka bir dala aktarmayı talep etmemizi sağlar.
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git switch 'mehmetsait-guraslan'
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız..
Git fetch, uzaktaki bir deponun dosyalarını, anlık görüntülerini ve referanslarını yerel deponuza indiren bir komuttur. Git Merge iki branchi birleştirir. Git Pull bir deponun yerel sürümünü remote olarak güncellemek için kullanılan bir git komutudur.
7. Merge conflict nedir?
Çakışmadır.İki kişi aynı kodu değişştirir merge edemezse çakışma olur.
8. Merge conflict'i nasıl çözeriz?
Git conflict çözmek için, kullanıcının ilk olarak dosyayı açması ve çatışmalı bölümleri bulması gerekir. Daha sonra, çatışmalı bölümleri manuel olarak düzenlemek ve Git'e tekrar birleştirme işlemini yapması gerekir.