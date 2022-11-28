## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
Git bir versiyon kontrol sistemidir. Projelerimizin güvenli şekilde kayda alınmasını sağlar. Geçmiş güncellerimize kolayca ulaşabiliriz, projeler üzerinde yaptığımız değişiklikleri düzenli biçimde görebiliriz. Başkalarının yazdığı projelere ulaşabilir ve karşı tarafın da gönüllü olması durumunda projelerine ekleme yapabiliriz. 
2. Git ile GitHub arasında ne fark var?
GitHub Git uygulaması kullanılarak oluşturulmuş, projelerinizi internet üzerinde depolayacağınız bir sistemdir. 
3. Neden bir branch oluşturuyoruz? 
Main projede değişiklik yapmadan kodu geliştirmek için branch kullanırız. İsteğe göre oluşturulan branch main projeye merge edilebilir. 
4. Pull Request'in amacı nedir?
Pull request forklamış olduğumuz projedeki değişikliği ana projeye sunmak için oluşturulan bir taleptir.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
git checkout master
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch: Kodu remote depoadan local depoya çeker ancak birleştirmez.
git merge: Branchleri birleştirmek için kullanılır.
git pull: Remote depoadan alan verileri çeker ve local ile birleştirir. fetch ve merge komutlarının birleşimi gibidir.
7. Merge conflict nedir?
Aynı değişkende yapılan farklı işlemlerin çakışma durumu.
8. Merge conflict'i nasıl çözeriz?
Pull request butonunda resolve conflict'e tıklayarak çakışmaları tespit edebilir ve çözebilirsiniz.
