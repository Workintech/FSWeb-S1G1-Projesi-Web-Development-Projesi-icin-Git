## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
Versiyon kontrolü ve Git hakkında
Bir versiyon kontrol sistemi veya VCS, insanlar ve ekipler projeler üzerinde birlikte çalıştıkça değişikliklerin geçmişini izler. Geliştiriciler projede değişiklik yaptıkça, projenin daha önceki herhangi bir sürümü herhangi bir zamanda kurtarılabilir.

Geliştiriciler şunları öğrenmek için proje geçmişini inceleyebilir:

Hangi değişiklikler yapıldı?
Değişiklikleri kim yaptı?
Değişiklikler ne zaman yapıldı?
Değişikliklere neden ihtiyaç duyuldu?
VCS'ler her katılımcıya bir projenin birleşik ve tutarlı bir görünümünü sunarak halihazırda devam etmekte olan çalışmaları ortaya çıkarır. Değişikliklerin şeffaf bir geçmişini, bunları kimin yaptığını ve bir projenin gelişimine nasıl katkıda bulunduklarını görmek, ekip üyelerinin bağımsız çalışırken aynı hizada kalmalarına yardımcı olur.

Dağıtılmış bir sürüm kontrol sisteminde, her geliştirici projenin ve proje geçmişinin tam bir kopyasına sahiptir. Bir zamanlar popüler olan merkezi sürüm kontrol sistemlerinin aksine, DVCS'lerin merkezi bir depoya sürekli bağlantıya ihtiyacı yoktur. Git en popüler dağıtılmış sürüm kontrol sistemidir. Git, hem açık kaynak hem de ticari yazılım geliştirme için yaygın olarak kullanılır ve bireyler, ekipler ve işletmeler için önemli faydalar sağlar.

Git, geliştiricilerin değişikliklerinin, kararlarının ve herhangi bir projenin ilerleyişinin tüm zaman çizelgesini tek bir yerde görmelerini sağlar. Bir projenin geçmişine eriştikleri andan itibaren, geliştirici projeyi anlamak ve katkıda bulunmaya başlamak için ihtiyaç duydukları tüm bağlama sahip olur.

Geliştiriciler her zaman diliminde çalışır. Git gibi bir DVCS ile, kaynak kod bütünlüğünü korurken işbirliği her zaman gerçekleşebilir. Geliştiriciler dalları kullanarak üretim kodunda güvenli bir şekilde değişiklik önerebilir.

Git kullanan işletmeler, ekipler arasındaki iletişim engellerini ortadan kaldırabilir ve ekiplerin en iyi işlerini yapmaya odaklanmalarını sağlayabilir. Ayrıca Git, büyük projelerde işbirliği yapmak üzere işletme genelindeki uzmanları bir araya getirmeyi mümkün kılar.
2. Git ile GitHub arasında ne fark var?
GitHub, Git depolarını barındırır ve geliştiricilere komut satırı özellikleri, sorunlar (iş parçacıklı tartışmalar), çekme istekleri, kod incelemesi veya GitHub Marketplace'teki ücretsiz ve satın alınabilir uygulamalar koleksiyonunun kullanımı yoluyla daha iyi kod göndermeleri için araçlar sağlar. GitHub akışı gibi işbirliği katmanları, 15 milyon geliştiriciden oluşan bir topluluk ve yüzlerce entegrasyona sahip bir ekosistem ile GitHub, yazılımın oluşturulma şeklini değiştiriyor.

GitHub, işbirliğini doğrudan geliştirme sürecine dahil ediyor. Çalışmalar, geliştiricilerin gereksinimleri veya yönü ana hatlarıyla belirleyebildiği ve ekip üyeleri için beklentiler oluşturabildiği depolar halinde düzenlenir. Ardından, GitHub akışını kullanarak, geliştiriciler güncellemeler üzerinde çalışmak için bir dal oluşturur, değişiklikleri kaydetmek için işler, değişiklikleri önermek ve tartışmak için bir çekme isteği açar ve herkes aynı sayfada olduğunda çekme isteklerini birleştirir. 
3. Neden bir branch oluşturuyoruz?
Branch, deponuzun sınırlı bir alanında özellikler geliştirmenize, hataları düzeltmenize veya yeni fikirleri güvenle denemenize olanak tanır.

