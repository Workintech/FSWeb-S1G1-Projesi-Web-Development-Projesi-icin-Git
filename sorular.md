## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
Git, yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol sistemidir.
2. Git ile GitHub arasında ne fark var? 
 Git bir versiyon kontrol sistemidir. GitHub ise bu versiyon kontrol sistemi ile kullandığımız projeleri depolayabildiğimiz bir portal diyebiliriz.
3. Neden bir branch oluşturuyoruz? 
Çalıştığımız projenin farklı versiyonlarına erişmemizi sağladığı için.Mesela projeye bir yenilik eklemek istedik ama bir hata yaptığımızda projenin tamamiyle bozulmasını engellemek için.
4. Pull Request'in amacı nedir? 
proje sahibine proje üzerinde değişiklik yaptığımızı gösteririz ve proje sahibinin katkımızı gözden geçirip birleştirmesini talep ederiz.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz. 
git checkout
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız. 
Uzak depoda bulunan tüm değişiklikleri yerel çalışma dizinine birleştirmek için 'git pull' komutu kullanılır.'git fetch' yerel depomuzu uzaktaki deponun içeriğine güncelle anlamına gelir.
'git merge' başka bir branch'deki değişiklikleri üzerinde çalıştığımız kendi branch'imize entegre etme komutudur.
kısaca farklarını anlatmak gerekirse 'git pull' önce bir 'git fetch' yapar, sonrasında ise 'git merge' uygular.
7. Merge conflict nedir? 
İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda merge conflict olacaktır.
8. Merge conflict'i nasıl çözeriz?
projenin merge edilmeden önceki haline dönerek.veyahut çatışan kısımları manuel olarak kontrol edip düzelterek.
