# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Git, yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol sistemidir. Git sayesinde yapacağınız projelerin adım adım versiyonlarının kopyalarını alarak daha sonra ihtiyaç duyduğunuzda aldığınız kopyalara yani versiyonlara kolayca dönebiliyorsunuz.

2. Git ile GitHub arasında ne fark var?
Git, bir versiyon takip yazılımıdır (bkz: VCS Nedir ve Nasıl Kullanılır?). Lokal olarak bilgisayarda çalışır ve Github olmadan da Git'i kullanabilmek mümkündür. Git ile projelreinizin versiyonlamasını yapabilir ve bunu internete bile bağlanmadan kullanabilirsiniz. Herhangi bir kayıt işlemine ihtiyaç duymaz.

Github ise Git repository'lerinin cloud üzerinde saklandığı online bir servistir. Github'a kayıt olmanız gereklidir ve ek fayda olarak da başka kişilerin repository'lerine erişebilir ya da kendi repository'lerinize erişmelerini ve katkı sağlamalarını isteyebilirsiniz. Online bir servistir ve offline olarak kullanabilneniz mümkün değildir.

3. Neden bir branch oluşturuyoruz?

Branch oluşturmak kullanıcıya çalıştığı projenin farklı versiyonlarına erişmesini sağlar. Kullanıcı, projesine bir yenilik eklemek istediğinde, yaptığı değişiklik projenin çalışmasını olumsuz etkileyebilir. Bu gibi durumlarda projemizin o anki halini bozmamak için branch kullanabiliriz. Branch yardımı ile projemizin çalışır halini kaydedip, yeni eklenti üzerinde rahatlıkla çalışabiliriz. Projemizde herhangi bir sorun çıktığı takdirde geri dönüp önceki versiyona kolaylıkla erişebiliriz. Branch, sadece projenizi değiştirirken ya da güncellerken eski halini korumak ile kalmıyor. Projenize bir versiyon çıkarttığınız zaman her yeni versiyon için repository oluşturmak yerine her bir versiyon için farklı branchler açabilirsiniz. Böylece versiyonları bir arada kolayca takip edebilir ve erişebilirsiniz.

4. Pull Request'in amacı nedir?
GitHub Reposunda yeni bir branch açtıktan sonra değişikliklerini bu Branch'e yaparsın ve asıl Branch'e bir pull request(merge Request'te denir aynı zamanda) oluşturursun. Bu pull request onaylandığında değişiklikleri yaptığın branch, ana Branch'e katılır ve değişiklikler ana Branch'e yansır.

Örnek bir senaryo vermek gerekirse; Ali, Technopat web sitesine chat özelliği eklemek istesin. Ali Technopat development Branch'i üzerinden yeni bir branch oluşturup bunun adını feature-chat diye isimlendirir ve işi bittiğinde development'a bir pull request atar. Bu PR yetkisi olan kişi tarafından onaylanırsa artık development Branch'i bu chat branchinde yapılan commitleri içermiş olur.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

Git’de branch değiştirmek için git checkout komutunu kullanırız.

git checkout main 

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

git fetch yerel git'inize orijinalden en son meta-veri bilgilerini almasını söyleyen komuttur (ancak herhangi bir dosya aktarımı yapmaz. Bu daha çok, herhangi bir değişiklik olup olmadığını kontrol etmeye benzer). 
git merge Merging en basit anlamda herhangi bir brach'de yaptığımız değişiklikleri master branch'imiz ile birleştirme veya master branch'e entegre etme işlemidir. 
git pull git fetch ve git merge komutlarının amacına tek bir komutta hizmet eden bir komuttur.

7. Merge conflict nedir?

İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır. 
Bu durumda çakışma yaşayan kişi gerekirse ekipteki diğer kişi ile beraber oturup çakışmayı çözdükten sonra merge işlemine devam etmelidir.

8. Merge conflict'i nasıl çözeriz?

Öncelikle her iki kodda kontrol edilir. Daha az komutla daha mantıklı çözüm içeren kod için kabul yapılır. Bu konsept ile ilerlenir. 

