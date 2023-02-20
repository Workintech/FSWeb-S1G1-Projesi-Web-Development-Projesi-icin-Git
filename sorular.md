## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
-Git, yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol sistemidir. Git sayesinde yapaılan projelerin adım adım versiyonlarının kopyalarını alarak daha sonra ihtiyaç duyulduğunda alınan kopyalara yani versiyonlara kolayca dönebilme imkanı sağlar.
Açık kaynaklı özgür bir yazılım ürünüdür.Git,  merkezi sürüm kontrol sistemlerinden farklı olarak özellik dalları (feature branches) sunar. Bu, ekipteki her yazılım mühendisinin kodda değişiklik yapmak için yalıtılmış bir yerel depo sağlayan bir özellik dalını ayırabileceği anlamına gelir.
2. Git ile GitHub arasında ne fark var?
-Git bir versiyon kontrol sistemidir. GitHub, sürüm kontrol sistemi olarak Git kullanan yazılım projeleri için bir depolama servisidir. 
3. Neden bir branch oluşturuyoruz? 
-Branch oluşturmak kullanıcıya çalıştığı projenin farklı versiyonlarına erişmesini sağlar. Örneğin, projeye yeni bir özellik eklemek istediğimizde projenin patlama ihtimali olduğu için, branch yardımı ile projenin çalışır halini kaydedip, yeni eklenti üzerinde çalışma imkanı sağlanmış olur. Projede herhangi bir sorun çıktığı takdirde geri dönüp önceki versiyona erişebiliriz. 
4. Pull Request'in amacı nedir?
-Pull request, projede birlikte çalışılan kişileri bir dalda yapılan değişikliğin ana depoya gönderildiğine dair bilgilendirdiğiniz anlamına gelmektedir. Bu depo, katkıda bulunanları kabul edebilir veya reddedebilir.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
-Git'de branch değiştirmek için git checkout komutunu kullanabiliriz. git checkout komutunu yazdıktan sonra gitmek istediğimiz branch'in adını yazarız ve geçiş sağlanır.
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
-git fetch : Uzaktaki bir deponun dosyalarını, anlık görüntülerini ve referanslarını yerel depomuza indiren bir komuttur. Bu komut, yerel deponun mevcut çalışma durumunu güncellemeden uzaktaki verileri indirir, çalışmamızı olduğu gibi bırakır ve getirilen içerik gitcheckout komutu kullanılarak açıkça kontrol edilir.Sadece kim ne katkı yapmış onu görmenizi sağlar. 
git merge : Başka bir branch'deki değişiklikleri üzerinde çalıştığımız kendi branch'imize entegre etme işlemidir. 
git pull : Git pull komutu, git fetch ve git merge komutlarının amacına tek bir komutta hizmet eden bir komuttur. Pulls teriminin kendisi, bu komutu kullanan kullanıcının depodan veri veya içerik çekmeye çalıştığını açıklar. Git pull, kullanıcıdan izin istemeden veya belirtmeden git fetch işlevini yerine getirir ve kullanıcıya haber vermeden değişiklikleri birleştirir, yalnızca sonuç, yani bu komutun işleminin başarılı olup olmadığı ve uyarılar vb. kullanıcı tarafından bilinir.
Sonuç olarak, git fetch ve git pull uzak depo ile etkileşime girerken çok sık kullanılır.Uzak depodaki orijinal içeriği etkilemeden yapılabilecek değişiklikleri kontrol etmek veya gözden geçirmek istediğimizde,  git fetch komutunu uygulayabiliriz.
Ancak uzaktaki deponun en son taahhütlerini yerel depomuzun taahhütleriyle birleştirmek istiyorsak, git pull komutunu kullanabiliriz.
Yani sonuç olarak : Git Pull = Git Fetch + Git Merge diyebiliriz.
7. Merge conflict nedir?
-İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır.
Bunun için  git merge --abort komutunu çalıştırırız.
8. Merge conflict'i nasıl çözeriz?
Merge conflict'i önlemenin en iyi yolu,  üzerinde çalıştığımız özellik dalını sıklıkla master üzerinden rebase komutuyla güncelleştirmektir. Bu çakışma olasılığını düşürür.
-git reset HEAD~1 komutu ile yapılan değişiklikleri geri alabiliriz. (2 commit yapıldıysa HEAD~2 komutunu kullanmak gerekir.)
Daha sonra çakışma gerçekleşmeden önce uygulanan tüm adımlar tek tek tekrar uygulanır.
git add -A

git commit -m “Çakışma giderildi.”

git push --force 
komutları uygulanır ve branch'ı master üzerinde merge ederiz. İşlem tamamlanmış olur. 