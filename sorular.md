
# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular


1. Git nedir?

Git, yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol sistemidir. Git sayesinde yapacağımız projelerin adım adım versiyonlarının kopyalarını alarak daha sonra ihtiyaç duyduğumuzda aldığımız kopyalara yani versiyonlara kolayca dönebiliriz.İşlerin takibi ve işlerin gelişimi açısından önemlidir. Ekibimizdeki diğer developerların neler yaptığını görebiliriz.

2. Git ile GitHub arasında ne fark var?

Git, bir dağıtık versiyon kontrol sistemi olarak çalışır. Bu, her geliştiricinin kendi bilgisayarında bir Git deposuna sahip olabileceği ve projenin tüm geçmiş sürümlerinin dağıtık olarak saklanabileceği anlamına gelir. Geliştiriciler, bir Git deposu oluşturarak, kodlarını burada saklayabilirler ve Git’in sunmuş olduğu özellikleri kullanarak bu kodları kontrol edebilirler.

GitHub ise, Git depolarının barındırılabileceği bir bulut tabanlı servistir. Bu sayede, geliştiriciler, Git depolarını GitHub’a yükleyerek, kodlarını paylaşabilir, işbirliği yapabilir ve projeleri yönetebilirler.

GitHub ayrıca, “fork” özelliği ile başka birinin Git deposunu kopyalayarak, onun üzerinde çalışma ve kendi değişikliklerini yapma imkanı sağlar. Bir geliştirici, bir açık kaynak projeye katkıda bulunmak istediğinde, projenin GitHub deposunu kopyalar, kendi değişikliklerini yapar ve daha sonra projenin sahibine bir “pull request” göndererek, değişikliklerinin kabul edilmesini talep edebilir.

Git ve GitHub arasındaki en büyük fark, Git’in yerel depolama ile çalışması ve GitHub’ın bulut tabanlı bir hizmet olmasıdır. Ayrıca, GitHub, Git’in sağladığı özellikleri artırır ve kullanıcıların projelerini daha kolay yönetmelerini sağlar.

3. Neden bir branch oluşturuyoruz?

Branch oluşturmak kullanıcıya çalıştığı projenin farklı versiyonlarına erişmesini sağlar. Kullanıcı, projesine bir yenilik eklemek istediğinde, yaptığı değişiklik projenin çalışmasını olumsuz etkileyebilir. Bu gibi durumlarda projemizin o anki halini bozmamak için branch kullanabiliriz. Branch yardımı ile projemizin çalışır halini kaydedip, yeni eklenti üzerinde rahatlıkla çalışabiliriz. Projemizde herhangi bir sorun çıktığı takdirde geri dönüp önceki versiyona kolaylıkla erişebiliriz.

4. Pull Request'in amacı nedir?

Pull request talebi, temelde branch’dan sorumlu kişiden kodunuzu eklemesini istemektir. Ayrıca o kişinin kodda tam olarak neyi değiştirdiğinizi görmesine de yardımcı olur.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

Git’de branch değiştirmek için git checkout komutunu kullanabiliriz. git checkout komutunu yazdıktan sonra gitmek istediğimiz branch’in adını yazmalıyız.

git checkout main

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu komutlar ne yapar açıklayınız.

Git Fetch

Kodu uzak depodan yerel depoya çeken bir komutttur.Uzak bir depoda yapılan değişiklikleri çakışma yaratmadan geri yükler.Birleştirme yapılmadığı için herhangi bir çakışma meydana gelmez.

Git Pull

Uzak depoda yakın zamanda yapılan değişiklikleri indiren ve bunları yerel bir depoda birleştiren bir komuttur.Uzak depoda yapılan değişiklikleri kaydeder ve bunları birleştirir, bu da çakışmalar yaratır.
Geliştiriciler güncelleme için yerel kod deposunu değiştirebilir.

Git merge

Git'de merge işlemi başka bir branch'deki değişiklikleri üzerinde çalıştığınız kendi branch'inize entegre etme işlemidir. Git merge işlemi sırasında değişikliklerin çoğunu sizin için otomatik olarak entegre eder.

7. Merge conflict nedir?

Bir versiyon kontrol sisteminde en büyük problem çakışmalardır. Bu çakışmalar yaptığımız geliştirmeye bağlı olarak bazen basitçe çözebilir bazen de saatlerce zamanımızı alabilir.

Çakışma aslında çok basit bir şekilde karşımıza çıkabilir. İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır. Bu durumda çakışma yaşayan kişi gerekirse ekipteki diğer kişi ile beraber oturup çakışmayı çözdükten sonra merge işlemine devam etmelidir.

8. Merge conflict'i nasıl çözeriz?

Çakışma oluştuğunda ilk yapmamız gereken şey çakışmanın neden olduğunu bulmaktır. Örneğin takım arkadaşınız aynı dosyada sizin de değiştirdiğiniz bir satırı mı değiştirdi veya aynı dosyada bir satır mı sildi veya sizinle aynı isimli yeni bir dosya mı oluşturdu?

git status komutunu çalıştırdığımızda Git bize branch'imizde entegre edilmemiş dosyalar olduğunu söyleyecektir.Çakışmayı düzeltmek için dosyamızı açıp çakışan satırları düzeltmemiz gerekiyor.