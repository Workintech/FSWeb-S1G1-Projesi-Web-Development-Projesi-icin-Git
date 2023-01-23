## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
Git, yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol sistemidir. Git sayesinde yapacağınız projelerin adım adım versiyonlarının kopyalarını alarak daha sonra ihtiyaç duyduğunuzda aldığınız kopyalara yani versiyonlara kolayca dönebiliyorsunuz. 
2. Git ile GitHub arasında ne fark var?
Git, bir versiyon takip yazılımıdır. Lokal olarak bilgisayarda çalışır ve Github olmadan da Git'i kullanabilmek mümkündür. Git ile projelerinizin versiyonlamasını yapabilir ve bunu internete bile bağlanmadan kullanabilirsiniz. Herhangi bir kayıt işlemine ihtiyaç duymaz.

Github ise Git repository'lerinin cloud üzerinde saklandığı online bir servistir. Github'a kayıt olmanız gereklidir ve ek fayda olarak da başka kişilerin repository'lerine erişebilir ya da kendi repository'lerinize erişmelerini ve katkı sağlamalarını isteyebilirsiniz. Online bir servistir ve offline olarak kullanabilneniz mümkün değildir.
3. Neden bir branch oluşturuyoruz? 
Branch oluşturmak kullanıcıya çalıştığı projenin farklı versiyonlarına erişmesini sağlar. Kullanıcı, projesine bir yenilik eklemek istediğinde, yaptığı değişiklik projenin çalışmasını olumsuz etkileyebilir. Bu gibi durumlarda projemizin o anki halini bozmamak için branch kullanabiliriz. Branch yardımı ile projemizin çalışır halini kaydedip, yeni eklenti üzerinde rahatlıkla çalışabiliriz. Projemizde herhangi bir sorun çıktığı takdirde geri dönüp önceki versiyona kolaylıkla erişebiliriz. Ayrıca birden fazla kişinin projenin üzerinde çalışabilmesini sağlar.
4. Pull Request'in amacı nedir?
Bazı değişiklikleri yaptıktan sonra, bir pull request talebinde bulunarak bu kodu bir şubeye geri gönderebilirsiniz. Pull request talebi, temelde branch’dan sorumlu kişiden kodunuzu eklemesini istemektir. Ayrıca o kişinin kodda tam olarak neyi değiştirdiğinizi görmesine de yardımcı olur.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz. 
git checkout main
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch : Bu komut remote’daki tüm commitleri local’e çeker. Fakat çekilen commitler remote branch’lar olarak depolanır, local olarak değil. Bu sayede local’deki kodla merge etmeden önce gözden geçirme şansı verir.
git merge : Git'de merge işlemi başka bir branch'deki değişiklikleri üzerinde çalıştığınız kendi branch'inize entegre etme işlemidir. Git merge işlemi sırasında değişikliklerin çoğunu sizin için otomatik olarak entegre eder.
git pull : Git pull komutu, git fetch ve git merge komutlarının amacına tek bir komutta hizmet eden bir komuttur. Pulls teriminin kendisi, bu komutu kullanan kullanıcının depodan veri veya içerik çekmeye çalıştığını açıklar. Git pull, kullanıcıdan izin istemeden veya belirtmeden git fetch işlevini yerine getirir ve kullanıcıya haber vermeden değişiklikleri birleştirir, yalnızca sonuç, yani bu komutun işleminin başarılı olup olmadığı ve uyarılar vb. kullanıcı tarafından bilinir.
  Aslında git pull = git fetch + git merge diyebiliriz. git pull projenin son halini direkt birleştirdiği için yapılan değişiklikleri gözden geçirmemize izin vermez, bu da riskli bir kullanımdır. Bu yüzden önce git fetch sonra git merge kullanmak daha riksizdir. 
7. Merge conflict nedir?
Bir proje üzerinde belirli bir süre çalıştık diyelim. Ancak bu süreç içerisinde takım arkadaşlarımız master üzerine kendi özellik dallarını birleştirdiler. Artık master o eski bildiğimiz master değil. Eğer aynı dosya üzerinde çalışılmadıysa master ne kadar çok değişirse değişsin herhangi bir çalışma sorunu olmayacaktır. Hatta aynı dosya üzerinde bile çalışsanız, çoğu zaman git çakışma yaratmadan değişiklikleri birleştirecektir. Ancak kimi zaman aynı satırlar üzerinde değişiklikler yaptığınız zaman, git doğal olarak bunu nasıl birleştireceğini bilemiyor. Bu durumda seçimi size bırakmak üzere “conflict” yani çakışma uyarısı veriyor. 
8. Merge conflict'i nasıl çözeriz?
Merge conflict hatası aldığımızda manuel olarak çakışan satırları düzenleyip tekrar birleştirme işlemi yapılır.