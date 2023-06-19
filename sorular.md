# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Git, açık kaynak kodlu proje paylaşım sistemi/teknolojisidir. 

2. Git ile GitHub arasında ne fark var?
Git, kod paylaşım teknolojisidir. Github ise bu teknolojinin kullanılmasını sağlayan cloud hizmetidir.

3. Neden bir branch oluşturuyoruz?
Kapsamlı bir çalışmaya başladığımız zaman ana projede değişiklik yapmadan sadece çalışma yaptığımız alana odaklanmamız gerekir. Branch sayesinde başka bir sekmede çalışıyormuş gibi değişikliklerimizi gerçekleştirebiliriz. 

4. Pull Request'in amacı nedir?
Pull Request sayesinde yaptığımız değişiklikler branch üzerinde çalışan diğer developerlara bildirilir. Bu sayede branchi merge etmeden önce üzerinde tartışma yapılabilir ve gerekli düzeltmeler sağlanabilir. 

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git brach dedikten sonra gitmek istediğimiz brach'ın adını yazarız. git brach main yazarım.
 
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch: Remote’daki tüm commitleri local’e çeker. Çekilen commitler remote branch’lar olarak depolanır, local olarak değil. Bu sayede local’deki kodla merge etmeden önce gözden geçirme şansı verir.
git merge: branch ile ayırıp çalıştığımız bölümleri git merge komutu ile ana projeye bağlarız.
git pull: Remote depodaki yakın zamanda yapılan çalışmaları local depomuza almamızı sağlayan komuttur. İki kodun birleşimi şeklinde düşünülebilir: git pull = git fetch + git merge

7. Merge conflict nedir?
Branch halindeyken aynı kod satırının değiştirilirse ve git otomatik merge edemezse bu çakışma sorunu meydana gelir.

8. Merge conflict'i nasıl çözeriz?
Kullanıcının ilk olarak dosyayı açması ve çatışmalı bölümleri bulması gerekir. Daha sonra, çatışmalı bölümler manuel olarak düzenlenmeli ve Git'te tekrar birleştirme işlemi yapılmalı.
