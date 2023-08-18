# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

2. Git ile GitHub arasında ne fark var?

3. Neden bir branch oluşturuyoruz?

4. Pull Request'in amacı nedir?

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

7. Merge conflict nedir?

8. Merge conflict'i nasıl çözeriz?

## Cevaplar 

1. Git, en kısa tanımıyla bir versiyon kontrol sistemidir. Versiyon kontrolü, bir projenin üzerinde farklı bilgisayarlardan, birden fazla kişinin çalışmasına ve proje üzerinde yapılan değişikliklerin eş zamanlı olarak kaydedilmesine olanak verir. Bu kaydedilme işlemi ise versiyonların, yani her yeni değişimin, detaylı bir dökümüne ulaşmayı kolaylaştırır.

2. Git bir versiyon kontrol sistemidir. Lokal olarak çalışır ve GitHub olmadan da git kullanmak mümkündür. Github ise Git repository'lerinin cloud üzerinde saklandığı online bir servistir. Github'a kayıt olmanız gereklidir ve ek fayda olarak da başka kişilerin repository'lerine erişebilir ya da kendi repository'lerinize erişmelerini ve katkı sağlamalarını isteyebilirsiniz. Online bir servistir ve offline olarak kullanabilneniz mümkün değildir.

3. Branch bir projenin farklı versiyonlarına erişmemizi sağlar. Örnek olarak projemize bir update yaptığımızda olumsuz bir durumla karşılaştığımızda önceki halini bozmamak için branch kullanırız.

4. Bir proje üzerinde değişiklik yaptığımızda ve proje sahibinin yaptığımız kısımları kontrol edip merge yapmasını talep etmek için kullanılır.

5. git checkout -b komutunu kullanarak branchler arası geçiş yapabiliriz örnek komut olarak 'git checkout -b main' komutunu yazarak main branchine geçiş yapılır.

6. git fetch local repository'i remote repository'e göre güncelleme komutudur. "git pull" komutuna benzerdir. git pull komutu ise remote repository deki değişikleri local repositoriye getirmesini söyler. git merge komutu ise başka bir branch'deki değişiklikleri üzerinde çalıştığınız kendi branch'inize entegre etme işlemidir.

7. İki farklı Branchin ve İki farklı kullanıcının aynı dosyayı ve aynı satırı değiştirirse git otomatik olarak merge edemezse bu durumda conflict(çakışma) gerçekleşir. 

8. Bunun için bazı methodlar var bakıldığı zaman manuel olarak elle tek tek kontrol edebiliriz veya "git reset --hard [commit-ID]" komutunu kullanarak yaptıklarımızı geri alabiliriz.