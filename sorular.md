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

1. Git, dağınık çalışan bir versiyon kontrol sistemidir. Merkezi versiyon kontrol sistemlerinden farkı aynı dosya üzerinde birden fazla kişinin çalışabilmesi ve daha sonra bu dosyaların birleştirilebilmesidir.
2. Git, bir versiyon kontrol sistemi iken; GitHub, Git ile üzerinde çalıştığımız projeleri yükleyebildiğimiz bir platformdur. 
3. Üzerinde çalışılan projenin farklı versiyonlarına ulaşabilmek için ya da kendi versiyonumuz üzerinde çalışabilmek için branch oluştururuz. 
4. Branch'in ana sorumlusundan yaptığımız değişikleri ekleme talebine Pull Request denir.
5. git checkout
6. git fetch:  uzaktaki değişiklikleri sisteme indirme
git pull: git fetch ve git merge'ün birleştirilmiş hali
git merge: birleştirme
7. Merge conflict: iki kişi bir dosya üzerinde çalışırken aynı satırı değiştirirse ve git bunu merge edemezse oluşan çakışmaya denir.
8. Değişen yerlere tek tek bakarak ve kontrol ederek ve doğru olanı seçerek ilerlemek.