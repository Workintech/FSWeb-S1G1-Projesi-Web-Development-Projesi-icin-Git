# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Bir proje uzerinde birden fazla developerin calismasina imkan veren acik kaynakli bir versiyon kontrol sistemidir.
2. Git ile GitHub arasında ne fark var?
GitHub, Git uzerinde calisilan projenin serverda depolandigi yerdir.
3. Neden bir branch oluşturuyoruz?
Projeye eklenmek istenen degisikligin tam verimle calistigindan emin olana kadar masteri korumak icin branch acip deneme yapilir.
4. Pull Request'in amacı nedir?
Proje uzerinde yapilan degisikligi haber vermektir.
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout master
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu komutlar ne yapar açıklayınız.
git fetch: remoteda yapilan degisiklikleri lokal bilgisayara yukler
git merge: yapilan guncellemeleri main branche ekler
git pull: bu iki kodun kombinasyonu gibi calisir, yapilan degisikligi yukler ve projeyle birlestirir
7. Merge conflict nedir?
Projenin ayni satirinda birden fazla developer tarafindan degisiklik yapildiginda ortaya cikan cakismadir.
8. Merge conflict'i nasıl çözeriz?
Cakismanin bulundugu satiri bulup her iki degisikligi kombine ederek duzeltebiliriz.
