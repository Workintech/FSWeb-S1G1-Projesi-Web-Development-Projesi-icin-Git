# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Versiyon kontrol sistemidir. Tek merkezde tutulan orijinal kaynak kodlarının kopyalarının diğer kullanıcılara ulaştırılması ve bu kopyalar üzerinde yapılan değişikliklerin kaydedilmesini sağlayan ve projenin güncel kalmasını sağlayan bir sistemdir.

2. Git ile GitHub arasında ne fark var?
Git, proje üzerinde birden çok kişi tarafından değişiklik yapılmasını ve bunların kaydedilmesini sağlayan bir sistemdir. GitHub ise bu projelerin depolandığı git temelli bir paylaşım platformudur.

3. Neden bir branch oluşturuyoruz?
Ana koda zarar vermeden değişiklik yapmak için branch kullanıyoruz . Ana branchi kopyalayarak oluşturduğumuz branch ile geliştirmek veya yeni eklemek istediğimiz özelliği ana branchten bağımsız olarak yaparız. Aynı zamanda diğer yazılımcılar tarafında da kontrol sağlandığı için hata varsa düzeltebiliriz, öneri varsa ekleyebiliriz Bunun sonucunda hatasız ve çalışır bir kod ile ana dosyada devam etmemizi sağlarız.

4. Pull Request'in amacı nedir?
Ana branchten kopyalayarak oluşturduğumuz branchimiz üzerinde yaptığımız değişiklikleri tamamladıktan sonra projeden sorumlu kişiye yapılan değişikliği eklemesi için talepte bulunmayı sağlar. Pull request olarak gönderdiğimizde proje üzerinde değişiklik yaptığımızı sorumlu kişiye bildirir ve bunu onaylayarak ana projeye merge etmesini isteriz.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout main

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git pull: remote repodaki güncel dosyayı kendi branchimize eklemek için kullanılır. 
git fetch, remote repodaki dosyaların güncel halini bilgisayara indirir. Fakat git pulldan farklı olarak değişen her şeyi merge etmez 
git merge: herhangi bir branchte yaptığımız değişiklikleri ana branch ile birleştirme işlemidir.

7. Merge conflict nedir?
İki kişi aynı branchi ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır.

8. Merge conflict'i nasıl çözeriz?
Merge yapacak dosyadan sorumlu kişi çakışan kodları karşılaştırır ve hangisini kullanmak doğruysa onunla devam eder.

