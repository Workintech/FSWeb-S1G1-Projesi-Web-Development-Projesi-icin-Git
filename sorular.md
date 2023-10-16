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

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

7. Merge conflict nedir?

8. Merge conflict'i nasıl çözeriz?


## Cevaplar

1. Git bir versiyon kontrol aracıdır. Bir projenin tüm versiyonlarında denetleme ve kontrolü sağlar. Bunun yanında Branch gibi proje dalları oluşturma imkanı sunarak projelerin çalışmasındaki olabilecek aksaklıkların önüne geçer.

2. Git versiyon kontrol aracıyken, GitHub git tabanlı projelerin depolanması ve paylaşılmasını sağlayan çevrimiçi platformdur.

3. Branch sayesinde farklı bir çalışma ortamı oluşturabiliriz. Bu sayade -main- proje çalışmaya devam ederken oluşturduğumuz branch ortamında projemizin farklı bir özelliğini geliştirebiliriz. Yeni yazdığımız kodun oluşturacağı bir hatadan da projemizi korumuş oluruz. 

4. Birden fazla geliştiricinin çalıştığı projelerde kod paylaşımını kolaylaştırır. Bu sayede iş takibini, projede olabilecek hatalardan kaçınmayı ve yazılan kodun birçok geliştrici tarafından gelişmesi konusunda faydalar sağlar. 

5. `git checkout main` komutu ile branch main olarak değiştirilir.

6. 
    `git fetch` komutu ile repodan güncellemeler çekilir fakat kod ile birleştirilmez.
    `git merge` branchleri birleştirmek için kullanılır
    `git pull` komutu ise repodaki güncelleştirmeleri çekip kodumuzla birleştirmemizi sağlar. Hızlıca kodu güncelleştir.

7. Merge yaparken, aynı dosyada iki kod satırı birbirinin çalışmasını engelleyecek şekilde aynı satırda çakışmasıdır. Bu hatada git hangi kodu tutacağını bilemez. 

8. Çakışma olan satırlar görüldükten sonra, bir metin düzenleyicisinde hangi satırın korunacağı seçilerek kaydedilir. Düzeltmeler yapıldıktan sonra, `git add` ve `git commit` komutlarıyla kodu güncelleriz. Daha sonra merge ederek birleştirme tamamlanabilir.
