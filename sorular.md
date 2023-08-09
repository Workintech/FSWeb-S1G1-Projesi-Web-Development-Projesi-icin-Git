# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir? Git yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol sistemidir.

2. Git ile GitHub arasında ne fark var? Git versiyon kontrol sistemiyken GitHub ise bu versiyon kontrol sistemi ile kullandığımız projeleri depoyabildiğimiz bir portal diyebiliriz.Git bir projenin bir çok kişi ile aynı anda yapılabilmesini sağlarken GitHub ise projelerimizin saklandığı bir uzak sunucudur.

3. Neden bir branch oluşturuyoruz? Şuan bu soruya aynanda herkesin farklı cevap verebilmesi için diyebilirim ama bu kadar basit değil main den bağımsız her yazılımcının kendi partını yapıp daha büyük bir taske ulaşabilmesi birbirleriyle yardımlaşıp çalışabilmesi için branchleri oluşturuyoruz.

4. Pull Request'in amacı nedir? Aynı repository üzerinde çalıştığın insanlara yaptığın değişiklikleri göndermek, pull request açıldığında potansiyel yeni değişimleri ve yaptıklarınla alakalı mergeden önce düzenleme ve fikir alışverişi yapmak.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın? "Git checkout"(branchin adı)komutudur.git checkout "-b" ile de yeni bir branch oluşturabilirsin. İsim soy isim branchinden main branche geçmek için git checkout main yazarım.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız. Git fetch "yerel depomu uzaktaki deponun içeriğine günceller", git pull " uzaktaki deponun değişikliklerini yerel depoya getir"der git merge ise başka bir branch'deki değişiklikleri üzerinde çalıştığın kendi branchine entegre etme işlemidir tanımları birbirlerinden ayırır.

7. Merge conflict nedir? Basitçe çakışma iki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse meydana gelen durum.

8. Merge conflict'i nasıl çözeriz? Git status komutunu çalıştırıp entegre edilmemiş dosyaları tespit edip çakışan satırları düzelterek,dosyanın mergeden önceki haline git merge --abort komutuyla dönerek, daha çakışma başlamadan üzerinde çalışılan özellik dalını master üzerinden rebase komutuyla güncelleştirerek çözebiliriz.
