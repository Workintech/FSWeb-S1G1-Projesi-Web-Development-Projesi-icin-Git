# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

2. Git ile GitHub arasında ne fark var?

3. Neden bir branch oluşturuyoruz?

4. Pull Request'in amacı nedir?

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

7. Merge conflict nedir?

8. Merge conflict'i nasıl çözeriz?
## Sorular

1. Git nedir?

  -Git, yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol sistemidir.
2. Git ile GitHub arasında ne fark var?

  Git sistemi kullanan bir hizmettir.Github ise projelerimizin saklandığı(depolandığı) uzak sunucudur.
3. Neden bir branch oluşturuyoruz?

Branch oluşturmak kullanıcıya çalıştığı projenin farklı versiyonlarına erişmesini sağlar.
4. Pull Request'in amacı nedir?

-Yapılan değişiklerin projeye katkısı bulunması isteniyorsa repo sahibine iletilmesidir.
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

git branch ile mevcut branchler listelenir
 git checkout main ile main branchine geçilir.
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

-git fetch:Uzak sunucudaki kodları localimize indirir fakat pull gibi merge işlemini gerçekleştirmez.
-git pull: Uzak sunucudaki değişiklikleri veya herhangi bir projeyi localimize çekmek için kullanılır. 
 git merge: git branch tarafından oluşturulan bağımsız geliştirme satırlarını almanızı ve bunları tek bir branch'ta birleştirmenizi sağlar.
7. Merge conflict nedir?

-Merge conflict, Git'in iki işlem arasındaki kod farklarını çözemediği durumlarda meydana gelen çakışma durumudur.
8. Merge conflict'i nasıl çözeriz?
-Kod yazarken bolca fetch işlemi yapmak çakışmayı önler. Çakışma olursa eğer git reset ile işlem geri alınır ve yeniden pull yapılır.