# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
 Git yazılım geliştirme süreçlerinde kullanılan versiyon kontrol sistemidir. Yazdığımız projeleri tutmayı ve yönetmeyi sağlar.
2. Git ile GitHub arasında ne fark var?
Git bir versiyon kontrol sistemidir. Github ,projelerimizin depolandığı remote sunucudur.Githuba proje ekleyebilir aynı zamanda farklı projelere github üzerinden erişebiliriz.
3. Neden bir branch oluşturuyoruz?
Proje yapmak istediğimiz yenilikler için veya projede olan hataların düzeltilmesini sağlamak için projeye değişiklik yapmak istediğinde projenin o anki halini bozmamak amacıyla farklı bir branch oluşturulur.
4. Pull Request'in amacı nedir?
Branch'den sorumlu kişiden projede yaptığımız değişikliklerin eklenmesini istemektir.
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout 'geçmek istediğimiz branch ismi'
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch de local repomuzdaki çalışma durumumuzu etkilemeden remote repodaki güncellemeleri indirmemizi sağlar. Git pull ise remote repodan çekilen verileri localdekilerle eşleşecek şekilde günceller.  Gİt merge komutu ise birleştirmek demektir. başka bir branchteki değişiklikleri kendi branchinize entegre etme işlemidir.
7. Merge conflict nedir?
İki kişi aynı dosya ve satırı değiştirirse ve git otomatik olarak merge edemezse conflict yani çakışma olacaktır.

8. Merge conflict'i nasıl çözeriz?
ortak yapılan değişikliklerden biri geri alınabilir.