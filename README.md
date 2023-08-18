# Web Development Projesi İçin Git Kullanımı

Yeni bir kurumda bir Full Stack Web Developer olarak işe başladığınızı hayal et. İlk gün yapacağın işlerden biri de, sorumlu olacağın projenin kodlarını kendi bilgisayarınıza almak ve bu kodların çalışacağı ortamı hazırlamak.

Sorumlu olacağın projenin kodlarını çalıştırabilmek için;

1. Tüm gerekli programları yüklemelisin.
2. Bilgisayarında yeni bir SSH key oluşturup Github hesabına eklemelisin.

Bunları yaptıysan, sana yöneticin tarafından verilen ilk görevin 'Git'e aşina olmak' projesi. Projenin detaylarını aşağıdaki görevi adımları olarak bulabilirsin.

## Görev 1:

- [x] Bu repo'yu sağ üstteki Fork butonu ile kendi hesabında bir kopyasını oluştur.
- [x] ❗**Kendi Github hesabında**❗oluşan kopya'yı aç. Bilgisayarınıza _clone_'lamak için sağ üstteki yeşil `Code` butonu ile SSH URL'i kopyala. SSH URL örneği: `git@Github.com:senin-Github-hesabin/fsweb-s1g1-projesi-web-development-projesi-icin-git`
- [x] Mac kullanıyorsan `Terminal`i, Windows kullanıyorsan `Git Bash`'de `git clone` yazdıktan sonra bu url'i yapıştırıp çalıştır. Örneğin: `git clone git@Github.com:senin-Github-hesabin/fsweb-s1g1-projesi-web-development-Projesi-icin-git`
- [x] Clone'ladığın projenin klasörüne gir. (İPUCU: `ls`komutu ile oluşan klasörün adını görebilir, `cd` komutu ile klasöre girebilirsin.)
- [x] Bir branch yarat: `git checkout -b 'isim-soyisim'`
- [x] Sorular.md dosyasındaki soruları cevapla.
- [x] Aşağıdaki adımları takip ederk;
- 1 [x] bilgisayarında değiştirdiğin dosyayı ekle (`git add dosya-adi`),
- 2 [x] commit ediniz(`git commit -m 'Yaptığın değişikliği, iki hafta sonraki unutkan haline bile hatırlatabilecek bir açıklama'`)
- 3 [x] ve Github'a push'la (`git push -u origin isim-soyisim`).
- 4 [x] Github'da Pull Request oluştur: Kendi reponun içerisinde iken, yeni geliştirme yaptığın branchden, main branche pull pull request gönder: Sağda yeni oluşturduğun branch `'isim-soyisim'`, solda ise `main` branch olduğundan emin ol. Uyarı: "merge" buton'una **basmadığına** emin ol!)

## Biten Projeyi Teslim Adımları

Verilen görevi tamamladıktan sonra [Workintech Platformu](https://app.workintech.com.tr)'nda (app.workintech.com.tr) `Sprint 1>Gün 1`'in sonundaki "`Proje Teslim: Sprint 1 Gün 1`" içeriğini açıp; Github hesabınızda oluşturduğun repo'nun adresini buraya ekle.

Eğitmenlerimiz, gün projeni kontrol edecek, gereken durumlarda sana slack üzerinden geribildirimde bulunacak.
