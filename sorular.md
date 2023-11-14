# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Git, yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol sistemidir. Git sayesinde yapacağınız projelerin adım adım versiyonlarının kopyalarını alarak daha sonra ihtiyaç duyduğunuzda aldığınız kopyalara yani versiyonlara kolayca dönebiliyorsunuz.


2. Git ile GitHub arasında ne fark var?
Git; bir projenin bir çok kişi ile aynı anda yapılabilmesini sağlar. Düşünsenize Git olmadan önce insanlar Flash bellekler kullanarak projelerini depolayıp saklıyorlar ve her yeni güncelleme sırasında tekrar aynı projeyi belleğe atıyorlar. Bir de projeyi birden fazla kişi yapıyorsa bu yapılanlar nasıl birleştirilecek diye düşünürsek Git bu konuda hayatımızı ciddi anlamda kolaylaştırmıştır.
Github ise projelerimizin saklandığı (depolandığı) uzak sunucudur. Github’a projelerinizi ekleyebilir aynı zamanda istediğiniz public olan farklı projelere Github üzerinden erişerek projeyi bilgisayarınıza indirebilirsiniz. Hatta istediğinizde bu projeler üzerinde değişiklikler yaparak Pull Request gönderebilirsiniz.


3. Neden bir branch oluşturuyoruz?
Branch oluşturmak kullanıcıya çalıştığı projenin farklı versiyonlarına erişmesini sağlar. Kullanıcı, projesine bir yenilik eklemek istediğinde, yaptığı değişiklik projenin çalışmasını olumsuz etkileyebilir. Bu gibi durumlarda projemizin o anki halini bozmamak için branch kullanabiliriz. Branch yardımı ile projemizin çalışır halini kaydedip, yeni eklenti üzerinde rahatlıkla çalışabiliriz. Projemizde herhangi bir sorun çıktığı takdirde geri dönüp önceki versiyona kolaylıkla erişebiliriz. Branch, sadece projenizi değiştirirken ya da güncellerken eski halini korumak ile kalmıyor. Projenize bir versiyon çıkarttığınız zaman her yeni versiyon için repository oluşturmak yerine her bir versiyon için farklı branchler açabilirsiniz. Böylece versiyonları bir arada kolayca takip edebilir ve erişebilirsiniz.


4. Pull Request'in amacı nedir?
Pull request, açık kaynaklı bir projede katkıda bulunmak isteyen bir kullanıcının, projenin sahibine değişikliklerini inceletmek üzere yaptığı bir taleptir.


5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
Git'de branch değiştirmek için git checkout komutunu kullanabiliriz. git checkout komutunu yazdıktan sonra gitmek istediğiniz branch'in adını yazmanız yeterlidir. Eğer gitmek istediğiniz branch'in adını hatırlamıyorsanız git branch komutu ile bütün branchleri listeleyebilirsiniz.
 git checkout -b 'MEHTAPAYDINYILMAZ'


6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch=başkalarının uzak depoya yüklediği tüm yeni işlemeleri indirir.
git merge=Git'de merge işlemi başka bir branch'deki değişiklikleri üzerinde çalıştığınız kendi branch'inize entegre etme işlemidir. Git merge işlemi sırasında değişikliklerin çoğunu sizin için otomatik olarak entegre eder.
git pull=Proje ana dosyasındaki yaptığınız değişikliklerin bilgisayarınızdaki versiyonuna çekilmesini sağlar.


7. Merge conflict nedir?
İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır. Bu durumda çakışma yaşayan kişi gerekirse ekipteki diğer kişi ile beraber oturup çakışmayı çözdükten sonra merge işlemine devam etmelidir.


8. Merge conflict'i nasıl çözeriz?
Çakışma oluştuğunda ilk yapmanız gereken şey çakışmanın neden olduğunu anlamak olmalıdır. Örneğin takım arkadaşınız aynı dosyada sizin de değiştirdiğiniz bir satırı mı değiştirdi veya aynı dosyada bir satır mı sildi veya sizinle aynı isimli yeni bir dosya mı oluşturdu?  Bu çakışmayı düzeltmek için dosyamızı açıp çakışan satırları düzeltmemiz gerekiyor.