## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
Git, yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol sistemidir. Git sayesinde yapacağınız projelerin adım adım versiyonlarının kopyalarını alarak daha sonra ihtiyaç duyduğunuzda aldığınız kopyalara yani versiyonlara kolayca dönebiliyorsunuz.
2. Git ile GitHub arasında ne fark var?
Git bir versiyon kontrol sistemidir. GitHub ise bu versiyon kontrol sistemi ile kullandığımız projeleri depolayabildiğimiz bir portal diyebiliriz.
3. Neden bir branch oluşturuyoruz? 
Projeleri değiştirirken ya da düzenlerken eski halini korumak ve istediğim gibi işlem yapmak için oluşturuyoruz.
4. Pull Request'in amacı nedir?
Branch'dan sorumlu kişiden kodunuzu eklemesini istemektir.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
git checkout main
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu komutlar ne yapar açıklayınız.
git fetch, “yerel depomu uzaktaki deponun içeriğine güncelle” anlamına gelir. 
git pull “uzaktaki deponun değişikliklerini yerel depoya getir” der.
Git'de merge işlemi başka bir branch'deki değişiklikleri üzerinde çalıştığınız kendi branch'inize entegre etme işlemidir.

7. Merge conflict nedir?
İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır.
8. Merge conflict'i nasıl çözeriz?
Çakışma yaşayan kişi gerekirse ekipteki diğer kişi ile beraber oturup çakışmayı çözdükten sonra merge işlemine devam etmelidir.

