Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Git, Açık Kaynak Dağıtılmış Sürüm Kontrol Sistemi(Open Source Distributed Version Control System)'dir.

2. Git ile GitHub arasında ne fark var?
GitHub, bulut tabanlı bir git barındırma hizmeti sunan kâr amaçlı bir şirkettir. Ocak 2020 itibariyle GitHub, 40 milyondan fazla kullanıcıya ve 100 milyonun üzerinde bir depoya (en az 28 milyon kapasiteli herkese açık alan dahil) sahip olduğunu bildirmiş ve dünyanın en büyük kaynak kodu barındırıcısı haline gelmiştir. Popüler olmasının nedeni, versiyon kontrolü ve işbirliği için git kullanımını bireyler ve ekipler için kolaylaştırmasıdır. GitHub'daki projelere standart git komut satırı arayüzü kullanılarak erişilebilir ve tüm standart git komutları bununla çalışır.

3. Neden bir branch oluşturuyoruz?
Branch: Üzerinde çalışılan kaynak kodun bir kopyasını oluşturarak geliştirmelerin orijinal koddan bağımsız olarak ilerlemesini sağlayabilirsiniz. Örneğin bir git deposu varsayılan olarak master branch'i ile oluşur. Dilerseniz geliştirme amaçlı olarak "development" isminde farklı bir branch oluşturarak kod üzerindeki geliştirmelerinizi burada yapabilir ve test süreci sonrasında hatasız olduğuna emin olduğunuzda değişiklikleri master branch'ine taşıyabilirsiniz.
4. Pull Request'in amacı nedir?
 bir deponun yerel sürümünü remote olarak güncellemek için kullanılan bir git komutudur. Varsayılan olarak, git pull geçerli yerel çalışma branch’ını (o an için kullanılan branch’ı) günceller ve diğer tüm branch’lar için remote-tracking branch’larını (uzaktan takip branch’ları) günceller.
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout komutu kullanilir

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
 Merge, git'in çatallanmış bir geçmişi tekrar bir araya getirme yoludur. git merge komutu, git branch tarafından oluşturulan bağımsız geliştirme satırlarını almanızı ve bunları tek bir branch'ta birleştirmenizi sağlar,  bir deponun yerel sürümünü remote olarak güncellemek için kullanılan bir git komutudur. Varsayılan olarak, git pull geçerli yerel çalışma branch’ını (o an için kullanılan branch’ı) günceller ve diğer tüm branch’lar için remote-tracking branch’larını (uzaktan takip branch’ları) günceller, git fetch farklı depolardan objeleri reposteri ediyor
7. Merge conflict nedir?
Birleştirme çakışması, Git'in iki işlem arasındaki kod farklarını otomatik olarak çözemediği durumlarda gerçekleşen bir olaydır.
8. Merge conflict'i nasıl çözeriz?
   Git, yalnızca taahhütler farklı satırlarda veya dallardaysa değişiklikleri otomatik olarak birleştirebilir.


