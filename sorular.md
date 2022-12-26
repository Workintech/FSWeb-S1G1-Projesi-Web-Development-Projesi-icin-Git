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



1) Yazılım geliştirme süreçlerinde kullanılan versiyon kontrol sistemlerinden birisidir. Git ile çalışılan bir projenin önceki versiyonlarını tekrar kullanılabilir ve eski - yeni versiyonları arasında geçiş yapılabilir.

2) Git versiyon kontrol sistemidir. Github ise git kullanan projeler için bi depolama servisidir.

3) Mevcut projemize bir yenilik eklemek ya da farklı versiyonlara dönüş yapabilmek için halihazırda kullanılan  projenin versiyonunda değişiklik ya da olumsuzluk olmasını istemiyorsak branch oluşturmalıyız. Branch yardımı ile projemizin çalışır halini kaydedip, yeni eklenti üzerinde rahatlıkla çalışabiliriz

4) Bir proje forklanıp değişiklikler yapılabilir. Burda yapılan değişikliler forkladığımız için bizim tarafımızda kalır. Bunların asıl projeye eklenmesi için pull request yapılır. Asıl projenin sahibi değişikleri uygun bulursa bu değişiklikler asıl projeye uygulanır.

5) Branchler arası geçiş için ; " git checkout  branchismi " kullanılır. Şu an kullandığımız branch  onurarici ise " git checkout main" komutu ile main branche geçebiliriz.

6) Git fetch: Örneğin pcmizde bulunan repolarmızın githubdaki repo içeriğine güncellenmesidir. 

   Git merge: Farklı branchdeki değişikleri üzerinde çalışılan bir diğer branche entegre etmek için kullanılabilir. 

   Git pull : Bulut depoda bulunan değişikleri yerel dizinlere yani bilgisayarlarımıza çekmek için kullanılır.	

7) İki kişi aynı dosyayı ve aynı satırı değişirse silerse ya da aynı isimki dosya oluşturulursa  git bunları merge edemezse conflict - çakışma oluşabilir.

8) Çakışmanın neden olduğunu incelemek gerekir. Git status komutu ile unmerged dosyalar aranabilir.

   
   
   
