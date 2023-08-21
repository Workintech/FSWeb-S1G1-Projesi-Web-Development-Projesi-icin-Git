# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
c1. Git, açık kaynak dağıtılmış versiyon kontrol sistemidir. Bir proje geliştirilirken geliştiricinin seçeceği aşamalar kaydedilir. Bu sayede her geliştirici projenin farklı kısımlarında 
bağımsız şekilde çalışabilir.

2. Git ile GitHub arasında ne fark var?
c2. Git, versiyon kontrol sistemidir.  GitHub ise Git teknolojisini kullanarak geliştiricilere çevirimiçi hizmet sunan bulut tabanlı bir şirkettir.

3. Neden bir branch oluşturuyoruz?
c3. Proje için geliştirilen kodun etkisini önceden bilemeyiz. Bu kodları projeye dahil etmeden önce o kodlar ayrı bir projede değerlendirilmeli. Bunun için belirlenen bir sürümün bir 
kopyası oluşturulur ve o versiyon üzerinde denemeler yapılır. Bu kopya oluşturma işlemine branch denir.

4. Pull Request'in amacı nedir?
c4. Projeye katkıda bulunmak isteyen geliştirici, geliştirdiği yeni versiyonu proje sahibine incelemesi amacıyla gönderir. 

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
c5. git checkout master

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
c6. git fetch, uzaktaki deponun içeriğinde olan güncellemeleri alıp indirir. Ancak yerel dosyalarda değişiklik yapmaz.
git pull, uzaktaki depoda olan değişiklikleri alır ve bu değişiklikleri yerel çalışmaya entegre eder.
git merge, iki branch'i birleştirmeye yarar. Ve yeni branch oluşturur.

7. Merge conflict nedir?
c7.İki farklı branchin aynı dosyanın aynı bölümünü değiştirmeye çalışmasından dolayı ortaya çıkan çakışmadır. Git, böyle bir durumda hangi değişikliğin uygulanacağına kadar veremez ve 
kullanıcının müdahalesini bekler.

8. Merge conflict'i nasıl çözeriz?
c8. Öncelikle sorunun nerede olduğu tespit edilir. Ardından sorunlu olduğu git tarafından gösterilen kodlar incelenir ve çakışan kısımlarda hangi değşikliğin korunacağına geliştiriciler 
karar verir. Ardından dosya kaydedilir. Bu işlemden sonra "add" ve "commit" komutlarıyla dosyaların hazır olduğu belirtilir. Son olarak da "merge" ile birleştirme tamamlanmış olur.
