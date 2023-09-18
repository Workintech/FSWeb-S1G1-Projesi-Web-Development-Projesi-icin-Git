## Sorular ve Cevapları (W1D1_b-y)

1. Git nedir?
    Versiyon kontrol sistemi.

2. Git ile GitHub arasında ne fark var?
    Git konsolun ve dolayısıyla sistemin kendisi, github ise bunların depolandığı birnevi bir bulut ortamı.

3. Neden bir branch oluşturuyoruz?
    İleride olası kritik dönüş/değişiklikler üzere birnevi ana çalışmamızı/tezgahımızı koruyabilmek için.

4. Pull Request'in amacı nedir?
    Ortak çalışılan bir kod çalışmasında yapılacak olan değişiklikler üzerine toplu karar vermek.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
    git checkout main

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
    git fetch, remote bir depodaki tüm dosyaları bilgisayardaki yerel depoya indirir.
    git merge, bir branchteki çalışmaları kendi çalıştığımız branch ile birleştirir.
    git pull, uzaktaki ana depoda yapılan değişiklikleri bilgisayardaki yerel depoya geçirir, git push ile birlikte çalışırsa senkronizasyon olur.

7. Merge conflict nedir?
    Ortak bir kod çalışması üzerinde aynı satır/yer(ler)in birden fazla kişi tarafından (aynı anda) değiştirilmesi ve sistemin/konsolun bu (çakışan) değişiklikleri birleştirememesi durumu.
    
8. Merge conflict'i nasıl çözeriz?
    Çakışmanın olduğu yer için ortak çalışılan kişilerle bizzat iletişime geçilip, ortak bir yargıya varıldıktan sonra birleştirme (merge) sağlanacak.