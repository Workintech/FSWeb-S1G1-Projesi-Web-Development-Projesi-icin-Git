## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
-Açık Kaynak Dağıtılmış Sürüm Kontrol Sistemi(Open Source Distributed Version Control System)'dir.
2. Git ile GitHub arasında ne fark var?
git:Sürüm kontrol sistemi
github:projelerimizin saklandığı (depolandığı) uzak sunucudur
3. Neden bir branch oluşturuyoruz? 
-çalıştığımız projenin farklı versiyonlarına erişimini sağlar.
4. Pull Request'in amacı nedir?
-Fork ettiğimiz projenin üzerinde çalışarak proje üzerinde yaptığımız değişiklikleri, projenin sahibine pull request şeklinde gönderebiliriz. Pull request olarak göndermenin anlamı; proje üzerinde değişiklik yaptım, sen de bu değişiklikleri onaylarak projene merge et demek anlamına gelir.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
-git checkout komutu
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
-git fetch, yerel depomu uzaktaki deponun içeriğine güncellemektir.
-git merge, başka bir branch'deki değişiklikleri üzerinde çalıştığınız kendi branch'inize entegre etme işlemidir.
-git pull, uzak sunucudaki değişiklikleri çalışma dizininize getirir ve birleştirir.
7. Merge conflict nedir?
-İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse oluşan durum merge conglict'tir.
8. Merge conflict'i nasıl çözeriz?
- Bu durumda çakışma yaşayan kişi gerekirse ekipteki diğer kişi ile beraber oturup çakışmayı çözdükten sonra merge işlemine devam etmelidir.
