# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
	Git, bir versiyon kontrol sistemidir. Bir projenin son haline ulaşmamızı  ve güncel tutmamızı sağlayan bir araçtır.

2. Git ile GitHub arasında ne fark var?
	Git, bir versiyon kontrol sistemidir demiştik, GitHub ise bu projeleri depolayabildiğimiz bir portaldır, diyebiliriz.

3. Neden bir branch oluşturuyoruz?
	Branch oluşturmamızın temel sebebi, üzerinde çalışılan projenin orijinalinin korunmasını sağlamaktır. Yeni branch açıldığı zaman, projenin bir kopyası oluşturulur ve bütün değişiklikler ve testler burada yapılır daha sonrasında merge edilerek, ana proje ile birleştirilir. Böylelikle ana proje hiç bir zaman zarar görmez.

4. Pull Request'in amacı nedir?
	Pull Request, fork ettiğimiz projenin üzerinde yaptığımız değişiklikleri, projenin sahibine göndermeye yaramaktadır. Buradan, üzerinde çalışılan projede kimler hangi değişiklikleri ne zaman yapmış, hepsini görebilmekteyiz. Pull Requestin temel amacı, branchtan sorumlu kişiden kodu eklemesini istemektir.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
	Git'te bir branchten diğerine geçmek için "git checkout" komutu kullanılır. Eğer şu anda "isim-soyisim" branch'inde çalışıyorsam ve "main" branch'ine geçmek istiyorsam, '' git checkout main'' komutunu kullanırım. Bu komut, mevcut çalışmamı "main" branch'ine değiştirir ve bu branch'de çalışmaya devam etmemi sağlar.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
	git fetch, uzak depodaki değişiklikleri yerel depoya indirir.
	git merge, farklı iki branch arasındaki değişiklikleri birleştirir.
	git pull ise , git fetch ve git merge işlemlerini birleştirerek uzak depodaki değişiklikleri hızlı bir şekilde almamızı ve yerel depo ile birleştirmemizi sağlar.

7. Merge conflict nedir?
	Merge conflict (birleştirme çakışması), Git'te iki veya daha fazla branch'te aynı dosyanın aynı satırında yapılan değişikliklerin birleştirilmesinde ortaya çıkan bir durumdur. Bu durum, Git'in otomatik olarak iki değişikliği birleştirmesi mümkün olmadığında ortaya çıkar.

8. Merge conflict'i nasıl çözeriz?
	Bir merge conflict durumunda,  birleştirme işleminin otomatik olarak yapılması yerine, kullanıcının manuel olarak çakışmayı çözmesini gerekir. Bu işlem genellikle bir metin düzenleyicisi kullanılarak  ve kullanıcının çakışmanın her iki tarafındaki değişiklikleri birleştirerek gerçekleştirilebilir.