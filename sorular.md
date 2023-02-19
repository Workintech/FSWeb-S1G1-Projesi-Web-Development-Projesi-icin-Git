## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz.

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
   Bir versiyon kontrol sistemidir.

2. Git ile GitHub arasında ne fark var?
   Git bilgisayara yüklediğimiz bir yazılım githubsa internetten giriş yaptığımız, projeleri depolayabildiğimiz bir portal.

3. Neden bir branch oluşturuyoruz?
   Bir kod yazarken ya acaba şöyle bir şey denesem de olur diye düşündük ama mevcut kod üzerinden ilerlemek istemiyoruz. o zaman branch oluştururuz.

4. Pull Request'in amacı nedir?
   Ben bu koddaki şu sorunu çözdüm, şuraya şöyle bir şey ekledim, daha iyi oldu, sen de bu kodu kullanmak istersin belki demek için pull request yaparız.

5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
   git checkout brachinadı komutunu yazarız

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
   git fetch kaynaktan en yeni veri bilgilerini geri yüklemek için yerel git’i gösterir, bir dosya aktarmaz,
   git pull tüm değişiklikleri deponuza çekmekle birlikte aynı şeyi yapar.
   git merge ise başka bir branch deki değişiklikleri üzerinde çalıştığınız kendi branch inize entegre etme işlemidir.
   pull request de aslında bunu merge et demektir ama merge de direkt kendimiz yaparız.

7. Merge conflict nedir?
   Aynı dosyada ve aynı satırda değişiklik yapılıyorsa farklı kişiler tarafından, git otomatik olarak merge edemez ve conflict (çakışma) oluşur

8. Merge conflict'i nasıl çözeriz? iki şekilde çakışmaları çözebiliriz
9. çakışma gerçekleşmeden önce çalıştığımız branchi sıklıkla rebase komutuyla güncelleştirmek ve bunu alışkanlık haline getirmek
   2.Çakışma gerçekleştikten sonra: git reset HEAD~1 ile yapılan değişiklikleri geri almak
