# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
   Bir versiyon kontrol sistemidir.
2. Git ile GitHub arasında ne fark var?
   Git ile kullandığımız projeleri depoladığımız cloud tabanlı bir depo sistemidir. Github'da aynı proje üzerinde farklı yazılımcılarla birlikte çalışabiliriz.
3. Neden bir branch oluşturuyoruz?
   Çalışmak istediğimiz projenin farklı versiyonlarına ulaşabilmek, projemiz üzerinde değişiklik yapabilmek, yaptığımız değişiklik işe yaramazsa eski versiyona dönebilmek için branchler oluşturuyoruz. Her bir versiyon için yeni repo oluşturmak yerine farklı branchlerden takip etmek işimizi kolaylaştırıyor.
4. Pull Request'in amacı nedir?
   Forkladığımız bir proje üstünde değişikler yapıp bunu pull request ettiğimizde, proje sahibi yaptığımız değişiklikleri görüp projesine merge edebilir.
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
   Branchten diğerine: git checkout 'gitmek istediğimiz branch adı'
   main'e geri dönmek git checkout main

6. `git fetch`, `git merge` ve `git pull` arasındaki farklılıkarı açıklayınız. Bu komutlar ne yapar açıklayınız.
   git fetch başkalarının uzak depoya yüklediği yani hedef branchteki tüm yeni işlemeleri indirir yerel depoya kaydeder.
   git merge başka branchteki değişiklikleri kendi branchimize entegre etme işlemidir.
   git pull ise proje ana dosyasında yaptığımız değişikliklerin bilgisayarımızdaki versiyona çekilmesini yani güncellemeyi sağlar.
7. Merge conflict nedir?
   Aynı dosya üzerinde çalışan birden fazla kişi aynı satırda değişiklik yapar ve git otomatik merge edemezse çakışma oluşur.
8. Merge conflict'i nasıl çözeriz?
   conflict yaşayan kişiler yaptıkları değişiklikleri kontrol edip birlikte conflicti çözerek merge etmeye devam ederler.
