## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
 - Açık kaynak dağıtılmış sürüm kontrol sistemidir.
2. Git ile GitHub arasında ne fark var?
 - Bulut tabanlı git barındırma hizmeti sunan bir şirket.
3. Neden bir branch oluşturuyoruz? 
 - Yapacağımız geliştirmelerin orjinal koddan bağımsız sürdürülebilmesi için.
4. Pull Request'in amacı nedir?
 - Branch üzerinde yaptık yapacağımızı, al kardeş sen de bak beğendiysen kullan demek için.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
 - git checkout -main
6. `git fetch`, `git merge` ve `git pull` arasındaki farkları açıklayınız. Bu konutlar ne yapar açıklayınız.
 - git fetch, “yerel depomu uzaktaki deponun içeriğine güncelle” anlamına gelir.
 - git pull “uzaktaki deponun değişikliklerini yerel depoya getir” der.
 - git merge başka bir branch'deki değişiklikleri üzerinde çalıştığınız kendi branch'inize entegre etme işlemidir.
 --- Kısaca, git pull önce bir git fetch yapar, sonrasında ise git merge uygular.
7. Merge conflict nedir?
 - İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır.
8. Merge conflict'i nasıl çözeriz?
 - Bu durumda çakışma yaşayan kişi gerekirse ekipteki diğer kişi ile beraber oturup çakışmayı çözdükten sonra merge işlemine devam etmelidir.
