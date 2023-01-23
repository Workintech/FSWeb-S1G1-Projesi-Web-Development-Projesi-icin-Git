## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
Açık kaynak dağınık versiyon kontrol sistemidir. Her kullanıcı kendi değişikliklerini yapabilir ve en son tamamı merkezde birleştirilebilir. Birden fazla kişinin tek bir projede eş zamanlı çalışmasını sağlar.
2. Git ile GitHub arasında ne fark var?
GitHub her yazılımcının kendi reposunu oluşturduğu ve tamamının depolandığı açık kaynak servis sistemidir. Git ise kodların terminalde yazıldığı dağınık versiyon kontrol sistemidir.
3. Neden bir branch oluşturuyoruz? 
Ana projeyi değiştirmeden, proje üzerinde değişiklikler yapmak için branch oluşturulur.
4. Pull Request'in amacı nedir?
Mevcut branch i, diğer branch e göndermek için yapılan istektir. Bu sayede gönderilen branch, üzerinde yapılan çalışmalar kapsamında diğer tarafta değerlendirilir.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
git checkout BRANCH(hangi branch e geçilmek isteniyorsa) onun adı yazılır. Yani git checkout main yazılır.
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
Git fetch ile bir repodaki değişiklikleri alırız ama localdeki dosyaları güncellemeyiz. Git merge ile alınan değişiklikleri localimizde güncelleriz. Git pull ise önce fetch sonra merge in yapılmış, birleştirilmiş halidir.
7. Merge conflict nedir?
Merge conflict aynı satırın farklı zamanlarda yapılan çalışmalarında çıkan çakışmanın, hangi değişikliği yapacağını kişiye sormasıdır.
8. Merge conflict'i nasıl çözeriz?
Değişen satırlara detaylı bakılır ve doğru olan seçilir.
