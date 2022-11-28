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

## Cevaplar

1. Versiyon kontrol sistemidir.
2. Git sistemi kullanan bir hizmettir.
3. Core code korunarak yeni geliştirmeler yapmak için uygulanan bir dallandırma işlemidir.
4. Yapılan değişiklerin projeye katkısı bulunması isteniyorsa repo sahibine iletilmesidir.
5. git checkout (bracnh adı). git checkout main ile main branchine geçilir.
6. `git fetch` Yerel repoyu uzak repoda yapılan değişiklikleri alarak günceller.
   `git pull` bir deponun yerel sürümünü remote olarak güncellemek için kullanılan bir git komutudur. Varsayılan olarak, git pull geçerli yerel çalışma branch’ını (o an için kullanılan branch’ı) günceller ve diğer tüm branch’lar için remote-tracking branch’larını (uzaktan takip branch’ları) günceller.
   `git merge` Merge, git'in çatallanmış bir geçmişi tekrar bir araya getirme yoludur. git merge komutu, git branch tarafından oluşturulan bağımsız geliştirme satırlarını almanızı ve bunları tek bir branch'ta birleştirmenizi sağlar.
7. Birden fazla kişinin aynı anda aynı kod satırında değişiklik yaptığında meydana gelen çakışma durumudur.
8. Kod yazarken bolca fetch işlemi yapmak çakışmayı önler. Çakışma olursa eğer `git reset` ile işlem geri alınır ve yeniden pull yapılır.
