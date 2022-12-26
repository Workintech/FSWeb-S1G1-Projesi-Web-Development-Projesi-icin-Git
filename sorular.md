## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
Yazılım projeleri için versiyon kontrol sistemidir.
2. Git ile GitHub arasında ne fark var?
Git komut sistemi ile çalışırken Github kendisine ait arayüzü ile işlemler yapılabilen sistemdir.
3. Neden bir branch oluşturuyoruz?
Main de değişiklik yapmadan farklı denemeler yapabilmek için 
4. Pull Request'in amacı nedir?
Fork da yapılan değişikliklerin main e işleme alınmasını sağlatmaktır.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
git checkout "branch name" ile geçiş yapılabilir . maine geçmek için git checkout master kullanılır
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu komutlar ne yapar açıklayınız.
git fetch repository de bulunan tüm branchleri kendi cloud umuza çekmeye yarar. git pull git fetch ile aynı işlemi görür ancak git pull yapıldığında en son güncellemeler otomatik olarak işlenir. git fetch de otomatik olarak işlenmez sadece cloudda durur.git merge iki branch i birleştirmeye yarar. git merge kullanmadan önce sırasıyla git fetch ve git pull komutlarının kullanılması önerilir.
7. Merge conflict nedir?
Mevcut branch ile güncelleme yapan branch arasında ortaya çıkan sorunlardır
8. Merge conflict'i nasıl çözeriz?
Öncelikle git fetch ve git pull request lerinin yapılarak önceki günllemelerin alınması ve ardından emrge işleminin yapılması conflict i engeller. buna rağmen hala conflict oluşursa manuel kodlama yapılarak sorunun çözülmesi gerekir.