Her zaman mevcut bir Branchdan bir Branch oluşturursunuz. Tipik olarak, deponuzun varsayılan Branchından yeni bir Branch oluşturabilirsiniz. Daha sonra bu yeni Branch üzerinde diğer kişilerin depoda yaptığı değişikliklerden ayrı olarak çalışabilirsiniz. Bir özellik oluşturmak için oluşturduğunuz bir Branch, genellikle özellik Branchı veya konu Branchı olarak adlandırılır. 
4. Pull Request'in amacı nedir?
Fork ettiğimiz projenin üzerinde çalışarak proje üzerinde yaptığımız değişiklikleri, projenin sahibine pull request şeklinde gönderebiliriz. Pull request olarak göndermenin anlamı; proje üzerinde değişiklik yaptım, sen de bu değişiklikleri onaylarak  projene merge et demek anlamına gelir.Bazı değişiklikleri yaptıktan sonra, bir pull request talebinde bulunarak bu kodu bir şubeye geri gönderebilirsiniz. Pull request talebi, temelde branch’dan sorumlu kişiden kodunuzu eklemesini istemektir. Ayrıca o kişinin kodda tam olarak neyi değiştirdiğinizi görmesine de yardımcı olur.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
Git’te branch değiştirmek için checkout komutunu kullanıyoruz. git checkout dedikten sonra branch adımızı yazmamız yeterli.
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch, “yerel depomu uzaktaki deponun içeriğine güncelle” anlamına gelir.
git pull “uzaktaki deponun değişikliklerini yerel depoya getir” der.
git pull ve git fetch arasındaki fark;git pull önce bir git fetch yapar, sonrasında ise git merge uygular.
git merge komutu ile kaynak branch'deki commit edilmiş değişiklikler HEAD'e entegre edilir.
7. Merge conflict nedir?
Git genellikle dallar arasındaki farklılıkları çözebilir ve bunları otomatik olarak birleştirebilir. Genellikle değişiklikler farklı satırlarda, hatta farklı dosyalardadır, bu da birleştirmeyi bilgisayarların anlamasını kolaylaştırır. Ancak bazen Git'in sizin yardımınız olmadan çözemeyeceği rakip değişiklikler olabilir. Genellikle, insanlar aynı dosyanın aynı satırında farklı değişiklikler yaptığında veya bir kişi bir dosyayı düzenlerken başka bir kişi aynı dosyayı sildiğinde birleştirme çakışmaları meydana gelir.
Aynı dosyanın aynı satırında farklı değişikliklerin çakışması durumuna merge conflict denir.
8. Merge conflict'i nasıl çözeriz?
Bir birleştirme çakışmasını çözmek için, son birleştirmede tutmak istediğiniz değişiklikleri seçmek üzere çakışan dosyayı manuel olarak düzenlememiz gerekir.
Bir birleştirme çakışmasını çözmek için, son birleştirmede tutmak istediğiniz değişiklikleri seçmek üzere çakışan dosyayı manuel olarak düzenlemeniz gerekir. Bir birleştirme çakışmasını çözmenin birkaç farklı yolu vardır:
Merge conflict, Git deponuzdaki farklı dallarda aynı dosyanın aynı satırında farklı değişiklikler yapan kişiler gibi satır değişikliklerinden kaynaklanıyorsa, conflict editor kullanarak GitHub'da çözülebilir.

Diğer tüm Merge conflict türleri için, Merge conflictı deponun yerel bir klonunda çözmeniz ve değişikliği GitHub'daki dalınıza göndermeniz gerekir. Değişikliği göndermek için komut satırını veya GitHub Desktop gibi bir aracı kullanabilirsiniz. 