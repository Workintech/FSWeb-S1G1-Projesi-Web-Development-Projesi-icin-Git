## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
2. Git ile GitHub arasında ne fark var?
3. Neden bir branch oluşturuyoruz? 
4. Pull Request'in amacı nedir?
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
7. Merge conflict nedir?
8. Merge conflict'i nasıl çözeriz?

Cevaplar:
1. Git, yazılım geliştirme süreçlerinde kullanılan, hız odaklı, Açık Kaynak Dağıtılmış Sürüm Kontrol Sistemi(Open Source Distributed Version Control System)'dir. Git sürüm kontrol sistemini kullanan her bir çalışma dizini (proje), internet erişimi ya da merkezi bir depo olmaksızın tüm tarihçeyi tutan ve sürüm kontrol sisteminin tamamını içinde barındıran tam yetkili birer depodur. Ayni çalışma dizininin birçok depodan birindeki kopyasında yapılan değişiklikler diğerlerine güven temelli bir değerlendirmeyle kabul edilir; Güvenilmeyenden değişiklik alınmaz, o kendi ayrı sürümünü geliştirmeye devam eder.
2. Git, bir versiyon takip yazılımıdır. Lokal olarak bilgisayarda çalışır ve Github olmadan da Git'i kullanabilmek mümkündür. Git ile projelreinizin versiyonlamasını yapabilir ve bunu internete bile bağlanmadan kullanabilirsiniz. Herhangi bir kayıt işlemine ihtiyaç duymaz.
Github ise Git repository'lerinin cloud üzerinde saklandığı online bir servistir. Github'a kayıt olmanız gereklidir ve ek fayda olarak da başka kişilerin repository'lerine erişebilir ya da kendi repository'lerinize erişmelerini ve katkı sağlamalarını isteyebilirsiniz. Online bir servistir ve offline olarak kullanabilneniz mümkün değildir.
3. Kullanıcı projesine bir yenilik eklemek istediğinde mevcut projenin çalışmasını olumsuz etkilememek adına branch kulanabilir. Yeni bir eklenti üzerinde rahatlıkla çalışmaya yardımcı olur.Aynı zamanda projeye yeni bir versiyon çıkartılacağı zaman her yeni versiyon için repository oluşturmak yerine her yeni versiyon için farklı branch'ler açılabilir. Böylelikle versiyonlara erişim kolaylaşır ve takibi daha rahat yapılır.
4. Proje üzerindeki yeni kod değişikliklerini ana proje repository'sine entegre etme sürecini başlatmak için kullanılır. Bir diğer ifadeyle açık kaynaklı projelerde projeye destek vermek amacıyla veya aynı projedeki ekip üyelerinin geliştirmiş oldukları özelliklerin veya düzeltmelerin hazır olduğunu bildirme mekanizmasıdır. 
5. Mevcutta var olan branch'a geçiş yapmak için:
"$ git checkout <branch_name>"
main branch'in adı main olduğu için "$ git checkout <main>" kodu ile geçiş yapılabilir.
Yeni bir branch oluşturup, bu branch'a geçiş yapmak için ise "$ git checkout -b <branch_name>" kullanılır.
6. Git fetch, uzaktaki bir deponun dosyalarını, anlık görüntülerini ve referanslarını yerel deponuza indiren bir komuttur. Bu komut, yerel deponuzun mevcut çalışma durumunu güncellemeden uzaktaki verileri indirir, çalışmanızı olduğu gibi bırakır ve getirilen içerik gitcheckout komutu kullanılarak açıkça kontrol edilir.
Git pull komutu uzaktaki bir depodan verileri getirip indirirken yerel depoyu getirilen verilerle eşleşecek şekilde günceller. Git pulls komutu, git fetch ve git merge komutlarının bir kombinasyonudur, bu nedenle başlangıçta git fetch komutunun işlevini yerine getirir ve daha sonra commit’i birleştirir ve yeni bir merge commit oluşturur.
Git merge komutu genellikle iki farklı branch'de yapılan değişiklikleri birleştirmek için kullanılır.
7. Merge conflicts, insanlar aynı dosyanın aynı satırında farklı değişiklikler yaptığında veya bir kişi bir dosyayı düzenlerken başka bir kişi aynı dosyayı sildiğinde meydana gelir.
8. Merge conflicts'i çözmek için, final merge'de saklamak istediğiniz değişiklikleri seçmek için çakışan dosyayı manuel olarak düzenlemeniz gerekir. Merge conflicts'i çözmenin birkaç farklı yolu vardır:
Eğer merge conflict Git repository'nizde bulunan farklı branchlar'daki aynı dosyanın aynı satırında farklı bir değişiklik yapması sonucu satırların çakışmasından dolayı oluşuyorsa, bunun çözümü için GitHub üzerinden conflict editor kullanılarak sorun çözülebilir.
Haricindeki tüm merge conflict problemleri için, çakışmayı repository'nin lokal klonu üzerinden çözmeli ve değişiklikleri GitHub'daki branch'ınıza push etmelisiniz.
