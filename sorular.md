## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
	* Git bir versyon kontrol sistemidir. Linus Torwalds tarafından geliştirilmiştir. Yazdığımız kodlarımızı ya da dizinlerimizde yaptığımız değişikliklerin versiyonlarını saklar.
2. Git ile GitHub arasında ne fark var?
	* GitHub, kodlarımızı uzak serverlarda topladığımız alandır. Git versyonlarımızı buraya yükleyerek takibini daha rahat bir şekilde gerçekleştirebiliriz.
3. Neden bir branch oluşturuyoruz?
	* `main` branch üzerinde muhtemel hatalara sebebiyet vermemek için bir çeşit müsvedde branch oluşturuyoruz.
4. Pull Request'in amacı nedir?
	* Yaptığımız değişikliklerin kodu gözden geçirmeleri için repo sahibine, yapılan değişikliklerin olduğu versiyon ile orijinal versiyon arasındaki farklılıkları gösterir bir bildirim gönderir.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
	* git checkout main
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu komutlar ne yapar açıklayınız.
	* `git fatch`: Remote repo üzerinde biz ortalıkta yokken yapılan değişiklikleri kontrol etmemize yarayan komuttur.
	* `git merge`: İki farklı branch üzerindeki değişiklikleri birleştirmemize yarayan komuttur.
	* `git pull`:  Bir deponun yerel sürümünü remote olarak güncellemek için kullanılan bir komuttur.
7. Merge conflict nedir?
	* Aynı branch üzerinde iki farklı merge talebi alınca git'in kafası karışıyor. 
8. Merge conflict'i nasıl çözeriz?
	* Yapılan iki değişik committen birisini seçip ilerlemek gerekiyor.
