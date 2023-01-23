## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?

Yazılım geliştirme sürçlerinde adım adım versiyonların görülebildiği bir versiyon kontrol sistemidir. 

2. Git ile GitHub arasında ne fark var?

Git'te versiyon kontrolünü sağlamak mümkünken GitHub ise daha önce yapılan değişikliklerin ve versiyonların depolandığı bir portal görevi görüyor. 

3. Neden bir branch oluşturuyoruz? 

Branchler çalışmanın farklı versiyonlarına erişilmesini ve çalışmaya eklenecek ve belki de projeyi olumsuz etkileyebilecek yeniliklerin sorunsuzca eklenmesini sağlar. 

4. Pull Request'in amacı nedir?

Full request büyük projelerde değişiklikleri marge ederken sorun çıkmaması için kullanılır. Özünde kendi branchlerimizi main e eklememizi sağlar. 

5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.

Git checkout komutu

6. `git fetch`, `git merge` ve `git pull` arasındaki farkları açıklayınız. Bu konutlar ne yapar açıklayınız.

'git fetch' çalışılan projede çalışma yerimize repositoryde var olan bütün verileri getirir. 'git pull' çalışma yerin ve repository arasındaki farkları belirler ve farklı olan dosyaları getirir. 'Git merge' ise başa branş üzerinde yaptığımız değişikliklerin branchimize kaydetme işlevi görür. 

7. Merge conflict nedir?

Değişiklikler otomatik olarak erge edilirken sorun çıkması. Bazı değişiklikler otomatik olarak olmaz ve müdahale gerektirir.

8. Merge conflict'i nasıl çözeriz?

İlk olarak sorunun neyden kaynaklandığı anlaşılmalı. Aynı dosya üzerinde yapılan değişikliklerde çatışma yaşanabilir bu yüzden git status komutuyla çakışmanın hangi dosyada olduğu bulunur ve düzeltilir. 


