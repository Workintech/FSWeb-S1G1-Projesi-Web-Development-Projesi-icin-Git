## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
Açık kaynak dağıtılmış sürüm kontrol sistemidir.
2. Git ile GitHub arasında ne fark var?
Git projeleri birden fazla kişi yapıyorsa , kişiler arası etkileşim ya da kodlar üzerinde yapılan değişikliklere izin veren bir kontrol sistemidir.GitHub ise projelerin saklandığı uzak sunucudur.
3. Neden bir branch oluşturuyoruz? 
Üzerinde çalışılan kaynak kodun bir kopyasını oluşturarak geliştirmelerin orijinal koddan bağımsız olarak ilerlemesini sağlayabilmek amacıyla branch oluşturuyoruz.
4. Pull Request'in amacı nedir?
Pull Request;Branch'dan sorumlu kişiden kodu eklemesini istemektir. Ayrıca o kişinin kodda tam olarak neyi değiştirdiğinizi görmemize de yardımcı olur
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
git checkout 'mainbranch'
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
Git fetch:Kodu uzak depodan yerel depoya çeken bir komuttur.Uzak bir depoda yapılan değişiklikleri çakışma yaratmadan geri yükler. Git Merge:Uzak depoda yakın zamanda yapılan değişiklikleri indiren ve bunları yerel bir depoda birleştiren bir komuttur.Uzak depoda yapılan değişiklikleri kaydeder ve bunları birleştirir, bu da çakışmalar yaratır.Git Pull :Git pull komutu, git fetch ve git merge komutlarının amacına tek bir komutta hizmet eden bir komuttur.Git fetch komutu sadece gerekli verileri uzaktaki depodan yerel deponuza getirirken, git pull komutu git fetch ile aynı işlevi yerine getirmenin yanı sıra aynı verileri çalıştığınız çalışma alanına getirir.Git fetch komutunda veriler sadece indirilirken, git pull komutunda veriler indirilir ve yerel deponuzda yüklemeler yapılır.Git fetch komutu veriyi getirme işlevini yerine getirirken, git pull komutu veriyi getirme ve birleştirme işlevini yerine getirir.Git fetch komutu yalnızca komut satırı sözdizimine sahipken, git pull komutu komut satırı sözdizimine ve değişiklikleri göndermek için çekme isteğine sahiptir. Uzak depodaki orijinal içeriği etkilemeden yapılabilecek değişiklikleri kontrol etmek veya gözden geçirmek istediğimizde, bu amaçla git fetch komutunu uygulayabiliriz.Ancak uzaktaki deponun en son taahhütlerini yerel depomuzun taahhütleriyle birleştirmek istiyorsak, bu amaçla git pull komutunu kullanabiliriz.
7. Merge conflict nedir?
 İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse meydana gelecek olan çakışma problemidir. 

8. Merge conflict'i nasıl çözeriz?
git status ile çözüebilir.
