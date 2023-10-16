# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

Git, yazılım geliştiricilerin projelerinin sürüm kontrolünü yapmalarını, işbirliği yapmalarını ve geçmiş değişiklikleri izlemelerini sağlayan hızlı, dağıtık bir versiyon kontrol sistemidir. Projelerin farklı dallara ayrılmasını ve paralel geliştirmeyi kolaylaştırırken, değişiklikleri karşılaştırmayı ve birleştirmeyi mümkün kılar. Aynı zamanda sürüm etiketlemesi, yedekleme ve kurtarma gibi özellikler sunarak yazılım geliştirme süreçlerini daha verimli hale getirir.

2. Git ile GitHub arasında ne fark var?
Git bir versiyon kontrol sistemidir ve yerel bilgisayarınızda kullanılırken, GitHub ise Git tabanlı projelerin barındırıldığı çevrimiçi bir platformdur. GitHub, projelerinizi paylaşmanıza ve işbirliği yapmanıza yardımcı olur.

3. Neden bir branch oluşturuyoruz?
Dal (Branch) Desteği: Git, projenizi farklı dallara bölebilmenizi ve her dalın bağımsız olarak geliştirilebilmesini sağlar. Bu, paralel çalışmayı ve yeni özellikler eklerken mevcut kodu bozmadan devam etmeyi kolaylaştırır.

4. Pull Request'in amacı nedir?
Pull Requestler,bir geliştirici ya da bir grup geliştirici yeni bir projeye özellik eklemek veya bir hata düzeltmek istediğinde bu değişiklikleri ayrı bir dal(branch) üzerinde yapar.Ardından,bu değişiklikleri asıl projenin ana dalına(genellikle"master"veya "main") entegre etmek için bir PR oluşturur.Diğer geliştiriciler bu PR'yi inceleyip yorumlayabilir.Pull Request'ler, yazılım projelerinde kod değişikliklerini yönetmek, denetlemek ve işbirliği yapmak için önemli bir araçtır. Bu süreç, projenin kalitesini artırırken, geliştiricilerin daha verimli bir şekilde işbirliği yapmasını sağlar.


5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout main kodunu yazarım,main dalına geçmemi sağlar,istediğim dala geçmemi ve dalın mevcut durumunda çalışmamı sağlar.Değişikliklerimi taşımak için ise commit komutunu kullanırım.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch,uzak depodaki güncellemeleri getirir ancak yerel çalışma düzenini düzenlemez.git merge farklı dallardaki değişiklikleri birleştirirken kullanırız,git pull komutu aslında git fetch ve git pull komutlarını otamatik  olarak birleştirir,uzak depodaki güncellemeleri alarak yerel çalışma dizinine otamatik olarak birleştirir.

7. Merge conflict nedir?
Merge conflict (birleştirme çatışması), çoğunlukla Git gibi versiyon kontrol sistemlerinde karşılaşılan bir durumdur. Bu durum, farklı dallardaki veya sürümlerdeki değişikliklerin çakıştığı ve Git'in hangi değişikliklerin birleştirileceğini anlayamadığı zaman meydana gelir.

8. Merge conflict'i nasıl çözeriz?


Merge conflict çözümü için aşağıdaki adımları izleriz:

Çatışma bildirimi alırsınız ve hangi dosyada ve nerede çatışmanın olduğunu belirten bilgileri içerir.
Karşılaştığınız çatışmayı manuel olarak düzeltirsiniz, yani çakışan değişiklikleri nasıl birleştirmek istediğinizi belirlersiniz.
Çözülen dosyaları kaydeder ve git add komutu ile işlenmiş olarak işaretlersiniz.
git commit ile çözümü kaydedersiniz.
Son olarak, git merge veya git pull ile birleştirme işlemini tamamlarsınız.Merge conflict'ler, paralel geliştirme yapan çok sayıda geliştirici veya birden fazla dalı yönetirken ortaya çıkabilir ve bu çatışmaları çözmek, projelerin düzgün bir şekilde birleştirilmesini ve sürdürülmesini sağlamak için önemlidir.
