# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

git bir proje üzerinde değişikler takım halinde yapmamızı takım arkadaşlarımız ile paylaşmamızı sağlayan bir araçtır.

2. Git ile GitHub arasında ne fark var?
github bir çeşit memory görevi görürken git ise projeyi local bilgisayarımıza çekip değişiklikler yapmamızı daha sonra github'a push'lamamıza olanak sağlar.

3. Neden bir branch oluşturuyoruz?
bir projeye yeni bir özellik eklerken branch oluştururuz daha sonra başka özellik ekleyen takım arkadaşlarımız da bizde main projeye merge etmemiz gerekmektedir.

4. Pull Request'in amacı nedir?
local bilgisayarımızdaki projenin son halini kontrol etmemiz için pull request göndermemiz gerekmektedir.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

git branch isim-soyisim komutu ile branch oluştururuz. git chekcout -b isim-soyisim komutu ile 'isim-soyisim' branch'ine geçeriz.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git merge komutu iki branch'i birleştirmek için kullanılır. git merge komutunun kullanıldığı branchin içine diğer branch taşınır.
Git Fetch, local repository , değişiklikleri local repository  getirmeden remote repository  kullanılabilir değişiklikler olduğunu söyleyen komuttur. Git Pull ise remote repository  değişikliklerinin kopyasını local repository getirir.

7. Merge conflict nedir?
merge conflict aynı özellik üzerinde oluşturulan iki branch'in çatışması durumudur. merge durumu geri çekmek için git merge --abort komutunu kullanabiliriz.
8. Merge conflict'i nasıl çözeriz?
aynı dosya üzerinde iki fakrlı branch farklı değişikler yaptığında manuel olarak kendi branch'mizdeki değişiklikleri, gelen branch'de yapılan değişiklikleri veya her iki branch'deki değişiklikleri kabul etmemiz gerekecek ayrıca değişiklikleri karşılaştırabiliriz.DAha sonra git add ve git commit komutları kullanılır.
