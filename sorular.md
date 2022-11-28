## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
-Git, yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol sistemidir. Git sayesinde yapacağınız projelerin adım adım versiyonlarının kopyalarını alarak daha sonra ihtiyaç duyduğunuzda aldığınız kopyalara yani versiyonlara kolayca dönebiliyorsunuz.
2. Git ile GitHub arasında ne fark var?
-Git, kaynak kodu geçmişinizi yönetmenizi ve takip etmenizi sağlayan bir versiyon kontrol sistemidir. GitHub, Git repositorilerini yönetmenize izin veren bulut tabanlı bir barındırma hizmetidir.
3. Neden bir branch oluşturuyoruz? 
-Branch oluşturmak kullanıcıya çalıştığı projenin farklı versiyonlarına erişmesini sağlar. Kullanıcı, projesine bir yenilik eklemek istediğinde, yaptığı değişiklik projenin çalışmasını olumsuz etkileyebilir. Bu gibi durumlarda projemizin o anki halini bozmamak için branch kullanabiliriz.
4. Pull Request'in amacı nedir?
Pull Request, Git'te bir katılımcının bir Git repository sorumlusundan bir projede birleştirmek istedikleri kodu gözden geçirmesini istediği bir olaydır.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
git checkout 'main_branch'
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
-git merge: Birden çok commit dizisini tek bir birleşik geçmişe birleştirir. En sık kullanım durumlarında, iki branchi birleştirmek için git merge kullanılır.
-git fetch: Remote branch'deki değişiklikleri indirmek için git fetch komutunu kullanılır.
-git pull: Repositoryden içerik almak ve yerel repo ile birleştirmek için bu komut kullanılır.

7. Merge conflict nedir?
-Merge conflict, çakışan commitlere sahip branchleri birleştirdiğinizde meydana gelir ve Git'in son birleştirmede hangi değişiklikleri dahil edeceğine karar vermek için yardımınıza ihtiyacı vardır.
8. Merge conflict'i nasıl çözeriz?
Merge conflicti çözmenin birkaç farklı yolu vardır:
-Merge conflict, insanların Git deponuzdaki farklı branchlerde aynı dosyanın aynı satırında farklı değişiklikler yapması gibi, birbiriyle yarışan satır değişikliklerinden kaynaklanıyorsa, conflict editor kullanarak GitHub'da bu sorunu çözebilirsiniz.
-Diğer tüm merge conlict türleri için, merge conflict repositorynin  yerel bir klonunda çözmeli ve değişikliği GitHub'daki şubenize iletmelisiniz. Değişikliği pushlamak için komut satırını veya GitHub Desktop gibi bir aracı kullanabilirsiniz.

