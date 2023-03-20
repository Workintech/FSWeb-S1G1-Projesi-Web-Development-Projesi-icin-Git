# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

cevap:Git,yazılım geliştirme projelerinin sürüm kontrolleri ve beraber çalışma imkanı için kullanılan açık kaynaklı bir versiyon kontrol sistemi alternatiflerindendir.


2. Git ile GitHub arasında ne fark var?

cevap:Git, bir versiyon kontrol sistemi olarak kullanılan bir yazılımdır. Git, dosyaların, kodların ve diğer proje materyallerinin sürümlerini takip etmenizi, değişikliklerinizi izlemenizi ve bu değişiklikleri birlikte çalışan diğer geliştiricilerle paylaşmanızı sağlar.

GitHub ise, Git tabanlı bir bulut tabanlı hizmettir. GitHub, Git projelerini depolamanız, yönetmeniz, paylaşmanız ve diğer geliştiricilerle işbirliği yapmanız için bir platform sağlar. GitHub, kod incelemeleri, takım çalışması, açık kaynaklı proje katkıları, sorun takibi ve proje yönetimi gibi ek özellikler de sunar.

Yani kısacası, Git bir versiyon kontrol sistemidir ve yerel olarak çalışırken, GitHub ise bulut tabanlı bir platformdur ve uzaktaki diğer geliştiricilerle işbirliği yapmanızı sağlar. Git ile projenizi yerel olarak takip edebilirsiniz, ancak GitHub'a yükleyerek diğer geliştiricilerle paylaşabilir ve işbirliği yapabilirsiniz.

3. Neden bir branch oluşturuyoruz?

cevap:yazılım geliştirme projelerinin her aşaması rutin bir şekilde işlemek zorunda olmadığı gibi tek bir yazılımcı tarafından da kodlanmak zorunda değildir.Branch oluşturmak yazılım projeniz içerisinde var olan bir noktada size farklı bir yol ayrımı sunup projeyi farklı bir alternatifle ana branche dokunmadan ilerletme imkanı sunar ve isterseniz değişiklikleri commitlemeden silip branchi yok edebilir isterseniz de branchi ana branch ile merge edip değişiklikleri kalıcı hale getirebilirsiniz.Esasında branch oluşturmak projenin farklı bir noktaya odaklanmasında geliştiricilere yardımcı olmaktır.

4. Pull Request'in amacı nedir?

cevap:pull request githubda bulunan açık kaynak kodlu bir projede başka bir geliştiricinin yapmış olduğu değişiklikleri ve geliştirmeleri orijinal projeye yada repoya birleştirme talebidir.Amacı sahibi olmadığınız açık kaynak projelere yardımcı olabilmek ve çabalarınızı proje sahibine gösterebilmek için talep göndermektir.Tabii bu talebi kabul etmek veya red etmek tamamen repo sahibinin insiyatifindedir.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

cevap:git içerisindde bir branchden diğerine git checkout komuutu ile gidebiliriz örneğin:isim-soyisim branchinden master branchine geçiş için
git checkout main demeniz yeterli bir kez daha git checkout isim-soyisim yazarsanız isim-soyisim branchine geri dönebilirsiniz

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

cevap:git fetch,git merge ve git pull gitte uzak bir repodan yerel bir repoya veri kopyalamak için kullanılan üç  farklı kommuttur.Farklarını açıklayabilmek için üç git komutunun teker teker neler olduğunu özetlemekte fayda var.

git fetch:git fetch komutu remote repodaki son değişiklikleri local repoya indirir bu noktada git pulla benzer iş yaparken bu değişiklikleri local repoyla birleştirmez sadece cihazımıza kaydeder mevcut çalışma alınında değişiklik oluşturmaz.

git merge:merge komutu farklı dalları veya değişiklikleri birleştirmek için kullanılır.Birleştirme işlemi, iki farklı dalın ya da değişikliklerin aynı dosyaları değiştirdiği durumlarda otomatik olarak çakışma çözümleme yapar ve kullanıcıya çözümlemesi için seçenekler sunar. Birleştirme işlemi tamamlandıktan sonra, değişiklikler yerel depoya uygulanır.

git pull:ilk iki komutun özellikleri göz önüne alındığında git pull tek bir komutla hem fetch hem de merge yapmak için kullanılan özelleşmiş git komutudur.özetle git pull remote repodan güncdllenmiş dataları local repoya çekip local repoyla birleştirme işlemi yapar ve çalışılan dosyanın güncel kalmasını sağlar.

7. Merge conflict nedir?

cevap:merge conflict yazılım projesinde birden fazla kişi tarafından aynı veya farklı branchlerde yapılan değişikliklerin neticesinde merge işlemi sonucu yaşanan çakışmadır.

8. Merge conflict'i nasıl çözeriz?

cevap:merge conflict genellikle yazılımcının manuel çözmesi gereken bir sorundur.Yazılmcılar,çatışan değişiklikleri inceleyerek ve hangi değişikliğin kalması gerektiğine karar vererek bu conflicti çözerler.