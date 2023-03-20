# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Git bir sürüm kontrol sistemidir. Bu yöntem geliştiricilerin proje dosyalarını yönetmesine yardımcı olmaktadır. Git mantığının en temel anlamı ise üzerinde çalışılan projelerin tüm geçmiş yedeklerini tutabilmeleridir.

2. Git ile GitHub arasında ne fark var?
Git; bir projenin bir çok kişi ile aynı anda yapılabilmesini sağlar.Github ise projelerimizin saklandığı (depolandığı) uzak sunucudur.

3. Neden bir branch oluşturuyoruz?
Üzerinde çalışılan kaynak kodun bir kopyasını oluşturarak geliştirmelerin orijinal koddan bağımsız olarak ilerlemesini sağlayabilmemiz için.

4. Pull Request'in amacı nedir?
Temelde branch'dan sorumlu kişiden kodunuzu eklemesini istemektir. Ayrıca o kişinin kodda tam olarak neyi değiştirdiğinizi görmesine de yardımcı olur.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout main komutunu kullanarak mevcut branch'den main branchine geçiş sağlanmış olur.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
 'git fetch'i herhangi bir zamanda refs/remotes/<remote>/ altındaki remote branch’inizi update etmek için kullanabilirsiniz. Bu operasyon refs/heads altındaki lokal branchleri değiştirmez. Aynı zamanda üzerinde çalıştığınız kopyayı değiştirmeden işlem yapma açısından da güvenlidir.

 git merge komutu, git branch tarafından oluşturulan bağımsız geliştirme satırlarını almanızı ve bunları tek bir branch'ta birleştirmenizi sağlar.

git pull, bir deponun yerel sürümünü remote olarak güncellemek için kullanılan bir git komutudur. 

Kısaca cevap vermek gerekirse, git pull önce bir git fetch yapar, sonrasında ise git merge uygular.

7. Merge conflict nedir?
Bir branch'te değişiklik yaparken, takım arkadaşınız farklı bir branch'te aynı dosyalarda değişiklik yapabiliyor. İşte bu durumlarda çakışma (conflicts) ortaya çıkıyor.


8. Merge conflict'i nasıl çözeriz?
Çakışma yaşayan kişi gerekirse ekipteki diğer kişi ile beraber oturup çakışmayı çözdükten sonra merge işlemine devam etmelidir ya da

Manuel bir birleştirme yapmamız gerekiyor. Kodları inceleyip, işaretleri (<, =, >) silip dosyamızı istediğimiz hale getirdikten sonra çakışma (conflicts) çözülmüş olacak. Tabii sonrasında 

git add lib.php 
git commit -m “cakisma halledildi”
komutlarını kullanmayı unutmuyoruz.
