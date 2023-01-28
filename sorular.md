## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
- Git, yazılım geliştirme süreçlerinde kullanılan, hız odaklı, dağıtık çalışan bir sürüm kontrol ve kaynak kod yönetim sistemidir. İlk sürümü Linux çekirdeği'nin geliştirilmesinde kullanılmak üzere 2005 yılında bizzat Linus Torvalds tarafından tasarlanıp geliştirilmiş, 2021 yılı itibarıyla %73 pazar payına ulaşmıştır.[1]

Git sürüm kontrol sistemini kullanan her bir çalışma dizini (proje), internet erişimi ya da merkezi bir depo olmaksızın tüm tarihçeyi tutan ve sürüm kontrol sisteminin tamamını içinde barındıran tam yetkili birer depodur. Ayni çalışma dizininin birçok depodan birindeki kopyasında yapılan değişiklikler diğerlerine güven temelli bir değerlendirmeyle kabul edilir; Güvenilmeyenden değişiklik alınmaz, o kendi ayrı sürümünü geliştirmeye devam eder.(kaynak; vikipedia)

2. Git ile GitHub arasında ne fark var?
- Git bir versiyon kontrol sistemidir. GitHub ise bu versiyon kontrol sistemi ile kullandığımız projeleri depolayabildiğimiz bir portal diyebiliriz

3. Neden bir branch oluşturuyoruz?
- Birden cok programlamacinin calistigi bir proje her programlamaci kendi branch'i uzerinde calisarak onerdikleri veya olusturduklari kodlarin guvenli bir sekilde butune sunabilirler. 
4. Pull Request'in amacı nedir?
- Fork ettiğimiz bir projenin üzerinde çalışıp, projede yaptığımız değişiklikleri, projenin sahibine pull request olarak gönderebiliriz. Pull request olarak göndermek demek; ben projede değişiklikleri yaptım, sen de bu bu değişiklikleri onayla ve projene merge et, ben de katkı sağlamış olayım demek. (kaynak medium.com)
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
- git checkout main komutu
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
- git pull ; calisan kisi dominene yaptigi degisiklikleri gonderir
 git merge ; domain ana depoya yapilan degislikleri ekler
  git fetch ; kulanicinin uzaktaki deposuna kayit yapma
7. Merge conflict nedir?
- 2 programcinin ayni yerde degisiklik yapmasi
8. Merge conflict'i nasıl çözeriz?
- Butun kodlar kontrol edilerek cozulur



