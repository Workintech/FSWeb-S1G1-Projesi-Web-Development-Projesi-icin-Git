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
















CEVAPLAR

1- Yazılım geliştirirken kullanılan versiyon kontrol sistemi Git'tir.

2- Git bir versiyon kontrol sistemidir. Github ise bu bu versiyon kontrol sistemi ile çalıştığımız projeleri depolamak için kullandığımız yerdir. 

3- Branch oluşturmamızın sebebi işleyen kod dizilimini daha farklı bir kod dizilimi ile değiştirmeden önce, yeni yazacağımız kodun tam doğru çalışıp çalışmadığını test etmektir. Örnek olarak bir sitenin kodlarını değiştirirken branch yapmazsak ve kodlar hatalı çalışırsa sitenin çalışması aksar.

4- Pull request talebinin amacı, ayrı branch üzerinde çalışırken yaptığımız değişikliklerin ana branche alınması talebidir. 

5- Branchler arası gezme komutu “git checkout” komutudur. Main branche geçmek içinse git checkout main komutunu kullanabiliriz.

6- Git pull repodaki tüm değişiklikleri direkt çalışma dizinimize çeker.
   Git fetch repodaki değişiklikleri local repomuza kopyalar.
   Git merge, git fetch komutu kullanılmadan kullanılırsa çalışmaz. İlk     başta git fetch ile local repomuza kopyaladığımız değişiklikleri git merge ile çalışma dizinimize çekebiliriz.

7- Merge conflict iki kişi aynı dosya ve aynı satırı birbirinden farklı şekilde değiştirirse veya bir kişi düzenleme yaparken diğeri dosyayı silerse ortaya çıkabilir.

8- Aynı satırda iki farklı kod çatışmasını çözmek için, hangi dalın işleme alınacağını karar vererek çözebiliriz. 	
