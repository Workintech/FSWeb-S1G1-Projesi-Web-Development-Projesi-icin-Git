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
1. Git local sisteminizde bulunan bir sürüm kontrol sistemidir. Git, kaynak kod geçmişinizi yönetmenizi ve takip etmenizi sağlayan ve lokal sisteminizde bulunan bir sürüm kontrol sistemidir.
2. Git yerel sistemimizde bulunurken Github ise bulut tabanlı bir Git barındırma hizmetidir.
3. Ana branchteki(master) geliştirme yapısını etkilemeden projeyi diğer oluşturduğumuz branchler üzerinden yönetebilmemiz için veya Ana branchten kendi kurduğumuz yapısının etkilenmemesini sağlamak amacıyla Branchler kullanılır.
4. Fork edilen proje üzerinde değişiklikler yaptıktan sonra gerçek repository’e gönderilerek o projenin sahibi olan geliştiricinin değerlendirmesine sunmaktır. Eğer PR kabul edilirse ana repository üzerinde, fork ettiğiniz proje üzerinde değişiklikler işlenir.
5. git chechout [AYKUT-İNCE]
6. Git fetch komutu, kullanıcının uzak depodan yerel depoya taahhütleri, referansları ve dosyaları indirmesine yardımcı olur . Başka bir deyişle, bu komutu çalıştırmak, uzak depodaki tüm güncellemeleri görmenize yardımcı olacaktır. Değişiklikleri korumak istemezseniz ne olur diye düşünüyor olabilirsiniz. Peki, bu komut çalışma havuzunuza hiç zarar vermez.
Git merge, uzak havuzdaki değişiklikleri kabul etmeye hazır olduğunda, bu değişiklikleri yerel havuzda birleştirebilir. Adından da anlaşılacağı gibi, bu değişiklikleri "birleştirmeyi" onaylıyorsunuz .
Git pull, upstream’deki dosyaları çeker ve local’deki kodla direk birleştirir. İki kodun birleşimi şeklinde düşünülebilir:
git pull = git fetch + git merge
7. İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır.
8. Bu durumda çakışma yaşayan kişi gerekirse ekipteki diğer kişi ile beraber oturup çakışmayı çözdükten sonra merge işlemine devam etmelidir