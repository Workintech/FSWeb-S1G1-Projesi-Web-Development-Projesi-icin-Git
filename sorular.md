# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

Git, yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol sistemidir.

2. Git ile GitHub arasında ne fark var?

Git bir versiyon kontrol sistemidir. GitHub ise bu versiyon kontrol sistemi ile kullandığımız projeleri depolayabildiğimiz bir portal diyebiliriz.

3. Neden bir branch oluşturuyoruz?

 Branch oluşturmak kullanıcıya çalıştığı projenin farklı versiyonlarına erişmesini sağlar.

4. Pull Request'in amacı nedir?

Pull request talebi, temelde branch'dan sorumlu kişiden kodunuzu eklemesini istemektir. Ayrıca o kişinin kodda tam olarak neyi değiştirdiğinizi görmesine de yardımcı olur.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

git checkout main branch

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

Git fetch, uzaktaki bir deponun dosyalarını, anlık görüntülerini ve referanslarını yerel deponuza indiren bir komuttur. Bu komut, yerel deponuzun mevcut çalışma durumunu güncellemeden uzaktaki verileri indirir, çalışmanızı olduğu gibi bırakır. Git merge işlemi başka bir branch'deki değişiklikleri üzerinde çalıştığınız kendi branch'inize entegre etme işlemidir. Git pull komutu uzaktaki bir depodan verileri getirip indirirken yerel depoyu getirilen verilerle eşleşecek şekilde günceller. Git pull komutu, git fetch ve git merge komutlarının bir kombinasyonu gibidir, bu nedenle başlangıçta git fetch komutunun işlevini yerine getirir ve daha sonra commit’i birleştirir ve yeni bir merge commit oluşturur.

7. Merge conflict nedir?

İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır.

8. Merge conflict'i nasıl çözeriz?

Conflict olmadan önce çalıştığımız branchi sıklıkla master üzerinden rebase komutuyla güncelleştirmektir.(çakışma ihtimaline karşı yine de öncesinde kendi kodumuzu stash komutuyla güvenceye alıp rebase sonrası tekrar kullanabiliriz) Stash işleminden sonra yine conflict olabilir bunun için manuel düzeltme yapmak gerekir.Düzeltmeden sonra tekrar bunu git'e bildirmek gerekiyor. 

Conflict olduktan sonra git reset komutuyla commitlerimizi geri alıyoruz.(kaç tane commit yaptıysak: git reset HEAD~1,2,3...) Sonrasında yine conflict olmadan önceki güvenlik işlemlerini yapabiliriz. Bundan sonra sırasıyla: 

git add -A

git commit -m “Çakışma giderildi.”

git push --force

Bu işlemlerin sonrasında takım arkadaşlarımızla code review yapıp kendi branchimizi master branchine merge edebiliriz.
(kaynak: https://medium.com/@aliustaoglu/git-cakismalarini-gidermenin-etkili-yollari-91b1160ce2e9)
(bu yöntem okuyup anlayabildiğim bir yöntemler bütünü olduğu için yazdım, başka yöntemlerin var olduğunu da fark ettim)