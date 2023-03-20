# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

   Git, projenin local olarak çalışılmasını sağlar. Geliştiriciler tarafından yapılan güncellemeri kayıt altına alır. Eski versiyon kodlara ise erişim sağlanabilir
 
2. Git ile GitHub arasında ne fark var?

  GitHub, Git tabanlı çalışan cloud uygulamasıdır. GitHub, repository oluşturmamızı böylece veriyi depolamamızı sağlar. Git ise remote olarak repository arasındaki değişikleri sağlayandır. 

3. Neden bir branch oluşturuyoruz?
  Projeye yeni bir kod eklemek istendiğinde çalışmasını aksatma ihtimali vardır. Projeye yeni bir eklenti yapılmadan önce branch'i açılarak değişiklikler yapılabilir. Böylece default branch'e (master) zarar gelmeyecektir. 
  
4. Pull Request'in amacı nedir?

  Fork edilen bir projenin değişikler yapılarak fork ettiğimiz projenin sahibine gönderilen bir taleptir.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

  /git brach/  komudunu kullanarak sahip olduğum branch'lar listelenir. Böylece /git checkout main/ ile main branch'ime geçebilirim.
  
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
 'git fetch', kodu remote repodan local depoya geçiren bir komuttur. Remote depoda yapılan değişiklikeri çakışma yaratmadan tekrar geri yükleyebilmemizi sağlar.(canlı derste konuşulmadı araştırma)
 'git merge', herhangi bir branch'de yaptığımız değişiklikleri main branch'imize birleştirme ve entegre etme işlemidir.  
 'git pull', remote olarak olan değişiklikleri local projelermize dahil edebilmemizi sağlar. Depodan verileri indirip local olarak depolarken eşleşecek şekilde günceller. 
  
  git fetch + git merge = git pull 
 

7. Merge conflict nedir?

  İki kişi aynı dosyada aynı satırı değiştirir ve otomatik olarak merge edememe durumudur. Ortaya bir çakışma çıkmış olur.

8. Merge conflict'i nasıl çözeriz?
   Bu durumda çakışma yaşayan kişi gerekirse ekipteki diğer kişi ile beraber oturup çakışmayı çözdükten sonra merge işlemine devam etmelidir. (kaynak internet)