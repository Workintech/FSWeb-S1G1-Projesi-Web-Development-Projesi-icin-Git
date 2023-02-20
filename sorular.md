## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
Git, yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol sistemidir. Git sayesinde yapacağınız projelerin adım adım versiyonlarının kopyalarını alarak daha sonra ihtiyaç duyduğunuzda aldığınız kopyalara yani versiyonlara kolayca dönebiliyorsunuz.  İlk sürümü Linux çekirdeği'nin geliştirilmesinde kullanılmak üzere 2005 yılında Linus Torvalds tarafından tasarlanıp geliştirilmiş, 2019 yılı itibarıyla %70 pazar payına ulaşmıştır. Açık kaynaklı özgür bir yazılım ürünü olan Git'i istediğiniz gibi kullanabilirsiniz.

2. Git ile GitHub arasında ne fark var?
Git ve GitHub Nedir? Git bir versiyon kontrol sistemidir. GitHub ise bu versiyon kontrol sistemi ile kullandığımız projeleri depolayabildiğimiz bir portaldır.

3. Neden bir branch oluşturuyoruz? 
ranch oluşturmak kullanıcıya çalıştığı projenin farklı versiyonlarına erişmesini sağlar. Kullanıcı, projesine bir yenilik eklemek istediğinde, yaptığı değişiklik projenin çalışmasını olumsuz etkileyebilir. Bu gibi durumlarda projemizin o anki halini bozmamak için branch kullanabiliriz.

4. Pull Request'in amacı nedir?
Fork ettiğimiz bir projenin üzerinde çalışıp, projede yaptığımız değişiklikleri, projenin sahibine pull request olarak gönderebiliriz.

5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
git checkout kullanılır.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git pull önce bir git fetch yapar, sonrasında ise git merge uygular. fetch kullandığınızda, Git, hedef branchteki bulunan ve mevcut branchte bulunmayan herhangi bir commit işlemini yapar ve yerel reponuza kaydeder. Ancak, bunları mevcut branchiniz ile birleştirmez. pull kullandığınızda, Git otomatik olarak merge çalışır. Bağlamsal olarak hassastır, bu nedenle Git şu anda çalıştığınız branch için herhangi bir commit varsa birleştirecektir.

7. Merge conflict nedir?
İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır.

8. Merge conflict'i nasıl çözeriz?
İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır. Bu durumda çakışma yaşayan kişi gerekirse ekipteki diğer kişi ile beraber oturup çakışmayı çözdükten sonra merge işlemine devam etmelidir.

