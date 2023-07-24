# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

Git, yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol sistemidir. Git sayesinde projemizi

2. Git ile GitHub arasında ne fark var?

Git kullanım amacı itibariyle geliştiricinin uygulamasının, localde versiyon kontrolünü yapması için kullanılır. (Bir kaç komut hariç).
Github ise ekip arkadaşlarınızla birlikte geliştirme yapabileceğiniz bulut tabanlı bir servistir.

3. Neden bir branch oluşturuyoruz?

Main branch'teki kodumuza, geliştirme yaparken farklı bir branch'te çalışmamızın temel sebepleri şunlardır;
Yapılan geliştirmenin, esas projemizdeki herhangi bir alanla çakışıp projemizin patlamasını önlemek.
Kodumuzu canlıya almadan önce ekip arkadaşlarımızdan kodumuzu test etmesini istemek.
Bir ekip şeklinde aynı projenin farklı alanları üzerinde çalışabilmek.

4. Pull Request'in amacı nedir?

Bir ekip tarafından geliştirilen projelerde, yazılımcı yaptığı geliştirmeyi ana projeye eklemesi için pull request ile o projenin sahibine bir istek gönderir. Proje sahibinin yapmadsı gereken ise herhangi bir kod yazma stili izleniyorsa (airbnb, google style vb) yeni yazılan kodun buna uygun olduğundan emin olmak, hatasız çalıştığından emin olmaktır. Bu testlerden sonra yapılan geliştirme ana projeye eklenir.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

Branch değiştirmek için "git checkout" komutu kullanılır.
"git checkout main" komutu ile istenilen durum sağlanır.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

git fetch: Projenin güncel halini çeker, ancak mevcut branch'i güncellemez.
git merge: Farklı branch'lerdeki değişiklikleri birleştirmek için kullanılır.
git pull: git fetch ve git merge işlemlerini tek bir komutla yapar; projemizin güncellemeleri alır ve mevcut branch ile birleştirir.

7. Merge conflict nedir?

İki veya daha fazla branch'te aynı dosyanın aynı satırında yapılan ve birbiriyle çelişen değişiklikler, merge conflict'e sebep olur.

8. Merge conflict'i nasıl çözeriz?

Bu soruna çözüm olarak bir çok farklı yaklaşım vardır. Bunlardan biri "rebase" komutudur. rebase komutu ile A dalındaki her bir commit B dalına sanki commit işlemi B dalında yapılmış gibi yeniden yazılır. Bu sayede B dalının commit geçmişi sanki tüm değişiklikler bu dalda olmuş gibi görünür.
