# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Versiyon kontrol sistemidir. Orjinal şeyleri bozmadan yenisini oluşturmak için kullanabiliriz.Yeni bir branch oluşturarak.Çalışırsa kullanırız .Çalışmazsa çöpe atarız .Yaptığımız herşeyi kaydetmeye versiyonlama diyoruz.Git de bize bunu sağlıyor.

2. Git ile GitHub arasında ne fark var?
Git: Versiyonlama sistemi
GitHup: Versiyonları Depoladığımız yer (Projeleri başka insanlarla paylaşabiliyoruz)

3. Neden bir branch oluşturuyoruz?
Yeni bir future u denemek için branch oluşturuyoruz.
Ana kodları bozmamak için branch oluşturuyoruz sonra pullrequest e gönderiyoruz.

4. Pull Request'in amacı nedir?
Projenin kopyasını alıp üstünde çalıştıktan sonra  tekrar gönderip bunu kontrol etmesini istiyoruz.rica ediyoruz(pullrequest)
Projede yapılan değişiklikleri merge etmesi için istek göndermek.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout -b "pinarulgener"
git checkout -b main

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
it fetch: yeni yapılan şeyleri local e çekiyor birleştirmiyor.(Diğer branclerdeki değişikliklerin hepsini görmemizi sağlıyor)

git merge: İki branch i birleştirmek için kullanıyoruz.

git pull:Bütün çalışmaları almış ve değiştirmiş oluyor.remote server dan değişiklikliği alıyoruz.

7. Merge conflict nedir?
Çakışmadır.Problemi merge yapan kişiye söylüyor.

8. Merge conflict'i nasıl çözeriz?
