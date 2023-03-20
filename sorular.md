# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Git, açık kaynak kodlu bir versiyon kontrol sistemi yazılımıdır. Proje kaynak kodlarının sürüm kontrolü, işbirliği ve paylaşımını kolaylaştırır. Bir proje üzerinde birden fazla kişi çalışırken, değişikliklerin takibi ve yönetimi oldukça önemlidir. Git bu süreci yönetmek için birçok araç ve özellik sunar.
2. Git ile GitHub arasında ne fark var?
Git, bir versiyon kontrol sistemi yazılımıdır ve dosyalarınızı yerel bilgisayarınızda saklayabilirsiniz. Git, kodunuzu takip etmenize, değişiklikleri geri alma, farklı sürümleri karşılaştırma ve daha pek çok şey yapmanıza olanak tanır.

Öte yandan GitHub, Git tabanlı bir web barındırma hizmetidir. GitHub üzerinde, kodunuzu paylaşabilir, işbirliği yapabilir ve diğer geliştiricilerin projelerinize katkıda bulunmasına izin verebilirsiniz. GitHub, açık kaynaklı projeler için özellikle popülerdir ve projelerinizi dünya genelindeki diğer geliştiricilerle paylaşmanıza olanak sağlar.
3. Neden bir branch oluşturuyoruz?
Bir branch (dal) oluşturmanın birkaç nedeni vardır:

Çalışma alanınızı düzenlemek için: Büyük projelerde, birçok insan aynı anda çalışır ve her biri farklı bir özellik veya görev üzerinde çalışabilir. Her biri kendi branch'ında çalışabilir ve daha sonra tüm değişikliklerin birleştirilmesiyle birlikte ana projeye dahil edilebilir.

Deneme yapmak için: Bir değişiklik yapmadan önce, bir branch oluşturarak değişikliklerinizi test etmeniz daha güvenlidir. Eğer değişiklikler başarılı değilse, ana projenizde herhangi bir sorun oluşmadan önce branch'ınızı silebilirsiniz.

Yeni özellikler eklemek için: Yeni bir özellik eklemek istediğinizde, bunu mevcut kod tabanının üzerine yazmadan önce bir branch oluşturabilirsiniz. Böylece yeni özellik geliştirme sürecinde tüm değişiklikleri bu branch'ta yapabilirsiniz.

Farklı sürümleri yönetmek için: Eğer birden fazla sürüm yönetiyorsanız, farklı sürümler için farklı branch'lar oluşturabilirsiniz. Böylece, farklı sürümlere ait kodları düzenli bir şekilde yönetebilirsiniz.

Sonuç olarak, bir branch oluşturmak, kodunuzu düzenli bir şekilde yönetmek ve projenizde yapılan değişiklikleri takip etmek için önemlidir.
4. Pull Request'in amacı nedir?
Pull request, açık kaynaklı bir yazılım projesinde ya da takım halinde çalışan bir ekip içinde yapılan değişiklikleri ve katkıları diğer geliştiriciler veya ekibin diğer üyeleriyle paylaşmak için kullanılan bir araçtır.

Bir pull request, öncelikle bir geliştiricinin kendi local branch'ına yaptığı değişikliklerin, ana projenin bulunduğu repository'ye eklenmesi isteği anlamına gelir. Bu istek, diğer geliştiricilerin veya ekip üyelerinin yaptığınız değişiklikleri inceleyip, test edip, onaylaması ve son olarak da projeye dahil edilmesi ile sonuçlanır.

Pull request aynı zamanda, ekip içinde yapılan değişikliklerin şeffaflığını sağlamak için de kullanılır. Bu sayede, bir değişiklik yapmak isteyen geliştiriciler, önceden yapılan değişiklikleri inceleyerek, projenin genel yapısına ve işleyişine uygun bir şekilde katkıda bulunabilirler.

Sonuç olarak, pull request, ekip içinde işbirliğini kolaylaştıran, projeye dahil edilecek değişikliklerin kontrol altında tutulmasını ve hataların önlenmesini sağlayan bir araçtır.
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
"git checkout komutu", bir branch'ten diğerine geçmek için kullanılır.

Eğer isim-soyisim branch'inde çalışıyorsam ve main branch'e geçmek istiyorsam, git checkout main komutunu kullanabilirim. Bu komut, çalışma kopyasını main branch'e geçirir ve mevcut değişiklikleri isim-soyisim branch'inde kaydeder. Bu sayede, ana branch'e geçiş yaparak orada çalışmaya devam edebiliriz.
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch, git merge ve git pull komutları, Git'te farklı branch'ler arasındaki farkları ve değişiklikleri birleştirmek için kullanılan komutlardır. Ancak her biri farklı işlevlere sahiptir. Aşağıda bu komutların farkları açıklanmıştır:

