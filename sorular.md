## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
-Git versiyon kontrol sistemidir. Yapılan değişiklikleri, eklemeleri ya da silmeleri kontrol altına alan sistemdir. Bir bakıma yapılan projeyi sağlam adımlarla ilerletmeye yarar.
2. Git ile GitHub arasında ne fark var?
-Git versiyon kontrol sistemi iken github versiyon kontrol sisteminin çalıştığı bulut tabanlı bir uygulamadır/web sitesidir. Git local iken github online kontrol sağlar. 
3. Neden bir branch oluşturuyoruz? 
-Branch oluşturarak projeyi dallandırıyoruz. Aynı anda birden fazla kişinin çalışmasına olanak sağlayabiliyoruz bu şekilde.
4. Pull Request'in amacı nedir?
-Forkladığımız projedeki değişikleri proje sahibine yollamak için kullanıyoruz. Amaç; yapıtığımız değişikleri proje sahibinin ve başkalarının görmesini sağlamak.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
-git checkout -b "furkan-akif-islek"
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
-git fetch uzaktaki dosyaları pc'de kopyasını oluşturur ama değiştirmez. git merge ile değişim sağlanır. git pull iki komutu tek kod ile yapar hem değişikleri indirir hem de uygular.
7. Merge conflict nedir?
-aynı projede kodların çakışması durumu. 
8. Merge conflict'i nasıl çözeriz?
-git merge komutu ile conflict tespit edilir. <<<<, ====, >>>> yazan kısımlar silinir. Ondan sonra yeniden sırayla git add . , git commit -m "message", git push işlemleri yapılır
