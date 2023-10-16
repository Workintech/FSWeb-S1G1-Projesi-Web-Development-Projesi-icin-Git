# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Git, bireylere aynı dosya üzerinde aynı anda çalışma fırsatı sunan, üzerinde çalıştığımız dosyaları kontrol edebildiğimiz bir sistemdir. 
2. Git ile GitHub arasında ne fark var?
Github bir cloud zihmeti gibi çalışır. Git ile proje oluştururken, Github'da bu projelerimizi depolayabiliriz. 
3. Neden bir branch oluşturuyoruz?
Bazen bazı projelerde yeni bir şey geliştirmek uzun sürüyor ve bu süreçte var olan kodun kesintisiz çalışması için, yeni çalışacağımız konu için branch açarız. Daha sonra branch yaparak üzerinde çalıştığımız dosyayı merge ederek asıl projeye ekleyebiliriz. Bazen proje üzerinde bir deneme yapmak istediğimizde de branch oluştururuz. 
4. Pull Request'in amacı nedir?
Branch ile yaptığımız değişikliği main ya da başka bir branche eklemek için bunu yapma yetkisi olan birinden istemek. 
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
checkout 'main'
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
'git fetch' başkalarının yaptığı değişiklikleri gösterir. 'git merge' oluşturduğumuz yeni branchteki değişiklikleri ana projeye ya da başka bir branche ekleme komutudur. 'git pull' ise başkalarının yaptıkları değişiklikleri kendi localimize alma komutudur. 
7. Merge conflict nedir?
Birden fazla kişinin aynı dosyada aynı kısmı/satırı değiştirmesi ile oluşan problemdir. 
8. Merge conflict'i nasıl çözeriz?
Conflictli hali alınıp düzeltilip tekrar merge etmek gerekir, developerlar iletişim halinde olmalıdır bu tarz bir conflicti yaşamamak/çözmek için. 
