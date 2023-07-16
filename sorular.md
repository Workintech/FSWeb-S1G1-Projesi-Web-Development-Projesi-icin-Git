# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Git, yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol sistemidir. Git sayesinde yapacağınız projelerin adım adım versiyonlarının kopyalarını alarak daha sonra ihtiyaç duyduğunuzda aldığınız kopyalara yani versiyonlara kolayca dönebiliyorsunuz.

2. Git ile GitHub arasında ne fark var?
Git versiyon kontrol sistemidir.Kaynak kodu geçmişimizi yönetmek için araçtır.GitHub buna ilaveten depoları barındırma hizmetidir.
3. Neden bir branch oluşturuyoruz?
Projenin bir kısmını farklı bir kisi yapmak istediginde branch açılır.Branch aynı zamanda dallanmak demektir.
4. Pull Request'in amacı nedir?
GitHub Reposunda yeni bir branch açtıktan sonra değişikliklerini bu Branch'e yaparsın ve asıl Branch'e bir pull request(merge Request'te denir aynı zamanda) oluşturursun. Bu pull request onaylandığında değişiklikleri yaptığın branch, ana Branch'e katılır ve değişiklikler ana Branch'e yansır..

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

git switch main

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch‘i herhangi bir zamanda refs/remotes/<remote>/ altındaki remote branch’inizi update etmek için kullanabilirsiniz. Bu operasyon refs/heads altındaki lokal branchleri değiştirmez. Aynı zamanda üzerinde çalıştığınız kopyayı değiştirmeden işlem yapma açısından da güvenlidir. Hatta bazı programcılar git fetch için bir cron job olulşturup periyodik bir şekilde arkaplanda fetch çalıştırabilir.git pull‘u ise local bir branchi remote versiyona güncellemek için kullanırız. Aynı zamanda diğer remote brachleri de update etmek için yararlıdır.

7. Merge conflict nedir?
Branclerin çakısmasıdır.
8. Merge conflict'i nasıl çözeriz?
