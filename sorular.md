# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

Versiyon kontrol sistemidir.

2. Git ile GitHub arasında ne fark var?
   Git bir versiyon kontrol sistemidir. GitHub ise bu versiyon kontrol sistemi ile kullandığımız projeleri depolayabildiğimiz bir portaldır.

3. Neden bir branch oluşturuyoruz?

Ana proje üzerinde çalışma yaparken ana proje kodlarına zarar vermemek için .

4. Pull Request'in amacı nedir?

Çekme İsteği (Pull Request) ve Birleştirme İsteği Oluşturma (Merge Request) Pull Request ve Merge Request, bir dalda yaptığınız değişikliği başka bir dala aktarmayı talep etmenizi sağlar. Merge, yani birleştirme işlemi de istekte yapılan değişiklikleri dala aktarırsınız.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

git merge : branchleri birleştirme işlemi
git pull : repodaki verileri lokale çekmek için kullanlılır.
git fetch: pull'dan farklı olarak birleştirme işlemi olmaz.

7. Merge conflict nedir?

İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır.

8. Merge conflict'i nasıl çözeriz?

Git conflict çözmek için, kullanıcının ilk olarak dosyayı açması ve çatışmalı bölümleri bulması gerekir. Daha sonra, çatışmalı bölümleri manuel olarak düzenlemek ve Git'e tekrar birleştirme işlemini yapması gerekir. Bu işlemi yaparken, kullanıcının hangi değişikliklerin korunması gerektiğine karar vermesi gerekir.
