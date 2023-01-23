## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
--Versiyon kontrol sistemi. Projelerin versiyonlarını kopyalayıp ihtiyaç duyulduğunda dönebiliriz.
2. Git ile GitHub arasında ne fark var?
--Git bir projenin bir çok kişi ile aynı anda yapılabilmesini sağlar.Github ise projelerimizin saklandığı (depolandığı) uzak sunucudur
3. Neden bir branch oluşturuyoruz?
--main branch dışında lokalde çalışabiliriz ve birden çok kişi farklı branchlerde aynı projede çalışabilir.
4. Pull Request'in amacı nedir?
--Kodda yapılan değişiklikleri main ile birleştirmeden önce karşılaştırmak amaçlı yapılır.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
--git checkout 'branch adı'
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
-- git fetch remote branch'deki değişiklikleri indirmek için kullanılır
-- git merge remote branch'deki değişiklikleri local branch'inize entegre etmek için kullanılır
-- git pull değişiklikleri inceledikten sonra bunları local branche entegre etmek için kullanılır
7. Merge conflict nedir?
-- iki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict çıkar.
8. Merge conflict'i nasıl çözeriz?
-- doğru kod parçaları seçilerek giderilir
