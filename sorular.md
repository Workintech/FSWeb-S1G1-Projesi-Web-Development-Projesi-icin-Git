# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Git açık kaynaklı bir versiyon kontrol sistemi yazılımıdır
2. Git ile GitHub arasında ne fark var?
Git bir yazılım, github ise bu yazılım üzerinde yaptığımız çalışmaların kaydedildiği bir alan ve aynı zamanda bir sosyal ağdır; birden fazla kişinin aynı proje üzerinde çalışmasını sağlar.
3. Neden bir branch oluşturuyoruz?
Branch oluşturmak ana dosyadaki kodları bozmadan aldığımız farklı bir kopya üzerinden değişiklik yapmamıza izin verir; aynı zamanda birden fazla kişi aynı anda ana dosya klonları üzerinden çalışmalarını yapabilir.
4. Pull Request'in amacı nedir?
Bir branch üzerindeki değişiklikleri ana branch üzerine eklemek
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout kullanılır, main'e geçmek için git checkout main yazarım
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch komutu, uzak bir depodan tüm değişiklikleri indirir, ancak birleştirme yapmaz. git merge komutu, iki farklı branch'teki değişiklikleri birleştirir. git pull komutu ise, git fetch ve git merge komutlarını birleştirerek, uzak depodaki (remote) değişiklikleri yerel depoya (local) indirir ve bunları birleştirir.
7. Merge conflict nedir?
Git, iki farklı branch'teki değişiklikleri birleştirdiğinde, aynı dosya içindeki farklı satırlardaki değişiklikleri otomatik olarak birleştirebilir. Ancak, aynı dosya içinde aynı satırda yapılan farklı değişiklikler, otomatik olarak birleştirilemez. Bu durumda, Git bir "merge conflict" oluştuğunu belirtir ve kullanıcıya dosyayı manuel olarak düzenlemesi gerektiğini söyler.
8. Merge conflict'i nasıl çözeriz?
Manuel düzenleme gerektirir