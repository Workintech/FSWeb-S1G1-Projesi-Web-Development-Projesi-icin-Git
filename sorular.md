# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
   Git açık kaynak, versiyon kontrol sistemidir. Bilgisiyarmızda local olarak github'la ilgili her şeyden git sorumludur. Örneğin local kodu github'a push etmek gibi.

2. Git ile GitHub arasında ne fark var?
   Github bir site iken git bir araç olarak görülebilir. Localde git'le alakalı yaptığımız değişiklikleri ya da github ta bulunan kodları almak için git'i kullanırız. Github kodlarımızı depolayabildiğimiz ve paylaşabildiğimiz bir sitedir.

3. Neden bir branch oluşturuyoruz?
   Her proje oluşturulduğunda master branch oluşur. Bu master branch'e ana kodu değiştirmiden bir değişiklik yapıp daha sonradan yaptığımız değişikliği yeni oluşturduğumuz branch ile birleştirip atabiliriz

4. Pull Request'in amacı nedir?
   Proje üzerinde bir değişiklik yaptıktan sonra proje sahibinden değişikliği gözden geçirmesi ve birleştirmesi talep etmek için yapılır.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
   git checkout main

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
   git pull, git fetch metodunu kullanak github'daki repository deki değişiklikleri şuanda bulunan branch'la birleştirir. git pull'un özelliği ise duruma göre git merge ve git rebase yapmasıdır. git merge ise iki branchı birleştirmek için kullanılır.

7. Merge conflict nedir?
   Versiyon konrol sistemleri genelde birkaç kişinin koda değişikler yapması gerektirir. Bazen bu durumlarda birkaç yazar aynı kod parçasını değiştirebilir. Bu iki kod parçası birleştirilmeye çalıştığında merge conflict a neden olur.

8. Merge conflict'i nasıl çözeriz?
   Git merge conflite neden olan kısımları bize incelemeyiz. Daha sonra hataya sebep olan kısımları incelip kodu düzeltip. Yeni git'ten merge etmeyi deneyebiliriz.
