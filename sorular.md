# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

Git, yazılım geliştirme süreçlerinde projelerin depolandığı bir yerdir. Burada birden çok yazılımcının geliştime yapmasına olanak sağlar. Ekipteki kişilerin eskiden
yazılmış olan kodlarada tarihçe olarak erişebildiği bir ortamdır.

2. Git ile GitHub arasında ne fark var?

Git ile Github isim olarak benzeseler de farklı şeyler. Githubta depolarımızı başkaları ile paylaşabiliriz, diğer kişilerin neler yaptığını görebiliriz bilgisayarımıza
indirip üstünde değişiklik yapabiliriz. Bir projede diğer kişilerin nasıl değişiklik yaptıklarınıda takip edebiliriz. Git ise bu projelerin saklandığı kapsamlı bir depodur.


3. Neden bir branch oluşturuyoruz?

Direkt ana kodu etkilememek ve hatalı bir kod yazarsak ortamların bozulup, aksaklığa sebep olmaması için  branch oluştururuz.

4. Pull Request'in amacı nedir?

Yaptığımız geliştirmede hatalı bir yer var  mı ya da değiştirilmesi gerekn bir yer var mı diye başka bir geliştiricye kodumuzu yolladığımız yer eğer bir sorun yok ise kodda ki değişikliği
ortamlara geçiririz. Eğer olmayan yer varsa ya da değişiklşk olması gereken yer varsa açıklama yapılıp o kısımlarıan değiştirilmesi beklenir. 

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

Farklı bir branche  geçmek için git checkout komutundan sonra geçiş yapmak istediğimiz branch adını yazmamız gerekir. Örneğin git checkout main yazabiliriz.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

Git fetch değişiklikleri uzak depodan yerel depoya çeker. Git pull da benzer işlemi yapar fakat güncellemelerin eşleşmesini sağlar. Fetch işmemi yaptıktan sonra merge 
yapmadan değişiklikleri yerel klasöre kopyalamaz.


7. Merge conflict nedir?
 
 Geliştiricin kodda yaptığı düzenlemelerin çakışmasına denir.

8. Merge conflict'i nasıl çözeriz?

Hangi kodda değişiklik istiyorsa orada yaptığı çakışan düzenlemeleri gözden geçirir. En güncel hale getirerek kodda yapılan değişiklikleri son halini baz alır. Böylece düzelebilir.
