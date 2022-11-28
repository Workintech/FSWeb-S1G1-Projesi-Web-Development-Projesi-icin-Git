## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
Bir versiyon kontrol sistemidir.
2. Git ile GitHub arasında ne fark var?
Git, bir versiyon takip yazılımıdır.Github ise Git repository'lerinin cloud üzerinde saklandığı online bir servistir.
3. Neden bir branch oluşturuyoruz? 
Kullanıcı, projesine bir yenilik eklemek istediğinde, yaptığı değişiklik projenin çalışmasını olumsuz etkileyebilir. Bu gibi durumlarda projemizin o anki halini bozmamak için branch oluştururuz.
4. Pull Request'in amacı nedir?
Branch'dan sorumlu kişiden kodunuzu eklemesini istemektir. Ayrıca o kişinin kodda tam olarak neyi değiştirdiğinizi görmesine de yardımcı olur.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
git checkout main
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
`git fetch` Uzak bir depoda yapılan değişiklikleri çakışma yaratmadan geri yükler. `git merge` başka bir branch'deki değişiklikleri üzerinde çalıştığınız kendi branch'inize entegre eder. `git pull` Uzak depoda yapılan değişiklikleri kaydeder ve bunları birleştirir, bu da çakışmalar yaratır.
7. Merge conflict nedir?
İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır.
8. Merge conflict'i nasıl çözeriz?
Çakışma gerçekleşmeden önce bunu önlemenin en iyi yolu, üzerinde çalıştığımız özellik dalını sıklıkla master üzerinden rebase komutuyla güncelleştirmektir.
