## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz.

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

**1. Git nedir?**
Temel olarak, bir versiyon kontrol sistemidir. Projelerdeki her şeyi hız ve verimlilikle işlemek için tasarlanmış dağıtık versiyon kontrol sistemidir.
Yapılan değişiklikleri kaydetmemize ve eski sürümlerine ulaşmamızı sağlar.

**2. Git ile GitHub arasında ne fark var?**
Git, kaynak kodumuzun geçmişini yönetmemizi ve takip etmemizi sağlayan bir versiyon kontrol sistemi iken; Github, git repo'larını yönetmemize izin veren bulut tabanlı bir servistir. GitHub yerine GitLab veya Bitbucket gibi farklı servisleri de kullanabiliriz.

**3. Neden bir branch oluşturuyoruz?**
* Projemizi dallara ayırmamızı sağlar. Projeye farklı bir özellik eklemek istediğimizde, projemizin mevcut halini bozmak istemiyor ve halihazırda projenin akışı devam ediyorsa bu noktada branch'lerden yararlanarak proje üzerinde çalışabiliriz.
* Geliştirdiğimiz projede farklı versiyonlar bulunuyorsa bunları ayrı branch'lar halinde projemize devam edebiliriz.

**4. Pull Request'in amacı nedir?**
Mevcut bir projede bir özellik eklemek veya hataları çözmek amacıyla Pull Request(PR) oluştururuz.

**5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.**
`git checkout main`

**6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.**
`git fetch`, remote versiyondaki kodu local'e indirmek için kullanılır.
`git merge`, başka bir branch'deki değişiklikleri diğer bir branch'a entegre etme işlemidir.
`git pull`, local'deki kodu remote versiyonuna güncelleme işlemidir.
**7. Merge conflict nedir?**
Aynı projede birden fazla kişi çalıştığında ve kodlar merge edildiğinde kodlar birbiriyle örtüşmüyorsa merge conflict olur.
**8. Merge conflict'i nasıl çözeriz?**
Eşleşmeyen kodların olduğu satırlar incelenmeli çakışmanın sebebi aranmalıdır.