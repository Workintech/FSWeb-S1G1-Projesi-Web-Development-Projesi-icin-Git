## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
   Git, yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol sistemidir.
2. Git ile GitHub arasında ne fark var?
   Git bir versiyon kontrol sistemidir. Github ise versiyon kontrol sisteminde kullandığımız projeleri depolayabildiğimiz bir portaldır.
3. Neden bir branch oluşturuyoruz?
   Branch oluşturmak kullanıcıya çalıştığı projenin farklı versiyonlarına erişmesini sağlar. Kullanıcı, projesine bir yenilik eklemek istediğinde, yaptığı değişiklik projenin çalışmasını olumsuz etkileyebilir. Bu gibi durumlarda projemizin o anki halini bozmamak için branch kullanabiliriz.
4. Pull Request'in amacı nedir?
   Branch'dan sorumlu kişiden kodunuzu eklemesini istemektir.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
   git checkout
6. git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
   git fetch: Yerel depomu uzaktaki deponun içeriğine güncelle anlamına gelir.
   git merge: Başka bir branch'deki değişiklikleri üzerinde çalıştığınız kendi branch'inize entegre etme işlemidir.
   git pull: Uzak depoda bulunan tüm değişiklikleri yerel çalışma dizinine birleştirmek için kullanılır.
7. Merge conflict nedir?
   İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse çakışma olur.
8. Merge conflict'i nasıl çözeriz?
   git reset komutunu kullanarak yaptığımız işlemleri geri alabiliriz.