# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

Git, Açık Kaynak Dağıtılmış Sürüm Kontrol Sistemi(Open Source Distributed Version Control System)'dir.

2. Git ile GitHub arasında ne fark var?

Git bir versiyon kontrol sistemidir. GitHub ise bu versiyon kontrol sistemi ile kullandığımız projeleri depolayabildiğimiz bir portaldır.

3. Neden bir branch oluşturuyoruz?

 Geliştirmelerin orijinal koddan bağımsız olarak ilerlemesini sağlamak ve kod üzerindeki gelişmeleri burada yapıp test süreci sonrasında hatasız olduğundan emin olup master branch'e taşımak için.

4. Pull Request'in amacı nedir?

Brancdan sorumlu kişiden kodunuzu eklemesini istemektir.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

1.olarak => $git branch yazılır ve Branch listesi görülür gitmek istediğimiz branch için ikinci adım uygulanır.
2.olarak => $git checkout main yazılarak branch değiştirilir. 

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

GİT FETCH => Git fetch, uzaktaki bir deponun dosyalarını, anlık görüntülerini ve referanslarını yerel depomuza indiren bir komuttur. Birleştirme yapılmadığı için herhangi bir çakışma meydana gelmez.
GİT MERGE => Başka bir branch'deki değişiklikleri üzerinde çalıştığımız kendi branch'inize entegre etme işlemidir.
GİT PULL => Uzak depoda yakın zamanda yapılan değişiklikleri indiren ve bunları yerel bir depoda birleştiren bir komut. Aynı kod üzerinde çalışan iki kişi arasında birleştirme çatışması çıkar. 

Git fetch komutunda veriler sadece indirilirken, git pull komutunda veriler indirilir ve yerel deponuzda yüklemeler yapılır.
Git fetch komutu yalnızca komut satırı sözdizimine sahipken, git pull komutu komut satırı sözdizimine ve değişiklikleri göndermek için çekme isteğine sahiptir.

7. Merge conflict nedir?

İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır.

8. Merge conflict'i nasıl çözeriz?

Kullanıcının ilk olarak dosyayı açması ve çatışmalı bölümleri bulması gerekir. Daha sonra, çatışmalı bölümleri manuel olarak düzenlemek ve Git'e tekrar birleştirme işlemini yapması gerekir.