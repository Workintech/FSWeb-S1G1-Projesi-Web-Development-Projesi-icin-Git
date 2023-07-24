# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

Git, yazdığımız programa ait sürümleri kontrol altında tutmamızı sağlayan, açık kaynak kodlu bir sürüm yönetim sistemidir.



2. Git ile GitHub arasında ne fark var?
Git açık kaynak kodlu bir sürüm yönetim sistemiyken, github ise bu altyapıyı kullanan bir sunucu sistemidir. bünyesinde bulundurduğu sunuculara yazılımcıların projelerini ve sürümlerini yükleme olanağı sağlar.
github olmasa da, git sistemi ile farklı sunucular oluşturup, bir proje sisteminde ortak çalışabiliriz.




3. Neden bir branch oluşturuyoruz?
çalışan ana projeyi bozmadan proje üzerinde geliştirmeler ve denemeler yapmak için branch oluşturuyoruz.




4. Pull Request'in amacı nedir?
projede uyguladığımız değişikliklerin ana projeye eklenmesini talep etmek amacıyla kullanılır. 



5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
bu komut checkout komutudur.

git checkout main
komutu ile bulunduğumuz branch'ten main branchine geçebiliriz.


6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

fetch komutu repodaki bilgileri bilgisayara indirir fakat çalıştığımız dosyalar yeni indirilen dosyalar ile değiştirilmez.

merge komutu ile farklı branchlerdeki çalışmalar ana program ile birleştirir.

fetch ve merge komutlarının birleşimidir. hem yereldeki dalları, hem uzak bilgisayardaki değişiklikleri birleştirir.



7. Merge conflict nedir?
merge conflict, aynı dosya üzerinde çalışan iki veya daha fazla kişinin yaptığı değişikliklerin çakışma durumudur. sistem böyle bir durumda ilgili dosyaları merge edemez.


8. Merge conflict'i nasıl çözeriz?
bu durumda merge edilemeyen dosyaların listesine bakılmalı, ilgili dosyalar gerekirse elle müdahale edilerek, tek elden merge edilmelidir.