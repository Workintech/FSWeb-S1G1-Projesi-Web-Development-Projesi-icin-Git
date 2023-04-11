# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

Git versiyon kontrol sistemidir. Yazdığınız programı, kodu veya herhangi bir dosyalar topluluğunu, versiyonlara ayırarak ve iterasyonlar halinde geliştirmek istiyorsak kullanacağımız sistem diyebiliriz.

2. Git ile GitHub arasında ne fark var?

Git bir versiyon kontrol sistemidir. Github ise bu versiyon kontrol sistemi ile kullandığımız projeleri depolayabildiğimiz bir portaldır.

3. Neden bir branch oluşturuyoruz?

Kullanıcıya çalıştığı projenin farklı versiyonlarına erişmesini sağlar. Kullanıcı, projesine bir yenilik eklemek istediğinde, yaptığı değişiklik projenin çalışmasını olumsuz etkileyebilir. Bu gibi durumlarda projemizin o anki halini bozmamak için branch kullanabiliriz.

4. Pull Request'in amacı nedir?

Pull request talebi, temelde branch'dan sorumlu kişiden kodunuzu eklemesini istemektir. Ayrıca o kişinin kodda tam olarak neyi değiştirdiğinizi görmesine de yardımcı olur.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

Git checkout komutundan sonra geçiş yapmak istediğimiz branch adı olan git main yazarak main branchına geçiş yapabiliriz. 

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

Remote branch'deki değişiklikleri indirmek için git fetch komutunu kullanırız. Git merge başka bir branch'deki değişiklikleri üzerinde çalıştığımız kendi branch'imize entegre etmemizi sağlar. Git pull komutu local bir branch'i remote versiyona güncellemek için kullanırız.

7. Merge conflict nedir?

İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda merge conflict yani çakışma olacaktır.

8. Merge conflict'i nasıl çözeriz?

Çakışma gerçekleşmeden önce bunu önlemenin en iyi yolu, üzerinde çalıştığımız özellik dalını sıklıkla master üzerinden rebase komutuyla güncelleştirmektir.