# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?x  
Git yazılım geliştirme süreçlerinde kullanılan açık kaynak kodlu versiyon kontrol sistemidir.
2. Git ile GitHub arasında ne fark var?
Yazılım projeleri için git tabanlı çalışan kar amaçlı cloud depolama hizmeti.
3. Neden bir branch oluşturuyoruz?
Mevcut projeyi aksatmadan, yeni bir geliştirme yapmak ya da ek bir özellik eklemek amacıyla ana proje akışından ayrı şekilde geliştirme yapmak için
4. Pull Request'in amacı nedir?
Branch'te yapılan değişikliklerin master projeye aktarılması için talep gönderilmesidir. Bu talep ile proje üzerinde çalışan herkesin değişiklik hakkında bilgilendirilmesi ve kişilerin incelemesine olanak sağlaması amaçlanır.
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
"git branch" komutu ile tüm branchleri listler, sonrasında main branch'e geçmek için "git checkout main" komutunu yazarım. 

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
Git pull remote repodaki değişiklikleri çalışma dizinine kopyalarken, git fetch bu değişiklikleri local reponuza kopyalar ve zamanı geldiğinde git merge ile local repodaki değişiklikleri çalışma dizinine aktarırsınız.

7. Merge conflict nedir?
Merge conflict birden fazla branch'in merge edilmesi esnasında bu branch'lerin bir dosyadaki aynı satırlarda değişiklik yapması ya da bir branch'de silinen bir dosya diğer branch'de düzenllenmesiyle ortaya çıkar.

8. Merge conflict'i nasıl çözeriz?
Çözmek için conflict veren iki branch local repoda hatalardan ayıklanacak şekilde editlenir ve güncel değişiklikler remote repoya push edilir.