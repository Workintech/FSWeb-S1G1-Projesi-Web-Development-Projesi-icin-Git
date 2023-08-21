##Murat Can ÖZCAN

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

1. Git, yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol sistemidir.

2. GitHub, yazılım geliştiren ekiplerin aynı anda çalışabilmesini sağlayan internet tabanlı bir veri depolama alanıdır.

3. Branch, hali hazırda elimizde bulunan bir projenin kopyasını oluşturarak, ana projede bir değişiklik yapmadan yenilikler eklemek için kullanılır.

4. Pull request'in amacı, çalışılmak istenen projenin sahibine yapılan değişiklikleri inceletmek üzere talepte bulunmaktır.

5. `isim-soyisim` branch'indeyken "git checkout main" komutu ile geçiş yapabilirim.

6. `git fetch`, yerel depoyu uzaktaki deponun içeriğine göre güncellemeyi sağlar.
`git merge`, başka bir branch'deki değişiklikleri üzerinde çalışılan kendi branch'imize entegre etmemimizi sağlar.
`git pull`, proje ana dosyasında yapılan değişikliklerin bilgisayarımızdaki versiyonuna çekilmesini sağlar.

7. Merge conflict, iki kişi aynı anda aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemediğinde oluşan çakışmadır.

8. "git commit -a uygulama.txt" veya "git add uygulama.txt" ile sorun çözüme ulaştırılabilir.
