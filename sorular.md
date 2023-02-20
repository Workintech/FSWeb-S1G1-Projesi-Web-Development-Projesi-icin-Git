## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
Git, versiyon kontrol sistemidir. Ortak çalışma alanı yaratır ve çoklu değişikliklerin yapılmasını, versiyonların ve revizelerin görüntülenmesini sağlar.
2. Git ile GitHub arasında ne fark var?
Git, versiyon kontrol sistemidir, github ise bu versiyon kontrol sisteminin bir bağlantı aracıdır. Github'ı bir sosyal medya olarak düşünebiliriz. Bu platform sayesinde projeleri görebilir, forklama yapabilir, paylaşım yapabilir, pr gönderebiliriz.
3. Neden bir branch oluşturuyoruz? 
Branch oluşturmamızın sebebi, ana dosyaya ek olarak bir nevi yedeklemeler oluştururuz ve bu sayede yapacağımız değişikliklerin etkilenmemesi için bir nevi güvenlik yöntemi alırız.
4. Pull Request'in amacı nedir?
Pull Request, github üzerinde ki kullanıcıların, çözemedikleri bir kodlama da, ortak projelerde yapılacak planlamalarda gibi konularda proje üzerinde sorunu çözüp, veyatta ekleme yaptıklarında yaptıkları kodlamayı ana kullanıcıya, dosyaya iletip kodlarını versiyona yansıtmasıdır.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
branchler arası geçiş yapmak için "git checkout" komutu kullanırız. 
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
"git fetch" komutu ile ana dizinde ki değişikliklerin son halini indiririz ve görürüz fakat bu ana klasorde bir değişikliğe sebep olmaz yani versiyon farklarını görürüz. "git merge" komutu ise birden fazla kullanıcının yaptığı değişiklikleri birleştirmek için kullanılır. Yani yapılan değişiklikler anadosya da birleşir ve kullanılır hale getirilir. "git pull" ise son yapılan değişikliklerin anadosya üzerinde ki hallerini indirmek için kullanılır. Bu komut çalışırken bahsettiğimiz git fetch ve git merge komutlarını kullanır ve pull eder.
7. Merge conflict nedir?
Merge conflict, git üzerinde aynı işleme birden fazla kullanıcının işlem yapmasıyla birlikte oluşan birleştirememe problemidir. Bir yapıya birden fazla kullanıcı işlem yaptığında ve bu yüzden oluşan birleştirememe durumunu yansıtmaktadır.
8. Merge conflict'i nasıl çözeriz?
Burada ilk olarak proje yönetimi ve toplantı ile bu sorun çözülebilir. Hangi kullanıcının hangi kodları düzelteceği, nerede çalışma yapacağı belirlenerek bunun önüne geçilebilir. Bunun dışında, versiyon tarafında karşılaştığımız hatalar ile birlikte bunları temizleyebilir ve düzeltebiliriz, bu sayede merge conflict'in önüne geçmiş oluruz. 
