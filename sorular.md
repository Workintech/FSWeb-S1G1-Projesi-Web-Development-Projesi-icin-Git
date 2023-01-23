## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?

* Git,yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol sistemidir.

2. Git ile GitHub arasında ne fark var?

* Git bir versiyon takip yazılımı iken Github ise Git reposiyory'lerin Cloud üzerinde saklandığı bir online servistir.

3. Neden bir branch oluşturuyoruz? 

* Projenin değiştirilip ya da güncellenirken eski halini korumasını sağlamak amacı ile "branch" oluşturuyoruz.
Ayrıca her bir versiyon için farklı branchler açılabilir ve versiyonlar kolaylıkla takip edilebilir.

4. Pull Request'in amacı nedir?

* Branch'dan sorumlu kişinin kodunuzu ekleme isteğidir.ayrıca sorumlu kişinin kodda tam olarak neyi değiştirdiğini görmeye de yardımcıdır.

5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.

* git checkout -b "AD-SOYAD"

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

* 'git fetch' komutu remote'daki tüm commitleri local'e çeker ama çekilen commitler local yerine remote branch olarak depolanır.Bu sayede local'deki kod ile merge etmeden önce gözden geçirme şansı verir.
* 'git pull' komutu upstream'deki dosyaları çeker ve local'deki kodla direk birleştirir.
* 'git merge' komutu başka bir branch'deki değişiklikleri kendi branchimize entegre etme işlemidir.

**Bu üç komut arasındaki farklar ise 'git pull' tüm dosyaları birleştirirken,'git merge' ise iki branch'i birleştirmektedir.'git fetch' ise remote branch yaratır. 

7. Merge conflict nedir?

* İki kişinin aynı dosyayı ve aynı satırı değiştirir ve git bunları otomatik olarak merge edemezse bu duruma "merge conflict" denir.

8. Merge conflict'i nasıl çözeriz?

* Github'tan "Pull Request" oluşturarak sorunu çözebiliriz.