# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Git, Açık Kaynak Dağıtılmış Sürüm Kontrol Sistemi(Open Source Distributed Version Control System)'dir.

2. Git ile GitHub arasında ne fark var?
Kısaca söylemek gerekirse Git bir versiyon kontrol sistemidir. GitHub ise bu versiyon kontrol sistemi ile kullandığımız projeleri depolayabildiğimiz bir portaldır diyebiliriz.

3. Neden bir branch oluşturuyoruz?
Üzerinde çalışılan kaynak kodun bir kopyasını oluşturarak geliştirmelerin orijinal koddan bağımsız olarak ilerlemesini sağlayabilmek içindir, farklı bir branch oluşturarak kod üzerindeki geliştirmelerinizi burada yapabilir ve test süreci sonrasında hatasız olduğuna emin olduğunuzda değişiklikleri master branch'ine taşıyabiliriz
yani, deneme tahtasına da benzetebiliriz.

4. Pull Request'in amacı nedir?
Proje üzerinde değişiklik yaptığınızı gösterirsiniz ve proje sahibinin katkınızı gözden geçirip çekmesini ve birleştirmesini talep edersiniz. Değişiklikler, eklemeler ve çıkarmalar yeşil ve kırmızı olarak gösterilir.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout main branch      --->komutunu terminale girerek değiştirebilirim

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
Git fetch, bir uzak depodan son güncelleme durumunu getirir ve yerel bir kopya oluşturur. Yani, uzak depoda yapılan değişikliklerin yerel bir kopyası elde edilir, ancak yerel deponun kendisi değiştirilmez. Bu nedenle, `git fetch` işlemi, uzak depodaki güncellemeleri yerel depoya getirmek için kullanılır, ancak mevcut yerel deponuzu güncellemez.

Git merge, farklı dallardaki değişiklikleri birleştirir. Yani, bir dalın güncel halini başka bir dala birleştirir. Bu işlem, yerel depodaki farklı dallardaki değişiklikleri birleştirir ve sonuç olarak, farklı dallardaki değişiklikler tek bir dalda birleştirilir.

Git pull, aslında `git fetch` ve `git merge` komutlarını tek bir komutta birleştirir. Yani, uzak depodan son güncelleme durumunu getirir ve ardından yerel deponuzu güncellemek için `git merge` komutunu kullanır. Bu nedenle, `git pull`, hem uzak depodaki güncellemeleri getirmek hem de yerel depoyu güncellemek için kullanılır.

Özetle, `git fetch` işlemi uzak depodan son güncelleme durumunu getirir, `git merge` farklı dallardaki değişiklikleri birleştirir ve `git pull`, hem `git fetch` hem de git merge komutlarını tek bir komutta birleştirir.

7. Merge conflict nedir?
Merge conflict, Git depolama sisteminde bir çatışma olarak tanımlanır. Bu, aynı dosyayı farklı bir üye tarafından değiştirilmesi ve bu değişikliklerin birleştirilmesi gerektiğinde oluşur. Git, bu tür çatışmaları otomatik olarak çözmeye çalışır, ancak bazen manuel olarak çözülmesi gerekir.

Git conflict oluştuğunda, Git iki tarafın değişikliklerini birleştirmeye çalışır, ancak birleştirme işlemi başarısız olur. Bu durumda, Git conflict bildirir ve kullanıcının bu çatışmayı manuel olarak çözmesini ister.

8. Merge conflict'i nasıl çözeriz?
Çakışma oluştuğunda ilk yapmanız gereken şey çakışmanın neden olduğunu anlamak olmalıdır. Örneğin takım arkadaşınız aynı dosyada sizin de değiştirdiğiniz bir satırı mı değiştirdi veya aynı dosyada bir satır mı sildi veya sizinle aynı isimli yeni bir dosya mı oluşturdu?

git status komutunu çalıştırdığınızda Git size branch'inizde entegre edilmemiş dosyalar olduğunu söyleyecektir.

Bu çakışmayı düzeltmek için dosyamızı açıp belirtilen çakışan satırları düzelttiğimizde merge conflict çözülmüş olur.