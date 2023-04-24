# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Versiyon kontrolüdür.
2. Git ile GitHub arasında ne fark var?
GİT açık kaynaklı bir sürüm kontrol sistemidir.GİTHUB ise sürüm kontrol sistemi olarak GİT kullanan projeler için web tabanlı depolama sistemidir.
3. Neden bir branch oluşturuyoruz?
Projemizde değişiklik yapmak istediğimizde bu değişikliğin projemize zarar vermemesi için branch oluşturup kontrollü bir geliştirme yapabiliriz.

4. Pull Request'in amacı nedir?
Kısaca branchden sorumlu kişiye kodumuzu eklemesini istemektir.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

git checkout main kodunu kullanabiliriz.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch komutu kodu projemize çekiyor ama branch'imize entegre etmiyor,git pull komutu ise branch'imize direkt olarak uyguluyor.
git merge komutu oluşturulan featurları branchimize birleştirmeyyi sağlar.

7. Merge conflict nedir?
iki farklı oluşturulan branchdeki değişikliklerin çakışması durumu.

8. Merge conflict'i nasıl çözeriz?
Kullanıcılar aralarında konuşarak durumu çözmeli ve öyle merge işlemi yapmalıdırlar.
