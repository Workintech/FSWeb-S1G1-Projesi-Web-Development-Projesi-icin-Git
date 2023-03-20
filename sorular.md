# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Projelerin ortak bir alana(Github) yüklenmesi, versiyonlarının kontrol altında tutulduğu, değişikliklerin takibini ve ekip çalışması kolaylaştıran bir sistemdir.

2. Git ile GitHub arasında ne fark var?
Github projelerin depolandığı, repositorylerin yüklendiği, karşılaştırıldığı bir ortamdır. Git bu işlemlerin kendisidir.

3. Neden bir branch oluşturuyoruz?
Mevcut versiyon üzerinde değişiklik yapmak yerine branchj üzerinde çalışarak oluşabilecek sorunların önüne geçilebilir. ayrıca aynı anda birden fazla branch üzerinden aynı proje farklı alanlardan geliştirilebilir.

4. Pull Request'in amacı nedir?
Amacı proje sahibi veya sorumlusuna yapılan değişiklikerin iletilmesi ve gerekli kontrollerin yapılarak projeye merge edilmeye uygun olduğunu belirtmektir.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout <branch-name> kullanılır.  git checkout main 

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git merge branchte yapılan değişiklikleri main versiyona işler. git pull remote da bulunan versiyonun lokale çağrılmasını sağlar. git fetch remote da bulunan verciyonun localde yeni bir branch olarak oluşturulmasını sağlar.

7. Merge conflict nedir?
farklı commitlerde yapılan değişikliklerin çakışması sebebiyle git merge işlemini gerçekleştiremez.

8. Merge conflict'i nasıl çözeriz?
çakışmanın kaynağını tespit ederken bu kısım düzeltilmeli ve merge işlemi tekrar yapılmalıdır.