git fetch: Uzak bir repository'deki (örneğin GitHub'daki) değişiklikleri yerel repository'ye indirmek için kullanılır. Ancak bu komut, yerel branch'lerde herhangi bir değişiklik yapmaz. Yani, uzak repository'de yapılan değişiklikleri görmenizi sağlar ancak bu değişiklikleri yerel branch'lerinize birleştirmez.

git merge: Farklı branch'lerde yapılan değişiklikleri birleştirmek için kullanılır. Örneğin, feature branch'inde yapılan değişiklikleri main branch'ine birleştirmek istediğinizde git merge komutunu kullanabilirsiniz. Bu komut, farklı branch'lerdeki değişiklikleri bir araya getirir ve yerel branch'inizde birleştirilmiş değişiklikler oluşturur.

git pull: git fetch ve git merge komutlarını birleştirir. Yani, bu komut, uzak repository'deki değişiklikleri indirir ve yerel branch'inize birleştirir. git pull komutu, git fetch ve git merge komutlarını tek bir adımda yapmanızı sağlar.

Özetle, git fetch, uzak repository'deki değişiklikleri indirir ancak yerel branch'lerde birleştirme işlemi yapmaz. git merge, farklı branch'lerdeki değişiklikleri birleştirmek için kullanılır. git pull, git fetch ve git merge komutlarını bir arada kullanarak, uzak repository'deki değişiklikleri indirir ve yerel branch'lerinizi birleştirir.
7. Merge conflict nedir?
Merge conflict, Git'te birleştirme (merge) işlemi sırasında farklı branch'lerde aynı dosyaların farklı satırlarının değiştirilmiş olması durumunda ortaya çıkan bir durumdur.

Örneğin, bir geliştirici feature branch'inde bir dosyanın bir satırını değiştirirken, başka bir geliştirici de main branch'inde aynı dosyanın aynı satırını değiştirirse, Git bu değişiklikleri birleştirmekte (merge) sorun yaşayabilir ve merge conflict durumu ortaya çıkabilir.

Bu durumda, Git otomatik olarak birleştirme yapamaz ve geliştiricinin merge conflict'i çözmesi gerekmektedir. Geliştirici, çakışan değişiklikleri düzenleyerek veya hangi değişikliği kullanacağına karar vererek merge conflict'i çözebilir.

Merge conflict, geliştiricilerin eş zamanlı olarak aynı dosyalar üzerinde çalıştığı durumlarda sıklıkla ortaya çıkar ve Git'te birleştirme işleminin güvenli bir şekilde gerçekleştirilebilmesi için önemlidir.
8. Merge conflict'i nasıl çözeriz?
Merge conflict çözmek için aşağıdaki adımları takip edebilirsiniz:

Öncelikle, merge conflict'in hangi dosyada ve hangi satırlarda olduğunu öğrenmeniz gerekiyor. Bu bilgiyi Git tarafından size verilen hata mesajından öğrenebilirsiniz.

Sonra, conflict'i çözmek için düzenleyeceğiniz dosyayı açmanız gerekiyor. Dosya içinde, Git tarafından size conflict'in neden olduğu satırlar özel olarak işaretlenmiş olacak. Bu işaretlemelerle, hangi değişikliklerin hangi branch'ten geldiği ve nasıl çakıştığı belirtilir.

Conflict'i çözmek için, işaretlenmiş satırları düzenleyerek çakışmayı çözmeniz gerekiyor. Bu işaretlenmiş satırlar arasından hangisini kullanacağınıza karar vermelisiniz. Ya da iki değişikliği birleştirebilirsiniz.

Düzenleme işlemi bittiğinde, dosyayı kaydedin ve değişikliklerinizi commit edin. Conflict çözüldüğünde, Git artık birleştirme işlemini tamamlayabilir.

Bu adımları takip ederek merge conflict'i kolayca çözebilirsiniz. Ancak, bazen çözümler oldukça karmaşık olabilir, özellikle birleştirilecek değişiklikler çok büyükse veya çok sayıda conflict varsa. Bu durumda, dikkatli olmanız ve değişiklikleri doğru bir şekilde birleştirmeniz önemlidir.