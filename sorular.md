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

C1. Git, bir versiyon güncelleme sistemidir. Linus Torvalds tarafından 2005'te ilk olarak Linux'u geliştirmede yardımcı
olması açısından geliştirilmiştir.

C2. Git bir sistem iken, GitHub bu sistemi kullanan kâr amaçlı bir şirket ismidir.

C3. Yapacağımız değişiklikler ana kodda yer almadan önce daha iyi maintain edilebilmesini sağlamak amacıyla
bir branch üstünde yaparsak kod geliştirme açısından daha verimli olacaktır.

C4. Repository sahibine veya yetkililerine repository'lerini güncellemeleri için bir sinyal vermek olarak düşünülebilir.
Pull Request'i bu kişiler inceleyip kendi repository'lerine bu request'in içeriğini merge edebilirler.

C5. git checkout BRANCH_ISMI olarak bir branchten diğerkine geçilebilir. git branch komutu ile de varolan branchlar
görüntülenebilir.

C6. git fetch ve git pull aynı görevi görür sadece git fetch, pull gibi overwrite etmez.
