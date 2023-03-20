# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Git, açık kaynak versiyon kontrol sistemidir. 
2. Git ile GitHub arasında ne fark var?
Github dünyada varolan en büyük kaynak kod barındırıcısıdır. Cloud hizmeti sunmaktadır git ise sürüm kontrol sistemi olarak iş takibi vs. yapmamızı kolaylaştırmaya yarayan sistemdir.
3. Neden bir branch oluşturuyoruz?
Branchlar origin branchtan ayrılarak güncel kodlar ile kendi kodlarımızı yazabileceğimiz test edebileceğimiz bir alan açmaktadır, bu sayede main branch risk edilmemiştir. Ayrıca bir çok personel aynı alanda farklı şekilde çalışmalarını sürdürebilirler.
4. Pull Request'in amacı nedir?
Pull request değişik yaptığımız kodların origin brancha eklenmesinin talebidir. talep etmiş oluruz
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout main
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch : remote branch deki değişiklikleri locale çekmemize sağlar. 
git merge : ana branchimizden ayrı oluşturuduğumuz branchimizi ana branche bağlanmasını sağlar 
git pull : o an kullanmakta olduğumuz branchi remote branch ile entergre eder günceller.
7. Merge conflict nedir?
Branchlerin ana branche bağlanılırken ki çakışma durumudur ilk bağlanmaya çalışan için herhangi bir hata almaz sonradan bağlanılmaya çalışan ise hata ile karşılaşır çünkü bağlamak istediği brachte varolan kod veya aynı kod satırı üzerine yazılmış bilgiler mevcuttur bu sebeple git hangisini alacağını bilemez ve bu durumda developera sorar. 
8. Merge conflict'i nasıl çözeriz?
her ikisinide kabul edebiliriz yahut sonradan bağlanılmaya çalışan branchtaki kodu düzenleyerek çakışmayı engelleyebiliriz.
