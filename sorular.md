# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Açık kaynak dağıtılmış version kontrol sistemidir

2. Git ile GitHub arasında ne fark var?
Github yazdığımız kodları uzak sunucuda depolayabildiğimiz bir platform. Git ise belirli komutlarla kodumuzun neyin nasıl olacağını gösterdiğimiz kontrol sistemidir.

3. Neden bir branch oluşturuyoruz?

main branch imiz sürekli çalışır halde dursun herhangi bir hata olursa main de değil açılan branch da olsun diye.

4. Pull Request'in amacı nedir?

Forklanan projenin sahibine değiişiklik yapıldığını bunu kontrol edip kendi projesine merge etmesi için gönderilen istek.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

git checkout main.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

git fetch uzak sunucudaki kodları locale getirir fakat localdekiyle birleştirmez böylece çakışma olmaz. git merge branch birleştirmek için kullanılır . git pull dosyaları çeker ve localdeki kodla direk birleştirir. İki kodun birleşimi şeklinde düşünülebilir.

7. Merge conflict nedir?

iki kişi koddaki aynı yeri değiştirip merge etmeye çalıştığında çakışma meydana gelir buna da merge conflict denir.

8. Merge conflict'i nasıl çözeriz?

Eğer çakışma tek commit önce olmuşsa git reset Head~1 komutu ile bir commit öncesini silebiliyormuşuz. Eğer localdeki kod hatasız ise onu push luyoruz burda da pull etmeden push edemeyebiliriz orda da git push --force kullanıyoruz.
