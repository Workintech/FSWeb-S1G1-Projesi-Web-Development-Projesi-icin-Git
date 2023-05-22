Benim adım Messuddd :)

# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular ve Cevaplar

1. Git nedir?

- Geliştiricilerin bir takım halinde çalışabilmesi aynı zamanda güncel kod yapılarının paylaşılması ve locale çekilebilmesini
  sağlayan bir versiyon kontrol sistemidir. ( pull , push )

2. Git ile GitHub arasında ne fark var?

- Git kod parçacıklarını transferini sağlayan bir yapıdır yani bu versiyon kontrol sistemine bir nakliye işi diyebiliriz. Github
  ise bu kod parçacıklarının web tabanlı sunucularda tutulmasını sağlayan bir depodur yani GitHub git depolarını barındıran web tabanlı bir uygulamadır.

3. Neden bir branch oluşturuyoruz?

- Kaynak kodun geliştirilmesinin orginal koddan bağımsız olarak sağlayanabilmesi ve aynı zamamda projelerimizi dallara ayırmak için
  branch oluşturuyoruz . Başka bir branch üzerindeki bu kodu geliştirmenin sonunda testi de başarı ile sağlandıktan sonra tekrar bu kod parçacığını git repolarının varsayılan olarak tanımlandığı master branch denen yapı üzerine taşıyabiliriz.

4. Pull Request'in amacı nedir?

- Bir projede değişiklik yapılması halinde branchten sorumlu kişiden kodunuzun onaylanması ve projeye merge etmesi için yapılan
  bir yöntemdir.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main
   branch'ine geçmek istiyorsun, ne yaparsın?

- git checkout <branch_ismi> ---> Branch’ler arası geçiş yapmak istediğimizde kullandığımız komuttur ayrıca yeni bir branch
  oluşturduğumuzda doğrudan o branch’te çalışmaya başlamayız , öncelikle o branch’e geçmemiz gerekir.
- git checkout -b <branch_ismi> ---> Bu komutta ise iki işlem aynı anda yaptırılır: Yani branch oluşurulur ve oluşturulan branch’e
  geçiş yapılır.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

- git fetch ---> Uzak sunucuda bulunan branchlerin bilgisini localimize indirmemizi sağlayan komuttur.

- git merge ---> Oluşturduğumuz branchleri birleştirmek için kullanılan komuttur.

- git pull ---> Proje içerisinde master branch’den projenin en güncel halini almak için kullanılır.

7. Merge conflict nedir?

- Bir versiyon kontrol sisteminin tam manasıyla baş ağrısı olan kısımdır , conflict adı üstünde bir çakışmadır merge conflict ise
  bir projenin merge işleminden kaynaklanan çakışmalardır.
- Bu çakışmalar genellikle iki kişi aynı dosyayı veya aynı satırı değiştirse ve git otomatik olarak merge edemez ise meydana gelen
  durumdur diyebiliriz.

8. Merge conflict'i nasıl çözeriz?

- Çakışma gerçekleşmeden önce bunu önlemenin yolu üzerinden çalıştıgımız branchi sıklıkla master üzerinden rebase komutuyla  
  güncelleştirmek.
