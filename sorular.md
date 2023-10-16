# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

Git, bilgisayar programları veya dosyaların farklı sürümlerini saklayarak ve izleyerek işbirliği yapmayı kolaylaştıran bir sistemdir. Bu sayede birden fazla kişi aynı projede çalışabilir ve değişiklikleri izleyebilir.

2. Git ile GitHub arasında ne fark var?

Git bir sistem, github ise git depolarını cloud üzerinde barındıran bir hizmettir.

3. Neden bir branch oluşturuyoruz?

Hali hazırda çalışan/yayında olan bir proje'ye yeni bir özellik eklemek için ya da bir hatayı düzeltmek isterken güvenli bir ortam yaratmak için oluşturulur. Bu şekilde yapılacak bir hata esas projeye zarar vermez.

4. Pull Request'in amacı nedir?

Kod değişikliklerinin incelenmesi için kullanılır.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

git checkout main

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

git fetch: Güncel dosyaları local çalışma dizinine çekmek için kullanılır.
git merge: Farklı branchleri birleştirir.
git pull: Local çalışma dizinindeki branchi güncellemek için clouddan güncel verileri çeker.

7. Merge conflict nedir?

Aynı dosya veya aynı satırlarda farklı branchlerden gelen değişikliklerin çakıştığı durumdur. Git bunları otomatik olarak birleştiremediğinde ortaya çıkar.

8. Merge conflict'i nasıl çözeriz?

Yapılan değişiklikler sonrası ortaya çıkan bir conflictte hangi değişikliğin geçerli olması gerektiğine karar vermek gerekir. Gerekli düzenleme yapıldıktan sonra conflict ortadan kalkar.