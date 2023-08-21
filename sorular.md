# Araştırma Soruları

## Sorular

1. Git nedir?

Git, bir versiyonlama sistemidir. OpenSource olmasından kaynaklı herkes tarafından erişilebilir, değiştirilebilir ve dağıtılabilir. Aynı zamanda depolama görevi de yapar. Projelerde yapılan değişiklikleri kronolojik olarak görmemizi sağlar. Bir proje yaratıldıktan sonra bütün geliştiricilerin koda eklemeler, değişiklikler yapmasına olanak tanır.

2. Git ile GitHub arasında ne fark var?

GitHub içinde git barındırma hizmeti bulunur. Bireyler ve ekipler için git kullanımını kolaylaştırır.
Bulut tabanlı bir depolama hizmeti sunar.

3. Neden bir branch oluşturuyoruz?

Kaynak kodun bir kopyasını oluşturarak orijinal koddan bağımsız bir şekilde değişiklik yapmamızı sağlar. Yapılan değişiklikler eğer hatasızsa bu değişiklikler tekrardan master branch'e taşınır

4. Pull Request'in amacı nedir?

GitHub'daki proje ana dosyasında yapılan değişikliklerin bilgisayara çekilmesini sağlar. Github'da bulutta depolanan versiyonu yerel depoda birleştirmeye yarar.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

Git checkout komutunu kullanıp istediğim branch'in ismini yazarım.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

Git fetch: Yapılan değişiklikleri gösterir ancak bunları uygulamaz.
Git merge: git branch tarafından oluşturduğumuz branchleri tek bir branch've birleştirmemizi sağlar.
Git pull: Yapılan değişiklikleri gösterir ve uygular

7. Merge conflict nedir?

Birden fazla kişinin aynı satır veya dosyayı değiştirmesi durumunda git otomatik olarak merge edemezse conflict ortaya çıkar. Conflict olmaması için her değişiklikten sonra push ve pull yapılmalı.

8. Merge conflict'i nasıl çözeriz?

Conflict yaşayan kişilerin beraber oturup conflict yaşanan bölümleri bulması gerekir. Bu conflict'ler(çakışmalar) manuel olarak düzenlendikten sonra tekrardan merge işlemi gerçekleştirilir.
