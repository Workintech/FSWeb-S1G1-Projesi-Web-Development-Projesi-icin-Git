# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

Git, yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol sistemidir. Git sayesinde yapacağınız projelerin adım adım versiyonlarının kopyalarını alarak daha sonra ihtiyaç duyduğunuzda aldığınız kopyalara yani versiyonlara kolayca dönebiliyorsunuz.  İlk sürümü Linux çekirdeği'nin geliştirilmesinde kullanılmak üzere 2005 yılında Linus Torvalds tarafından tasarlanıp geliştirilmiş, 2019 yılı itibarıyla %70 pazar payına ulaşmıştır. Açık kaynaklı özgür bir yazılım ürünü olan Git'i istediğiniz gibi kullanabilirsiniz.


2. Git ile GitHub arasında ne fark var?

Git, kaliteli yazılım geliştirmek için veri güvencesi sağlayarak dağıtılmış doğrusal olmayan iş akışlarını destekleyen dağıtılmış bir sürüm kontrol sistemidir.	
Github, Git sürüm kontrol deposu için web tabanlı bir barındırma hizmetidir.

Git, yazılım geliştirme ve kaynak kodu yönetimi için kullanılır.
Github, dağıtılmış sürüm kontrolü, kaynak kodu yönetimi, erişim kontrolü, hata izleme sağlar.

3. Neden bir branch oluşturuyoruz?

Branch oluşturmak kullanıcıya çalıştığı projenin farklı versiyonlarına erişmesini sağlar. Kullanıcı, projesine bir yenilik eklemek istediğinde, yaptığı değişiklik projenin çalışmasını olumsuz etkileyebilir. Bu gibi durumlarda projemizin o anki halini bozmamak için branch kullanabiliriz. Branch yardımı ile projemizin çalışır halini kaydedip, yeni eklenti üzerinde rahatlıkla çalışabiliriz. Projemizde herhangi bir sorun çıktığı takdirde geri dönüp önceki versiyona kolaylıkla erişebiliriz. Branch, sadece projenizi değiştirirken ya da güncellerken eski halini korumak ile kalmıyor. Projenize bir versiyon çıkarttığınız zaman her yeni versiyon için repository oluşturmak yerine her bir versiyon için farklı branchler açabilirsiniz. Böylece versiyonları bir arada kolayca takip edebilir ve erişebilirsiniz.

4. Pull Request'in amacı nedir?

Fork ettiğimiz bir projenin üzerinde çalışıp, projede yaptığımız değişiklikleri, projenin sahibine pull request olarak gönderebiliriz.
•Pull request olarak göndermek demek; ben projede değişiklikleri yaptım,sen de bu bu değişiklikleri onayla ve projene merge et, ben de katkı sağlamış olayım demek.
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

git fetch nedir?
 git fetch‘i herhangi bir zamanda refs/remotes/<remote>/ altındaki remote branch’inizi update etmek için kullanabilirsiniz. Bu operasyon refs/heads altındaki lokal branchleri değiştirmez. Aynı zamanda üzerinde çalıştığınız kopyayı değiştirmeden işlem yapma açısından da güvenlidir. Hatta bazı programcılar git fetch için bir cron job olulşturup periyodik bir şekilde arkaplanda fetch çalıştırabilir.

git pull nedir?
 git pull‘u ise local bir branchi remote versiyona güncellemek için kullanırız. Aynı zamanda diğer remote brachleri de update etmek için yararlıdır.

Yani:

fetch kullandığınızda, Git, hedef branchteki bulunan ve mevcut branchte bulunmayan herhangi bir commit işlemini yapar ve yerel reponuza kaydeder. Ancak, bunları mevcut branchiniz ile birleştirmez. Peki git fetch ne işe yarar? Repomuzu güncel tutmamız gerekiyorsa, ancak dosyalarımızı güncellersek de bozulabilecek bir şeyler varsa fetch kullanmayı tercih ederiz. Bu işlemleri mevcut branchinize entegre etmek için sonrasında merge kullanmalısınız.

pull kullandığınızda, Git otomatik olarak merge çalışır. Bağlamsal olarak hassastır, bu nedenle Git şu anda çalıştığınız branch için herhangi bir commit varsa birleştirecektir. Dolayısıyla git pull ne işe yarar diye bir soru sorarsak; pull yapılan değişiklikleri gözden geçirmenize izin vermeden otomatik olarak birleştirir diyebiliriz. Eğer branchlerinizi dikkatlice yönetmiyorsanız, sık sık sorunlarla karşılaşabilirsiniz.

Merge kelimesi, Türkçeye “birleşmek” olarak çevrilir. Git’in güzel yanlarından birisi de budur zaten. Verdiğiniz komutlar direkt olarak yapılan iş hakkında bilgi verir. Örneğin git add (ekle), eklemeye yarar. Git commit (işlemek), kayıt almaya, git merge (birleştirmek), iki branchi birleştirmeye yarar. Gördüğünüz gibi isimlerin anlamları ve yaptığı işler birbiriyle son derece yakındır ve bu durum birçok komut için geçerlidir. Anlamsız veya soyut isim kullanımından mümkün olduğunca kaçınılmıştır. Neyse konuyu çok dağıtmayalım. Merge dediğimiz işlem iki branchi birleştirmektir.

7. Merge conflict nedir?

Aynı dosyalar üzerinde çalışınca conflict yanı çakışma yaşamak kaçınılmazdır. Duruma göre bu çakışmalar çok can sıkıcı olabilir. Bazen kabus haline bile dönüşebilir. Halk arasında conflict yemek olarak da bilinir.


8. Merge conflict'i nasıl çözeriz?

ki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır. Bu durumda çakışma yaşayan kişi gerekirse ekipteki diğer kişi ile beraber oturup çakışmayı çözdükten sonra merge işlemine devam etmelidir.
