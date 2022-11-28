## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
2. Git ile GitHub arasında ne fark var?
3. Neden bir branch oluşturuyoruz? 
4. Pull Request'in amacı nedir?
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
7. Merge conflict nedir?
8. Merge conflict'i nasıl çözeriz?

Cevaplar
1.yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol sistemidir.
2.Git; bir projenin bir çok kişi ile aynı anda yapılabilmesini sağlar.Github ise projelerimizin saklandığı (depolandığı) uzak sunucudur.
3.Ana akışı etkilemeden üzerinde çalıştığımız istenilen durumda merge edebileceğimiz bir kopya diyebiliriz.
4.proje üzerinde değişiklik yaptım, sen de bu değişiklikleri onaylarak projene merge et demek anlamına gelir.
5.git checkout main yazarak main'e geçiş yapılabilir.
6.git fetch, “yerel depomu uzaktaki deponun içeriğine güncelle” anlamına gelir.
git pull “uzaktaki deponun değişikliklerini yerel depoya getir” der.
git merge ise ana akışa bir dal ekleme yada iki dalı birleştirme anlamına gelir.
7.İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır. 
8.Bu durumda çakışma yaşayan kişi gerekirse ekipteki diğer kişi ile beraber oturup çakışmayı çözdükten sonra merge işlemine devam etmelidir.
