# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

Git, Açık Kaynak Dağıtılmış Sürüm Kontrol Sistemi(Open Source Distributed Version Control System)'dir.Geliştiriciler bir proje yarattıklarında ilk resmi (beta olmayan) sürüme kadar ve hatta sonrasında yeni sürümler yayınlayarak kod üzerinde sürekli değişiklik yaparlar. Sürüm kontrol sistemleri, değişiklikleri merkezi bir depoda saklayarak bu revizyonları düzenli tutar. Bu, geliştiricilerin kodun yerel sürümleri üzerinde çalışabilmelerini, değişiklik yapabilmelerini ve en yeni revizyonu yükleyebilmelerini sağlayarak kolayca işbirliği yapmalarına olanak tanır. Her geliştirici bu yeni değişiklikleri görebilir, indirebilir ve katkıda bulunabilir.

2. Git ile GitHub arasında ne fark var?
Git Sürüm kontrol sistemi olarak sürümler üzerinde değişiklik yapmaya olanak sağlar. GitHub, bulut tabanlı bir git barındırma hizmeti sunan kâr amaçlı bir şirkettir.Git araçtır, GitHub Git'i kullanan projeler için hizmettir. 

3. Neden bir branch oluşturuyoruz? 
 Üzerinde çalışılan kaynak kodun bir kopyasını oluşturarak geliştirmelerin orijinal koddan bağımsız olarak ilerlemesini sağlayabilmek adına branch oluşturulur. Örneğin bir git deposu varsayılan olarak master branch'i ile oluşur. Dilerseniz geliştirme amaçlı olarak "development" isminde farklı bir branch oluşturarak kod üzerindeki geliştirmelerinizi burada yapabilir ve test süreci sonrasında hatasız olduğuna emin olduğunuzda değişiklikleri master branch'ine taşıyabilirsiniz.

4. Pull Request'in amacı nedir?
Projeler birden fazla kanaldan geliştirilebilirler.Pull request de birden fazla geliştirici ile hazırlanan yazılımlarda bir git projesine push edilen değişikliklerin diğer geliştiricilere haber verilmesidir. Bir pull request açıldığında yeni eklenen kodların mevcut branch ile birleştirilmesi hakkında oluşturulan kodlar diğer geliştiriciler ile birlikte değerlendirilebilir. Böylelikle projenin gelişimine katkı sağlanabilir.

5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
"git checkout" komutu ile branchler arasında geçiş yapılabilmektedir.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
Git pull komutu, git fetch ve git merge komutlarının amacına tek bir komutta hizmet eden bir komuttur. Git fetch, hedef branchteki bulunan ve mevcut branchte bulunmayan herhangi bir commit işlemini yapar ve local reponuza kaydeder. Ancak, bunları mevcut branchinize merge etmez. Git pull otomatik olarak merge işlemini gerçekleştirir. Git Fetch ile merge işlemi kullanıcı tarafından yapılır.

7. Merge conflict nedir?
Conflict kelime anlamı olarak çakışma anlamındadır. Proje üzerinde merge conflict uyarısı alınıyorsa merge edilirken bir çakışmanın oluştuğu anlamına gelmektedir. Kısaca aynı proje üzerinde çalışan kişiler projenin aynı line (satır) üzerinde farklı değişiklikler yaptıklarında proje merge conflict uyarısı vermektedir.

8. Merge conflict'i nasıl çözeriz?
GitHub ya da command line kullanarak merge conflict çözmek mümkündür. Daha karmaşık bir problemde bazı durumlarda GitHub yeterli gelmeyebilir. Böyle durumlarda command line kullanarak belirli komutlarla bir sorunu ortadan kaldırabiliriz.

* Kullandığımız terminalde conflict uyarısı veren dosya açılır.
* Base Branch sonrası <<<<<<< HEAD , iki branch arası  =======  son olarakta  >>>>>>> BRANCH-NAME içeren conflict markers görülür.
* Üç farklı alternatif seçim mevcuttur. Her iki branchden biri ya da her iki branch değişikliğini içeren yeni bir branch     oluşturulabilir. Seçime karar verildikten sonra Conflict markers silinir, son olarak merge edilecek değişiklikler yapılır.
* Yeni oluşturulan branch commit edilerek merge conflict sorunu çözülür.
