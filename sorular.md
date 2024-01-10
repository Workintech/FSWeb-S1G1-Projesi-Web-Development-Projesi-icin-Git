# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
   Git, Açık Kaynak Dağıtılmış Sürüm Kontrol Sistemi(Open Source Distributed Version Control System)'dir.

2. Git ile GitHub arasında ne fark var?
   Git bir versiyon kontrol yazılımıdır. Projemizde yaptığımız değişiklikleri adım adım kaydetmemizi sağlar ama bunu bizim bilgisayarımızda yani yerel de yapar , internet bağlantısı olmadan veya kayıt olmadan kullanabiliriz. Bunun için bu yazılımı bilgisayarımıza indirmemiz lazım.
   GitHub ise projelerimizin cloud (bulut) tabanlı bir sistemde online olarak yer aldığı bir servistir. Bunun için www.github.com’a üye olmamız gerekir. GitHub ile başkalarının projelerine bakabiliriz, projelerine destek verebiliriz ve anlatacağımız bir çok işlevi yapabiliriz. GitHub’ı offline(çevrimdışı) olarak kullanamayız.

3. Neden bir branch oluşturuyoruz?
   Üzerinde çalışılan kaynak kodun bir kopyasını oluşturarak geliştirmelerin orijinal koddan bağımsız olarak ilerlemesini sağlamak için ve kendi değişikliklerimizin aynı projede calısan diğer insanları etkilememesi için branc olusturuyoruz. Örneğin bir git deposu varsayılan olarak master branch'i ile oluşur. Dilerseniz geliştirme amaçlı olarak "development" isminde farklı bir branch oluşturarak kod üzerindeki geliştirmelerinizi burada yapabilir ve test süreci sonrasında hatasız olduğuna emin olduğunuzda değişiklikleri master branch'ine taşıyabilirsiniz

4. Pull Request'in amacı nedir?
   GitHub Reposunda yeni bir branch açtıktan sonra değişikliklerini bu Branch'e yaparsın ve asıl Branch'e bir pull request(merge Request'te denir aynı zamanda) oluşturursun. Bu pull request onaylandığında değişiklikleri yaptığın branch, ana Branch'e katılır ve değişiklikler ana Branch'e yansır.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
   git checkout [main branch adı] yaparım
   git checkout
   Bu komut bir daldan (branch) diğerine geçiş yapmak için kullanılır. Git checkout komutu sayesinde projeni alt dallara ayırman da kolaylaşır. Proje haritası sayesinde aynı proje içinde alt projeler veya deneme projeleri geliştirebilirsin.
   git checkout -b [branch adı] (Bu komut yeni bir dal oluşturur ve aynı zamanda ona geçiş yapar.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

fetch kullandığınızda, Git, hedef branchteki bulunan ve mevcut branchte bulunmayan herhangi bir commit işlemini yapar ve yerel reponuza kaydeder. Ancak, bunları mevcut branchiniz ile birleştirmez. Peki git fetch ne işe yarar? Repomuzu güncel tutmamız gerekiyorsa, ancak dosyalarımızı güncellersek de bozulabilecek bir şeyler varsa fetch kullanmayı tercih ederiz. Bu işlemleri mevcut branchinize entegre etmek için sonrasında merge kullanmalısınız.
pull kullandığınızda, Git otomatik olarak merge çalışır. Bağlamsal olarak hassastır, bu nedenle Git şu anda çalıştığınız branch için herhangi bir commit varsa birleştirecektir. Dolayısıyla git pull ne işe yarar diye bir soru sorarsak; pull yapılan değişiklikleri gözden geçirmenize izin vermeden otomatik olarak birleştirir diyebiliriz. Eğer branchlerinizi dikkatlice yönetmiyorsanız, sık sık sorunlarla karşılaşabilirsiniz.

git merge: Birleştirme komutu olarak da bilinen git merge belirtilen uzantıyı veya dalı başka bir uzantı ile birleştirir.
Örnek
git push [değişken adı] master (Belli işlem demetlerini uzak sunucuya gönderir.)
git push [variable name] [branch] (Bu komut belirtilen değişkeni uzak depoya gönderir.)
git push –all [değişken adı] (Bu komut tüm işlem demetlerini uzak depoya gönderir.)
git push [değişken adı] :[branch name] (Bu komut, uzak depoda özel olarak belirtilen işlem demetini siler.)

git pull
Bu komut uzak sunucuda yapılan değişiklikleri çalışma dizinine getirir ve birleştirir.Kısaca git pull; önce bir git fetch yapar, sonrasında ise git merge uygular.
git pull [Depo Bağlantı Linki]

7. Merge conflict nedir?
   Git “merge conflict” (birleştirme çakışması), farklı dallardaki veya farklı commitlerdeki değişikliklerin aynı dosyanın aynı satırında çakıştığı durumlarda ortaya çıkar.

8. Merge conflict'i nasıl çözeriz?
   Git status komutu ile değişen dosyaları ve yorumları goruntuleyebiliriz. MErge işlemi sırasında cakısmaların tespiti için genelde kullanılır.
   Git log --merge komutu ile kaynak branch ile kendi branch arasındaki cakısmaları gosterir.
   git diff komutu ile commit olmayan değişiklikler ve önceki commit olanları görürüz.git diff komutu branchler commitler ve dosyaları karsılastırmak için genelde kullanılır. olası merge conflict leri onceden tespit etmeye yarar.
