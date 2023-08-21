# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
-Git, Açık Kaynak Dağıtılmış Sürüm Kontrol Sistemi(Open Source Distributed Version Control System)'dir.

2. Git ile GitHub arasında ne fark var?
-Git, bir versiyon kontrol sistemi iken GitHub ise bu versiyon kontrol sistemi ile kullanılan projeleri depolayabildiğimiz yerdir.

3. Neden bir branch oluşturuyoruz?
-Çalışılan kod üzerinde değişiklik yapmak istenirken, orijinal kodu değiştirmek istemediğimiz zaman branch oluşturarak kodlarımızı düzenleyebiliriz.

4. Pull Request'in amacı nedir?
-Açık kaynaklı bir projede katkıda bulunmak isteyen bir kullanıcının, yaptığı değişiklikleri proje sahibine onaylatması için izin alması gerekir. Buyüzden de Pull Request yapmalıdır.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
-git chekout main

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
-git fetch: yerel depomuzdakileri uzaktaki depomuzun içeriğine güncelle anlamına gelir.
-git merge: oluşturulan bağımsız geliştirme satırlarını almanızı ve bunları tek bir branch'ta birleştirmenizi sağlar.
-git pull: bir deponun yerel sürümünü remote olarak güncellemek için kullanılan bir git komutudur.
7. Merge conflict nedir?
-Kısaca çakışma olarak adlandırabiliriz. İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse conflict olur.

8. Merge conflict'i nasıl çözeriz?
-Çakışmaların olduğu bölgeleri düzenleriz, 'git add' ile dosyaları ekleyeriz ve 'git push' ile göndeririz.