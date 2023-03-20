# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Açık kaynaklı, projeleri tam kopya olarak geliştiricilerin lokal bilgisayarlarına dağıtabilen, geliştiriciler tarafından yapılan güncellemeleri kayıt altına alıp eskilerine de ulaşmalarını sağlayan bir versiyon kontrol sistemidir.
2. Git ile GitHub arasında ne fark var?
GitHub projelerin depolandığı bir uzak online servistir. Burada başkalarının repositorylerine ulaşabilir, ya da kendi repositorylerimize erişmelerini ve katkı sağlamalarını sağlayabiliriz. Git ile ise projelerimizin versiyonlarını yapabilir ve internete bağlanmadan kullanabiliriz.
3. Neden bir branch oluşturuyoruz?
Branch yeni dallar oluşturmayı sağlar. Bunun asıl amacı halihazırdaki projemize yeni özellikler eklemek istediğimizde bir yandan da projemize zarar gelmemesini istediğimizde branch oluşturmak yardıma koşuyor. Böylelikle hem yenilik sağlayıp hem de projemizi bozmadan ilerleyebiliyoruz.
4. Pull Request'in amacı nedir?
Fork ettiğimiz bir projenin üzerinde çalışıp, projede yaptığımız değişiklikleri, projenin sahibine pull request olarak gönderebiliriz. Pull request olarak göndermek demek; projede değişikliklerin yapıldıktan sonra, sahibine bu değişiklikleri onayla ve projene merge et, ben de katkı sağlamış olayım demek.
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout main
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch, yerel depoyu uzaktaki deponun içeriğine güncellemek anlamına gelir. Herhangi bir dosya aktarmaz. Daha çok değişikliklerin olup olmadığını bulmak için verileri incelemek gibidir.
git pull, ise tüm değişiklikleri depoya çekmekle birlikte aynı şeyi yapar ve birleştirir.
git merge, tüm değişikliklerden sonra emin olup, güncel branchı master dosyaya birleştirmektir.

7. Merge conflict nedir?
İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır.
8. Merge conflict'i nasıl çözeriz?
Çalışma arkadaşları ile görüşülüp ortak bir yol bulunabilir.