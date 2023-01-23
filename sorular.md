## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
  "Git", bir sürüm/versiyon kontrol sistemidir. Yazdığımız projeleri, bilgisayarımızda ya da harici disklerde birçok tehlike altında değil de internet üzerinde tutmamızı ve yönetmemizi sağlayan bir sistemdir.

2. Git ile GitHub arasında ne fark var?
  Basitçe aralarındaki farkı açıklamak gerekirse eğer, "Git" bir versiyon kontrol sistemidir. "GitHub" ise bu versiyon kontrol sistemi ile kullandığımız projeleri depolayabildiğimiz bir portaldır diyebiliriz. 

3. Neden bir branch oluşturuyoruz? 
  "Branch", sadece projenizi değiştirirken ya da güncellerken eski halini korumak ile kalmaz. Aynı zamanda projenize bir versiyon çıkarttığınız zaman her yeni versiyon için repository oluşturmak yerine her bir versiyon için farklı branchler açabilirsiniz. Böylece versiyonları bir arada kolayca takip edebilir ve erişebilirsiniz.  

4. Pull Request'in amacı nedir?
  "Pull Request" açıldığında proje üzerinde değişiklik yaptığınızı gösterirsiniz ve proje sahibinin katkınızı gözden geçirip çekmesini ve birleştirmesini talep edersiniz.

5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
  "git checkout" komutunu kullanıyoruz. Yeni bir branch oluşturmak istersek eğer, "git checkout -b 'YENİ BRANCH İSMİ' şeklinde ilerliyoruz. Main branch'ine geçiş yapmak istediğimizde; "git checkout main" komutunu kullanıyoruz.  

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu komutlar ne yapar açıklayınız.
  "git fetch": Başka bir sunucunun projesindeki her türlü içeriği veya veriyi yerel sisteminize indirmek için kullanılan bir komuttur.
  "git pull": Uzak depoda yapılan değişiklikleri kaydeder ve bunları birleştirir. Bu işlem de çakışmalar yaratır. "git fetch" ve "git merge" komutlarının amacına tek bir komutta hizmet eden bir komuttur. 
  Kullanıcıdan izin istemeden veya belirtmeden git fetch işlevini yerine getirir ve kullanıcıya haber vermeden değişiklikleri birleştirir, yalnızca sonuç, yani bu komutun işleminin başarılı olup olmadığı ve uyarılar vb. kullanıcı tarafından bilinir.
  "git merge": "Git" üzerinde merge işlemi başka bir branch'deki değişiklikleri üzerinde çalıştığınız kendi branch'inize entegre etme işlemidir.

7. Merge conflict nedir?
  İki kişi aynı dosyayı ve aynı satırı değiştirirse ve Git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır. 

8. Merge conflict'i nasıl çözeriz?
  Önce her bir kullanıcının çakışmanın neden olabileceğini araştırması gerekiyor. Sonra çakışma yaşayan kişiler iletişime geçmeliler. Beraber konunun üzerinde çalışıp çakışmayı çözdükten sonra merge işlemine devam edilmelidir. 
