## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
    Git yazılım sürecinde kullanılan versiyon kontrol sistemidir.
2. Git ile GitHub arasında ne fark var?
    Git bir versiyon kontrol sistemidir. GitHub ise bu versiyon kontrol sistemi ile kullandığımız projeleri depolayabildiğimiz bir portaldır.
3. Neden bir branch oluşturuyoruz? 
    Üzerinde çalışılan kaynak kodun bir kopyasını oluşturarak geliştirmelerin orijinal koddan bağımsız olarak ilerlemesini sağlamak için.
4. Pull Request'in amacı nedir?
    Pull requestin amacı, branch'dan sorunlu kişiden kodunuzu eklemesini istemektir.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
    git checkout 
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
    git fetch uzak repodan var olan bütün bilgileri getirir ve kaydeder.
    git branch tarafından oluşturulan bağımsız geliştirme satırlarını almanızı ve bunları tek bir branch'ta birleştirmenizi sağlar.
    git pull geçerli yerel çalışma branch’ını günceller ve diğer tüm branch’lar için remote-tracking branch’larını günceller.
7. Merge conflict nedir?
    İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır.
8. Merge conflict'i nasıl çözeriz?
    git status komutunu çalıştırdığınızda Git size branch'inizde entegre edilmemiş dosyalar olduğunu söyleyecektir.