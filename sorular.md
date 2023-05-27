# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
    Versiyon kontrol sistemi
2. Git ile GitHub arasında ne fark var?
    Gİthub internet  üzerinden erişebilen repoların olduğu bir yapıdır.
3. Neden bir branch oluşturuyoruz?
    Üzerinde çalışılan koddan bağımsız bir şekilde geliştirme yapabilmek için.
4. Pull Request'in amacı nedir?
    Koddan sorumlu kişinin kodu yüklemesi için yapılan talebe denir.
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout -b main

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch - localde bulunan kodları remote depoya gönderir.
git pull - remote depoda bulunan kodaları local depoya çeker.
git merge - branch yapılan değişiklikleri master branch ile birleştirmek veya entegre etmektir.
7. Merge conflict nedir?
Kod çakışmasıdır.
8. Merge conflict'i nasıl çözeriz?
Çakışma sırasında manuel müdahale ile devam etmek istediğimiz kodu seçerek ilerleriz.