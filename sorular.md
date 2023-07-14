# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

Git bir projenin asamalarinin derli toplu olmasi icin yaratilmis bir sistem. Mesela bir modulun uzerinde ugrasan biri nereden yola cikmis oldugunu, diger modullerin ne durumda oldugunu, veya baska insanlarin ne durumlarda oldugunu/nelerle ugrastiklarini takip edebiliyor. Herkesin, kendi kendilerinin bile, genel resimde nerede olduklarini takip edebilmeleri icin yani. Bir bakima Hansel ve Gretel'in ekmek kirintisi birakmasi gibi

2. Git ile GitHub arasında ne fark var?

GitHub halka acik ve internet uzerinden isteyenin istedigi yerden "gitleyebilme" platformu.

3. Neden bir branch oluşturuyoruz?

Ana dosyayi degistirmeden manupile etmis oluruz, ve eger baskalarindan daha manali bir eklentimiz varsa bunu geri sokabiliriz. Ayni zamanda bir taski birden fazla dala bolup hem  bitirilme hizini, hem verimini, hem de kisi basina dusen kolayligini arttirabiliriz. 

4. Pull Request'in amacı nedir?

Aslinda oldukca sezgisel bir isimlendirme. Kendine cekiyorsun disardaki file'i. Kendini updated tutuyorsun.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

git checkout main

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

git pull 			= 	git fetch	 + 	git merge

(hem guncel dosyayi getir)		(guncel dosyayi		(guncelle)
(hem de guncelle)			 locale getir)

7. Merge conflict nedir?

Cok ne zaman nasil bir conflict olabilecegine asina degilim ama bir ornek dusuneyim:
ben main'e bir update getirmek istiyorum fakat ordaki kullandigim bazi fonksaioynlar bir baskasi tarafindan degistirilmis. Ben merge etmeye calistigimda bir conflict olusur. O zaman gidip o degistirilmis halini kullanmam gerekir. 

8. Merge conflict'i nasıl çözeriz?

Git status ile conflict olan file'lara bakiyorum. Bir de az once bir video izliyordum. Orda adam git diff diye bir sey kullanmisti. Belki o da yararli olabilir.