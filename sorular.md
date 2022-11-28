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



1 GİT : Git, yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol sistemidir. Git sayesinde yapacağınız projelerin adım adım versiyonlarının kopyalarını alarak daha sonra ihtiyaç duyduğunuzda aldığınız kopyalara yani versiyonlara kolayca dönebiliyorsunuz.

2 GİT - GİTHUB
GİT: yazdığımız projeleri ve uygulamaları, bilgisayarımızda ya da harici disklerde değilde internet üzerinde tutmamızı ve yönetmemizi sağlayan bir versiyon kontrol sistemidir.

GİTHUB:sürüm kontrol sistemi olarak Git kullanan yazılım projeleri için bir depolama servisidir. GitHub özel depolar için ücretli üyelik seçenekleri sunarken, açık kaynaklı projeler için ücretsizdir.

3-NEDEN BRANCH ? :Kullanıcı, projesine bir yenilik eklemek istediğinde, yaptığı değişiklik projenin çalışmasını olumsuz etkileyebilir. Bu gibi durumlarda projemizin o anki halini bozmamak için branch kullanabiliriz.

4-Pull request talebi, temelde branch'dan sorumlu kişiden kodunuzu eklemesini istemektir. Ayrıca o kişinin kodda tam olarak neyi değiştirdiğinizi görmesine de yardımcı olur.

5-branchler arası geçiş :git checkout

6-`git fetch`, `git merge` ve `git pull`

git fetch:  Repomuzu güncel tutmamız gerekiyorsa, ancak dosyalarımızı güncellersek de bozulabilecek bir şeyler varsa fetch kullanmayı tercih ederiz. Bu işlemleri mevcut branchinize entegre etmek için sonrasında merge kullanmalısınız.

git pull: pull yapılan değişiklikleri gözden geçirmenize izin vermeden otomatik olarak birleştirir diyebiliriz. Eğer branchlerinizi dikkatlice yönetmiyorsanız, sık sık sorunlarla karşılaşabilirsiniz.

git merge: Git'de merge işlemi başka bir branch'deki değişiklikleri üzerinde çalıştığınız kendi branch'inize entegre etme işlemidir. Git merge işlemi sırasında değişikliklerin çoğunu sizin için otomatik olarak entegre eder.

7-merge conflict : İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır. 

8-çözümü : Bu durumda çakışma yaşayan kişi gerekirse ekipteki diğer kişi ile beraber oturup çakışmayı çözdükten sonra merge işlemine devam etmelidir

