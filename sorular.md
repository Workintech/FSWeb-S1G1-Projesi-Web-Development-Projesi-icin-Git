# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

    Yazılım geliştirme süreçinde kullanılan versiyon kontrol sistemidir. Git sayesinde projelerimizin versiyonlarının kopyalarını oluşturarak daha sonra ihtiyaç duyduğumuzda kopyalara ulaşabiliyoruz.

2. Git ile GitHub arasında ne fark var?

    Git yazılım geliştirme süreçinde kullanılan versiyon kontrol sistemidir, GitHub ise projelerin depo olarak kullanıldığı bir yerdir.

3. Neden bir branch oluşturuyoruz?

    Oluşturduğumuz projenin üzerinde güncelleme yapmak için ve bu projede birden fazla kişinin çalıştığını düşünürsek ayrı bir branch açarak daha kolay bir şekilde, karışmadan yapılması için kullanıyoruz.

4. Pull Request'in amacı nedir?

    Branch'daki yapılan güncellemeyi ana koda merge etmek için ve bu güncellemerin ne olduğunu görmemize yarar.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

    Branch oluşturulduktan sonra "git checkout 'isim-soyisim'" şeklinde yazarak branchler arasında geçiş yapababiliriz.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

    git fetch - uzak depodaki çalışmayı yerel depoya çeken bir komuttur.
    git pull - uzak depodaki yapılan güncellemeri çeken bir komut ve bu güncellemeri yerel depoda birleştirir.
    git merge - branch'deki yaptığımız değişiklikleri kendi branch'imize aktarmayı sağlar.
    
    "git fetch" ve "git pull" arasındaki farklar git fetch de kodu çektiğimiz zaman herhangi bir çakışma yaşamayız ama git pull da birden çok kişi tarafından alınan güncellemeler çakışma yaratabilir.

7. Merge conflict nedir?

    İki kişinin aynı anda oluşturduğu güncelleme yapılırsa ve bu git tarafından otomatik olarak merge edilmezse yaşanılan çakışmaya conflict denir.

8. Merge conflict'i nasıl çözeriz?

    