# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Git, Açık Kaynak Dağıtılmış Sürüm Kontrol Sistemi(Open Source Distributed Version Control System)'dir.

2. Git ile GitHub arasında ne fark var?
Git, bir versiyon takip yazılımıdır. Lokal olarak bilgisayarda çalışır ve Github olmadan da Git'i kullanabilmek mümkündür. Github ise Git repository'lerinin cloud üzerinde saklandığı online bir servistir.

3. Neden bir branch oluşturuyoruz?
Branch oluşturmak kullanıcıya çalıştığı projenin farklı versiyonlarına erişmesini sağlar. Kullanıcı, projesine bir yenilik eklemek istediğinde, yaptığı değişiklik projenin çalışmasını olumsuz etkileyebilir. Bu gibi durumlarda projemizin o anki halini bozmamak için branch kullanabilir.

4. Pull Request'in amacı nedir?
Fork edilen bir projenin üzerinde çalışılıp, projede yapılan değişiklikler, projenin sahibine pull request olarak gönderilir. Pull request onaylanması durumunda değişiklik yapılan branch, ana branch'e katılır ve değişiklikler ana branch'e yansır.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout isim-soyisim

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
Git fetch, uzak sunucuda bulunan branch'deki değişiklikleri indirmek için kullanılır. 
Git merge, belirtilen branch'in geçmişini geçerli branch ile birleştirir.
Git pull, uzak sunucudaki değişiklikleri çalışma dizininize getirir ve birleştirir. kısaca git pull = git fetch + git merge denilebilir.

7. Merge conflict nedir?
Git conflict, Git depolama sisteminde bir çatışma olarak tanımlanır. Bu, aynı dosyayı farklı bir üye tarafından değiştirilmesi ve bu değişikliklerin birleştirilmesi gerektiğinde oluşur. 

8. Merge conflict'i nasıl çözeriz?
Çakışma gerçekleşmeden önce bunu önlemenin en iyi yolu, üzerinde çalışılan özellik dalını sıklıkla master üzerinden rebase komutuyla güncelleştirmektir. Çakışma gerçekleştikten sonra "git reset HEAD~X" komutu ile x adet commit geri çekilir ve Çakışma gerçekleşmeden önceki yollar izlenir.