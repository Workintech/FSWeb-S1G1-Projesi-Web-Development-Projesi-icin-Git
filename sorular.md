1.Git nedir?

Git, yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol sistemidir. Git sayesinde yapacağınız projelerin adım adım versiyonlarının kopyalarını alarak daha sonra ihtiyaç duyduğunuzda aldığınız kopyalara yani versiyonlara kolayca dönebiliyorsunuz.  İlk sürümü Linux çekirdeği'nin geliştirilmesinde kullanılmak üzere 2005 yılında Linus Torvalds tarafından tasarlanıp geliştirilmiş, 2019 yılı itibarıyla %70 pazar payına ulaşmıştır. Açık kaynaklı özgür bir yazılım ürünü olan Git'i istediğiniz gibi kullanabilirsiniz.

2.Git ile GitHub arasında ne fark var?

Git, bir versiyon takip yazılımıdır. Lokal olarak bilgisayarda çalışır ve Github olmadan da Git'i kullanabilmek mümkündür. Git ile projelreinizin versiyonlamasını yapabilir ve bunu internete bile bağlanmadan kullanabilirsiniz. Herhangi bir kayıt işlemine ihtiyaç duymaz.

Github ise Git repository'lerinin cloud üzerinde saklandığı online bir servistir. Github'a kayıt olmanız gereklidir ve ek fayda olarak da başka kişilerin repository'lerine erişebilir ya da kendi repository'lerinize erişmelerini ve katkı sağlamalarını isteyebilirsiniz. Online bir servistir ve offline olarak kullanabilneniz mümkün değildir.

3.Neden bir branch oluşturuyoruz?

Branch oluşturmak kullanıcıya çalıştığı projenin farklı versiyonlarına erişmesini sağlar. Kullanıcı, projesine bir yenilik eklemek istediğinde, yaptığı değişiklik projenin çalışmasını olumsuz etkileyebilir. Bu gibi durumlarda projemizin o anki halini bozmamak için branch kullanabiliriz. Branch yardımı ile projemizin çalışır halini kaydedip, yeni eklenti üzerinde rahatlıkla çalışabiliriz. Projemizde herhangi bir sorun çıktığı takdirde geri dönüp önceki versiyona kolaylıkla erişebiliriz.

4.Pull Request'in amacı nedir?

Pull Request, yapılan katkıların bir gelişime açık projeye sunulması tekniğidir.

5.Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela isim-soyisim branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

"git checkout main" komutu ile geçebiliriz. 


6.git fetch, git merge ve git pull arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

git fetch, uzak bir havuzdan içerik indirmek için kullanılan birincil komuttur.

Git'de merge işlemi başka bir branch'deki değişiklikleri üzerinde çalıştığınız kendi branch'inize entegre etme işlemidir. Git merge işlemi sırasında değişikliklerin çoğunu sizin için otomatik olarak entegre eder.

git pull, uzak depodaki değişiklikleri almak ve bunları mevcut çalışma dizini ile birleştirmek için kullanılır.

Git Fetch ve Git Pull arasındaki temel fark, git fetch’in kaynaktan en yeni meta veri bilgilerini geri yüklemek için yerel git’inizi gösteren komut olmasıdır. Herhangi bir dosya aktarmaz. Daha çok değişikliklerin mevcut olup olmadığını bulmak için verileri incelemek gibidir, oysa git pull tüm değişiklikleri deponuza çekmekle birlikte aynı şeyi yapar


7.Merge conflict nedir?

Bazen birden fazla geliştirici aynı içeriği düzenlemeye çalışabilir. Geliştirici A, Geliştirici B'nin düzenlemekte olduğu kodu düzenlemeye çalışırsa bir çakışma meydana gelebilir

8.Merge conflict'i nasıl çözeriz?

1.Çakışan bir dosyayı çözmenin en kolay yolu dosyayı açıp gerekli değişiklikleri yapmaktır.
2.Dosyayı düzenledikten sonra, yeni birleştirilmiş içeriği hazırlamak için git add a komutunu kullanabiliriz.
3.Son adım, git commit komutunun yardımıyla yeni bir commit oluşturmaktır.
4.Git, birleştirmeyi sonlandırmak için yeni bir birleştirme commiti oluşturacak