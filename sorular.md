# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Git, en basit ifadeyle bir ortak çalışma ve versiyon kontrol sistemidir.
2. Git ile GitHub arasında ne fark var?
Git, projeleri kontrol edebildiğimiz bir sistemken Github, bu projeleri depoladığımız bir portaldır.
3. Neden bir branch oluşturuyoruz?
Üzerinde çalıştığımız projenin aslının bozulmaması için onun bir kopyası olan branch oluşturup değişiklikleri ve denemeleri bunun üzerinde yapabiliriz.
4. Pull Request'in amacı nedir?
Bir branch üzerinde çalıştıktan sonra bu branchtan sorumlu kişiden kodumuzu eklemesi için istediğimiz izindir.
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
Branchler arası geçişte kullandığımız komut "git checkout"tır. Herhangi bir branchten main ya da master branche geçmek için ise "git checkout main" komutunu kullanabiliriz. 
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
Git fetch remote branch i güncellemek için kullanılırken, git pull local bir branchi remote versiyonla senkron etmek, güncellemek için kullanılır. Git merge ise başka bir branch'deki değişiklikleri üzerinde çalıştığımız branch'e entegre etmemizi sağlar. Yani aslında git fetch, git pulldan oluşur ve git merge de git pullun bir uygulamasıdır.
7. Merge conflict nedir?
İki kişinin aynı dosya ya da aynı satır üzerinde çalışırken git'in yapılanları merge edemediği durumda yaşanan çakışmaya denir.
8. Merge conflict'i nasıl çözeriz?
Öncelikle bu çakışmanın nedenini algılayıp daha sonra "git status" komutunu çalıştırarak entegre edilmemiş dosyaları bulabiliriz. Son olarak bulduğumuz dosyaları açıp düzelttikten sonra sorunumuz çözülmüş olacak. 