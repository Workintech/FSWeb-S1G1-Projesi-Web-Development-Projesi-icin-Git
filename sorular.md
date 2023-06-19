# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Git, açık kaynaklı dapıtılmış sürüm kontrol sistemidir. Git, sürüm kontrol sistemi sayesinde birden fazla kişinin çalıştığı projelerde proje üzerinde yapılan değişiklikleri görmemizi ve bu süreci yönetmemizi sağlar.Açık kaynak olması orjinal kodların herkes tarafından erişilebilmesini ve uygun görülen şekilde değişiklikler yapılmasını sağlar. Ayrıca bir git içeriği depolamak için kullanılabilir.Geliştiricilerin kodun yerel sürümleri üzerinde çalışabilmelerini, değişiklik yapabilmelerini ve en yeni revizyonu yükleyebilmelerini sağlayarak kolayca işbirliği yapmalarına olanak tanır. Her geliştirici bu yeni değişiklikleri görebilir, indirebilir ve katkıda bulunabilir.

2. Git ile GitHub arasında ne fark var?
GitHub, Git tabanlı çalışan projeler için bir cloud sistemidir. Git, geliştiriciler için bir versiyon kontrol sistemidir. GitHub'a git tabanlı projelerimizi yükleyebilir, başka projelere ulaşıp bu projeleri bilgisayarımıza indirip Git ile değişikleri yaparak tekrar GitHub'a yükleyerek güncel versiyonunu paylaşabiliriz.

3. Neden bir branch oluşturuyoruz?
Hali hazırda sürekli çalışan bir projeye yeni bir özellik eklemek istediğimizde yeni bir branch oluştururuz. Yeni oluşturduğumuz branch sayesinde ana proje eklemek istediğimiz yeni özelliğin test süreci tamamlanana kadar hibçir şekilde etkilenmeden çalışır.

4. Pull Request'in amacı nedir?
Pull Request sayesinde, projede yaptığımız değişiklikleri, projenin sahibine pull request olarak gönderebiliriz. Pull request olarak göndermek demek; ben projede değişiklikleri yaptım, sen de bu değişiklikleri onayla ve istersen projeye merge et demektir. 

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
Bir branch'ten diğerine geçmek için "git checkout" komutunu kullanırız. Main branch'ine geçmek için "git checkout main" yazarak main branch'ine geçiş yaparız.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
 1.Git fetch: Kodu uzak bir depodan yerel depoya çeken komuttur. Bu komut uzak bir depoda yapılan değişiklikleri kendi depomuzdaki aynı dosyadan farklı bir dosyaymış gibi çekerek uzak depoda yapılan değişikler ile bizim hali hazırda yapmakta olduğumuz değişiklikler arasında çakışma olmamasını sağlar.
 2.Git merge: Herhangi bir brach'de yaptığımız değişiklikleri master branch'imiz ile birleştirme veya master branch'e entegre etme işlemidir.
 3.Git pull: Uzak depoda yakın zamanda yapılan değişiklikleri indiren ve bunları yerel bir depoda birleştiren bir komuttur. Bu komut uzak bir depoda yapılan değişiklikleri kaydeder ve bunları birleştirir, bu da çakışmalara sebep olur.

 Git Pull, mevcut HEAD dalınızı uzak sunucudan gelen en son değişikliklerle güncellemek için kullanılır. Pull yeni verileri indirir ve doğrudan mevcut çalışma kopyası dosyalarınıza entegre eder. Yaptığı bu entegre mevcut dosyada çakışmalara yol açabilir. Git fetch ise dosyalar arasında birleştime yapmadan sadece uzak depodaki yeni verileri farklı bir görünümmüş gibi çektiği için çakışmalara neden olmaz. Git Fetch kodu ile indirme yapıp birleştirme yapmak için ayrıca Git Merge kullanılır. Bu da bize şunu verebilir Git Pull = Git Fetch + Git Merge. Git Pull direkt birleştime yaptığı için bize indirdiğimiz kodda herhangi bir kontrol sağlamazken Git Fetch ile indirdiğimiz kodu kontrol ettikten sonra Git Merge ile birleştirme yapmak çakışma olasılığını azaltmamızı sağlar. 

7. Merge conflict nedir?
 Merge conflict, branch'lerin birleşmelerinde yaşanan çakışmalardır. 

8. Merge conflict'i nasıl çözeriz?
Merge conflict'i çözmek için branchleri git merge ile birleştirmek yerine git rebase ile birleştime yöntemini seçebiliriz. Bu yöntem sayesinde iki branch'de yapılan commitler arasında seçim ve düzenleme yapabiliriz. Bu sayede merge conflict oluşmamış olur. Ancak bu da versiyon takibi için sıkıntı yaratabilir.
