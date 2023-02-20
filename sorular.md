## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz.

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
   Git bir versiyon kontrol sistemdir. Kolektif calismak icin yaratilmis bir platfomdur. Local olarak calisir.
2. Git ile GitHub arasında ne fark var?
   Github yazilimcilarin kolarini birbirleriyle paylasmak/yardimlasmak/gostermek icin kullandiklari plaformdur. Git uzerinden yapilan degisiklikleri buraya yansitabiliriz. Git localdir ve servera ihtiyac duymaz.
3. Neden bir branch oluşturuyoruz?
   Branch olusturmanin amaci main uzerindeki devam eden degisiklikler disinda yanda yapilan ekleme/cikarmalarin belirtilmesi ve bu degisikligin devam etmekte olan main koda yansimamasidir. Bu degisikliklerin onaylanmasi halinde brancher main e merge edilebilir. Ana amac coklu calisma ortamini( main kodu dagitmayarak) saglamaktir.
4. Pull Request'in amacı nedir?
   Pull Request open source yazilimlarda baska yazilimcilar tarafindan yapilan degisikliklerin onerilmesi olarak ozetlenebilir.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.

git checkout master (master offensive buludungu icin main e gecilmis sanirim) ile ana branche gecilebilir. ancak degisikliklerinkaydedilmesi onemli.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
   git fetch repodan en son degisiklikleri indirir ancak local branch ile birlestirmez.Main bracnhi kopyasini gunceller ve degisiklikleri commit etmeden once incelememe olanak saglar.

git merge local branchlerin diger dallarla birlesmesini saglar.

git pull git fetch ve git merge komutunu ayni anda gerceklesitir.

7. Merge conflict nedir? Merge Conflict ayni kod uzerinde birden fazla versiyonlarinin merge edilmesinden kaynaklanir. Bu durumda github iki degisiklik oldugunu ve bu degisikliklerden cakisanlarin oldugunu belirtir vefarkli yerleri gostererek seceneklerden biriyle devam edilmesi gerektigini belirtir.
8. Merge conflict'i nasıl çözeriz?
   git bunu otomatik olarak yapamaz coder mudehale eder ve uygun olan versiyonu secerek merge eder.
