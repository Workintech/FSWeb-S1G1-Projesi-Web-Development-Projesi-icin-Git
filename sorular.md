## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz.

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?

Git için kısaca versiyon kontrol sistemi diyebiliriz. Böylece bir proje üzerinde çalışırken yapılan değişiklikleri kaybetmeyip kopyalarını oluşturabiliriz. Daha sonra bir hatayla karşılaştığımızda bu kopyalara geri dönerek projenin daha sorunsuz bir şekilde ilerlemesini sağlarız.

2. Git ile GitHub arasında ne fark var?

Git açık kaynaklı bir versiyon kontrol sistemi olup birden fazla kişinin bir dosya/proje üzerinde çalışmasını sağlarken GitHub'ı bu projenin saklandığı veya depolandığı uzak sunucu olarak düşünebiliriz. Git local sistemimizde bulunurken, Github bulut tabanlı olup internet üzerinden erişim sağlanmaktadır.

3. Neden bir branch oluşturuyoruz?

Projenin asıl dosyası üzerinde değişiklikler yapmak yerine, farklı bir branch oluşturup bu değişiklikleri bu branch üzerinde deneyebiliriz. Böylece main branch'i bozmamış, ve olası bir hatayı bu main dosyayı bozmadan oluşturduğumuz diğer branch üzerinde görmüş oluruz.

4. Pull Request'in amacı nedir?

Bize ait olmayan bir proje üzerinde değişiklik yaptığımızda, projenin sahibine bu değişiklikleri pull request yaparak gönderebiliriz. Eğer projenin sahibi bu değişiklikleri onaylarsa merge etmiş olup, bizim yaptığımız değişiklikler asıl projeye eklenmiş olur.

5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.

Öncelikle hangi branchte çalıştığımızı görmek için <i>git branch</i> komutunu kullanabiliriz. Daha sonra eğer main branch'e geçeceksek <i>git checkout main</i> metodunu kullanabiliriz.

6. `git fetch`, `git merge` ve `git pull` arasındaki farkları açıklayınız. Bu komutlar ne yapar açıklayınız.

<i>git fetch</i>'i projede başkaları tarafından yapılan değişiklikleri sorgulatma şeklinde düşünebiliriz. Bu aşamada herhangi bir dosya aktarımı yoktur, sadece ilgili dosyaları uzak depodan local'e çekmişizdir ama henüz birleştirme yoktur. <br>
<i>git merge</i> farklı branchler üzerinde çalışırken bu branchleri birleştirme/entegre etme komutudur. <br>
<i>git pull</i> ise aslında hem git fetch hem de git merge metodlarının birleştirilmiş halidir. Projede yapılan değişiklikleri sorgulayıp daha sonra direkt dosyalarınız üzerine bu değişiklikleri ekler. Çoklu kişiden oluşan projelerde riskli bir komut olabilir, o yüzden ilk başta <i>git fetch</i> yapıp değişiklere göz atmak faydalı olacaktır. Ama eğer tek kişi proje üzerinde çalışıyorsa <i>git pull</i> komutuyla tüm verileri yerel depoya indirmek sağlanabilir.

7. Merge conflict nedir?

Merge conflict; birden fazla kişi, aynı dosyada aynı satırı değiştirmeye çalıştığında ya da biri o dosyayı silmişken diğer(ler)inin düzenleme yaptığı gibi durumlarda oluşan çakışmalardır. Bu durumda git, merge işlemi(birleştirme işlemi) yapamaz, bir nevi hangisini merge edeceğini bilemediği için hata verir.

8. Merge conflict'i nasıl çözeriz?

Böyle bir durumda, öncelikle çakışmanın nereden kaynaklandığı incelenmelidir ve hangi değişikliğin kabul edilmesi gerektiği düşünülmelidir. Eğer hangi değişikliğin uygulanacağı konusunda hala bir tereddüt varsa, burada takımla veya conflict yaşanan kişiyle konuşulup ortak kanıya varılabilir.

\*git stash ve git rebase?
