# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Git, dağıtık bir sürüm kontrol sistemi olarak kullanılan bir yazılımdır. Kodların ve dosyaların tarihçesini saklar, değişiklikleri takip eder, farklı sürümler arasında geçiş yapmayı sağlar.

2. Git ile GitHub arasında ne fark var?
Git, sürüm kontrol sistemi olarak kullanılırken GitHub, Git tabanlı bir kod barındırma ve paylaşma platformudur. Git ile yapılan değişiklikler GitHub üzerinde paylaşılabilir, işbirliği yapılabilir ve proje takibi yapılabilir.

3. Neden bir branch oluşturuyoruz?
Bir branch oluşturmanın amacı, mevcut kod tabanının bir kopyasını alarak, yeni bir özellik veya düzeltme eklemek için ayrı bir çalışma alanı oluşturmaktır. Bu sayede, birden fazla kişi aynı anda farklı özellikler veya düzeltmeler üzerinde çalışabilir ve sonradan bu değişiklikler birleştirilebilir.

4. Pull Request'in amacı nedir?
Pull Request, kod değişikliklerinin bir branch'ten diğerine birleştirilmesi için yapılan bir istektir. Bu sayede, kod değişiklikleri incelenebilir, tartışılabilir ve onaylanabilir.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
`git checkout main` komutu kullanılabilir. Bu komut, isim-soyisim branch'inden ana branch'e geçiş yapmanızı sağlar.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
`git fetch`, uzak bir depodaki değişiklikleri yerel depoya indirir ancak yerel dosyalarda değişiklik yapmaz. `git merge`, farklı branch'lerdeki değişiklikleri birleştirir. `git pull` ise git fetch ve git merge komutlarını birleştirerek, uzak depodaki değişiklikleri indirir ve yerel branch ile birleştirir.

7. Merge conflict nedir?
Merge conflict, farklı branch'lerdeki aynı dosyaların aynı satırlarında yapılan farklı değişikliklerin çakışmasıdır. Bu durumda Git, hangi değişikliğin kullanılacağına karar veremeyeceğinden çakışma oluşur.

8. Merge conflict'i nasıl çözeriz?
Merge conflict çözmek için, öncelikle hangi dosyaların etkilendiğini tespit etmek gerekir. Sonra, dosyaların içeriği karşılaştırılarak farklılıklar tespit edilir. Farklılıklar düzeltilerek değişiklikler kaydedilir ve birleştirme işlemi tamamlanır. Bu işlem sırasında `git mergetool` gibi araçlar kullanılabilir.