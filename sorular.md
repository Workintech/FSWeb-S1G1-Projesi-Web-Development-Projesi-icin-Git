# Araştırma Soruları

## Sorular

1. Git nedir?

Git, yazılım projelerinin geliştirme sürecinde yapılan değişiklikleri izlemek, yönetmek ve paylaşmak için kullanılır.

Yazılımcılar, Git'i kullanarak projelerinde yapılan değişiklikleri takip edebilir, geçmişteki versiyonlara geri dönebilir ve aynı projede birden fazla geliştiricinin aynı anda çalışmasını sağlayabilir.

Git'in dağıtık olması, projenin tam bir kopyasını her bir yazılımcıya veritabanı olarak sağlar. Bu sayede her bir geliştirici, projeye katkıda bulunmak için kendi yerel kopyasını kullanabilir ve daha sonra bu değişiklikleri projenin merkezi bir kopyasıyla senkronize edebilir.

2. Git ile GitHub arasında ne fark var?

Git: Git, bir  kontrol sistemi olarak çalışır ve yerel bir bilgisayar üzerinde projenin tüm geçmişini izler, yönetir ve takip eder. Projenin tüm kopyalarını saklar ve projeye yapılan değişiklikleri kolayca geri almanızı veya birleştirmenizi sağlar. 

GitHub: GitHub, bir kod barındırma platformudur. Projelerimizi Git kullanarak yönetebileceğimiz bir depo sağlar. GitHub, projelerimizi çevrimiçi olarak depolamamıza, paylaşmamıza ve işbirliği yapmamıza olanak tanır. Açık kaynak projeler için yaygın bir işbirliği platformudur ve birçok geliştiricinin kodlarını paylaştığı ve projeleriyle katkıda bulunduğu bir topluluk sağlar.

3. Neden bir branch oluşturuyoruz?

Branch'ler, projenin farklı bölümlerinde ayrı çalışmalar yapmayı ve değişiklikleri güvenli bir şekilde yönetmeyi kolaylaştırır. Her branch, ayrı bir çalışma alanı sağlar ve projenin temel kopyasından bağımsız olarak değişiklikleri takip edebilmemizi sağlar. Bir branch oluşturarak, ana branch'ten (genellikle "main" olarak adlandırılır) bağımsız olarak yeni bir özellik veya değişiklik geliştirebiliriz. Bu, birden fazla geliştiricinin aynı anda farklı özellikler üzerinde çalışabilmesini sağlar. Her bir branch, özellik geliştirme süreci tamamlandığında ana branch ile birleştir


4. Pull Request'in amacı nedir?
PR süreci, sürekli entegrasyon ve otomatik test süreçlerini destekler. Projede tanımlanmış otomatik testler, bir PR oluşturulduğunda veya güncellendiğinde otomatik olarak çalıştırılabilir. Bu, değişikliklerin projeye olumsuz etkisi olup olmadığını belirlemek için önemli bir adımdır.

PR, proje yönetiminde kodun daha kaliteli ve güvenilir olmasını sağlar. İnceleme ve geribildirim süreci sayesinde, geliştiriciler arasında etkileşim ve işbirliği sağlanırken, projenin bütünlüğü ve sürekliliği korunur.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

Bir branctan diğerine geçmek için "git checkout" komutunu kullanırım. Örneğin; git checkout "seyma-kose" (daha önce oluşturmadıysam branchi ---> git checkout -b "seyma-kose") git checkout "main" olur.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

git fetch: Bu komut, uzaktaki bir Git deposundan güncel verileri çekmek için kullanılır. Yerel depoda bulunmayan yeni branch'leri ve commit'leri getirir. Ancak, yerel çalışma alanını etkilemeden yalnızca verileri çeker. Özetle, git fetch uzaktaki değişiklikleri getirirken yerel dosyaları etkilemez.

git merge: Bu komut, iki farklı branch'i birleştirmek için kullanılır. Örneğin, mevcut branch ile başka bir branch arasındaki değişiklikleri birleştirebilir. Merge komutunu kullandığımızda, Git, farklı branch'lerde yapılan değişiklikleri birleştirir ve sonucunda birleştirme commit'i oluşturur. Bu, değişiklikleri mevcut branch'e uygular ve geçerli branch'i günceller.

git pull: Bu komut ise, uzaktaki bir Git deposundan verileri çekmek ve yerel branch ile birleştirmek için kullanılır.


7. Merge conflict nedir?

Merge işlemi sırasında, çakışan veya farklılık gösteren değişikliklerin aynı dosyanın aynı satırında yapılması durumunda merge conflict ortaya çıkar.

Merge conflict, Git'in otomatik olarak farklılıkları birleştirememesi veya hangi değişikliklerin kabul edileceği konusunda belirsizlik olduğunda gerçekleşir. Örneğin, aynı dosyanın aynı satırında farklı branch'lerde yapılan değişiklikler veya aynı satıra eklenen farklı kod parçaları merge conflict'a neden olabilir.

8. Merge conflict'i nasıl çözeriz?
Merge conflict durumunda, Git bir çakışma bildirir ve hangi dosyaların veya satırların çakıştığını belirtir. Çakışmalar elle çözülmesi gereken durumlardır çünkü Git otomatik olarak nasıl birleştirileceğini bilemez.

Çakışmayı çözmek için, ilgili dosyayı metin düzenleyicide açıp çakışan kısımları düzenlememiz gerekebilir. Daha sonra, çakışmayı çözen değişiklikleri ekleyip commit yapmamız gerekir.