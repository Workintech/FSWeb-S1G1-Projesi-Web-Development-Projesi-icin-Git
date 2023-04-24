# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Açık kaynak, dağıtılmış, kaynak kod yönetim sistemidir.

2. Git ile GitHub arasında ne fark var?
Git yönetim sistemiyken, GitHub, Git tabanlı çalışan yazılım projeleri için kar amaçlı cloud hizmetidir.

3. Neden bir branch oluşturuyoruz?
Elimizdeki mevcut projeye dokunmadan yapmak istediğimiz değişiklikleri yapıp bunların etkilerini görebilmek için.

4. Pull Request'in amacı nedir?
Pull request talebi, temelde branch'dan sorumlu kişiden kodunuzu eklemesini istemektir. Ayrıca o kişinin kodda tam olarak neyi değiştirdiğinizi görmesine de yardımcı olur.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout 

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch: sadece yapılan değişiklikleri remote repodan local repoya indirir.
git pull: remotettaki değişiklikleri local projeyle birleştirir.
git merge: git branch tarafından oluşturulan bağımsız geliştirme satırlarını almayı ve bunları tek bir branchte birleştirmeyi sağlar.

7. Merge conflict nedir?
Bir dosyanın aynı satırında aynı anda değişiklikler yapıldığında veya bir kişi dosyayı düzenlerken başka biri dosyayı sildiğinde birleştirme çakışmaları olur. Bu olaya merge conflict denir.

8. Merge conflict'i nasıl çözeriz?
Farklı dallardan hangi değişikliklerin yeni bir işleme dahil edileceği seçilmeli.
