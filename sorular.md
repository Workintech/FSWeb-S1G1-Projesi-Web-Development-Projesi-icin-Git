# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Git bir versiyon kontrol sistemidir.

2. Git ile GitHub arasında ne fark var?
Git bir versiyon kontrol sistemi iken, github bunları içinde barındıran bir şirkettir. 

3. Neden bir branch oluşturuyoruz?
 proje üzerinde yapılan değişiklikleri projenin orjinalini bozmamak için oluşturulur. 
4. Pull Request'in amacı nedir?
 Bir dalda yapılan değişikliği başka bir dala aktarmayı yapar. 
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout -b main
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch uzaktaki bir repositorynin değişikliklerini yerele indirmeye yarar.
git merge bir branch de yapılan değişiklikleri diğer branchle entegre etmeye yarar.
git pull uzak sunucudaki değişiklikleri yerele çekmeye yarar.
7. Merge conflict nedir?
branchler arasında ortak bir dosya değiştirilmişse, bu branchlerin merge işlemi sırasında merge conflict ortaya çıkar.
8. Merge conflict'i nasıl çözeriz?
çakışma olan dosya açılır, gerekli değişiklikler yapılır, kaydedilir.