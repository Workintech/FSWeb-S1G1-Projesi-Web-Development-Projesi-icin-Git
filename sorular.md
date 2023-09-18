# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
    Projeleri yönetmek,yapılmış olan projeleri izlemek ve geçmiş sürümlere geri dönmek gibi işlevlerde kullanılan bir yazılımdır. 
2. Git ile GitHub arasında ne fark var?
    Git, projenin bir kopyasını oluşturduğumuz, yerel bilgisayarımızda değişiklikleri izlediğimiz,kaydettiğimiz ve geçmiş sürümlere erişim sağlayan GitHub ise git tabanlı projelerin uzak sunucularda barındırılmasını , işbirliği yapılmasını kolaylaştıran bir web tabanlı platfomdur.
3. Neden bir branch oluşturuyoruz?
    Sunucuda bulunan ana kodların üzerine yapılan değişimlerin herhangi bir hataya sebep olmaması için branch oluştururuz. 
4. Pull Request'in amacı nedir?
    Açık kaynaklı bir projeye katkıda bulunmak isteyen bir kişinin, proje sahibine yaptığı değişiklikleri inceletmek için yaptığı taleptir.
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
    git checkout main

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
    Git fetch: Uzaktaki bir deponun dosyalarını, anlık görüntülerini yerel depoya indiren komut.
    Git merge: Bir branch'deki diğişiklikleri kendi çalıştığımız branch'e entegre etme işlemi.
    Git pull: Ana proje dosyasındaki değişiklikleri kendi bilgisayarımızdaki versiyona çekmemizi sağlar.
    Farklılıklar: Git fetch, uzak depodan güncellemeleri çeker ancak yerel kodunuzu güncellemez; git merge, dallardaki değişiklikleri birleştirir; git pull, uzak depodan güncellemeleri çeker ve yerel kodunuzu günceller.
7. Merge conflict nedir?
 Master kodlardan bağımsız oluşturulan yedek kodlar üzerinde çalışılıp tekrar sisteme entegre edilmesine denir.
8. Merge conflict'i nasıl çözeriz?
    Merge conflict'i çözmek için, çakışan değişiklikleri elle düzenleyerek ve ardından düzeltilen dosyayı kaydedip commitleyerek Git'e çözümü işaretlemeniz ve birleştirme işlemine devam etmemiz gerekmektedir.