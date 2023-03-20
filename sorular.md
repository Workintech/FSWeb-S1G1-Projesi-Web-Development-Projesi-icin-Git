# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir? 

2. Git ile GitHub arasında ne fark var?

3. Neden bir branch oluşturuyoruz?

4. Pull Request'in amacı nedir?

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

6. `git fetch`, `git merge` ve `git pull` arasındaki farklılıkarı açıklayınız. Bu konutlar ne yapar açıklayınız.

7. Merge conflict nedir?

8. Merge conflict'i nasıl çözeriz?

## Cevaplar

1. Git, açık kaynak kodlu bir sürüm/versiyon kontrol sistemidir. Yazdığımız projeleri, internet üzerinde tutmamızı ve yönetmemizi sağlayan bir sistemdir.

2. Git yardımcı bir yazılımken; GitHub ise Git yazılımı kullanılan projelerin yüklendiği bir depolama servisidir.

3. Projeye eklenecek yeni bir özellik, test edilmeden ya da kontrolsüz eklendiğinde, uygulamanın/projenin kararsız çalışmasına veya çalışmamasına sebep olabilir. Bu tür durumların önüne geçebilmek adına projenin ana sürümünden ayrılan bir alt-kopyası oluşturulur. Yeni eklenen özellik test edilip onaylandığında, projenin kendisine dahil edilir ve çalışmaya devam edilebilir.

4. Branch üzerinde yapılan değişikliklerin projeye dahil(merge) edilmesi amacıyla, proje sahibine/yetkilisine iletilen taleptir. Bu talepler GitHub üzerinde incelenip, onaylandığı takdirde projenin kendisine dahil edilebilir.

5. git checkout master

6. `git fecth` = Uzak sunucudan projeye ait dosyalar indirilir, ancak yerel dizinde herhangi bir dosya değişikliği gerçekleştirilmez.  
   `git merge` = Halihazırda kullanımda olan branch, master ile birleştirilir / master'a dahil edilir.
   `git pull`  = Uzak sunucudan projeye ait dosyalar indirilir, yerel sunucudaki dosyalar ile değiştirilir/güncellenir. Fetch ile farkından ziyade, bir nevi fetch komutu otomatik olarak kullanılırken, sonrasında kullanıcıdan izin alınmadan, yerel dizindeki bütün dosyalar uzak sunucuda değişiklik içeren bütün dosyalarla değiştirir.

7. Birden fazla kullanıcının aynı dosya üzerinde ya da aynı kod bloğu üzerinde yaptığı değişiklikler bir karmaşa/çakışma (conflict) ortaya çıkartır. Merge esnasında ortaya çıkan bu çakışmaya "Merge Conflict" denir.

8. İlgili branchlerde, çakışmanın olduğu kısımlarda aynı kodlar kullanılarak bu sorun çözülebilir. Branchler birden fazla kullanıcının kontrolündeyse, ilgili kullanıcılar birbirleriyle iletişime geçip mutabakatı sağlamalıdır.