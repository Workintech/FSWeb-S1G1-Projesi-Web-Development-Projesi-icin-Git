# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

//Git, açık kaynak dağıtılmış sürüm kontrol sistemdir. Geliştiriciler tarafından gelişrtirilen kodlar gite kaydedilir. Geliştiriciler bu kodlara remote olarak erişebilir.

2. Git ile GitHub arasında ne fark var?

//Github, bulut tabanlı git barındırma hizmeti sunan kâr amaçlı bir       şirkettir. 

3. Neden bir branch oluşturuyoruz?

//Üzerinde çalışılan kaynak kodun bir kopyasını oluşturarak geliştirmelerin orijinal koddan bağımsız olarak ilerlemesini sağlayabilmek için oluşturulur. Böylece kaynak kod korunmuş olur. Farklı branchler olusturulup paralelde farklı alanda çalışılabilinir.

4. Pull Request'in amacı nedir?

//Yerel sürümün güncellenmesi için kullanılır. Diğer geliştiricierin yaptıkları değişiklikler locale alınır. 

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

// git checkout 'isim-soyisim' bu s

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

//git fetch : glabal repo dan cekilen veriler localdaki mevcut verileri degistirmez
git pull: glabal repo dan cekilen veriler localdaki mevcut verileri degistirir. Global repo yaninda branclar arasi da veri cekilabilinir.
git merge : test branchleri ile master branch birlestirmek icin kullanilir  

7. Merge conflict nedir?

//Branchler arasi yazilan kodlarda cakisma olmasi durumudur. 

8. Merge conflict'i nasıl çözeriz?
// İlk  yöntem, Git hub' in conflict editoru kullanilmasi. 2. yöntem ise  sorunun local clone da çözülüp push edilmesidir.