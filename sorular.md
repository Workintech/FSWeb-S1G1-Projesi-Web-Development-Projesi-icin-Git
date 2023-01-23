## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir? 
##Git bir versiyon kontrol sistemidir, kaynak kodlarinda degisiklik yapma, bunlari kayda alma gibi ozellikler sunar.
2. Git ile GitHub arasında ne fark var?
##Github git ozelliklerini kullanabildiginiz bir software gibi calisir. Githubda kodlarimizi tutabiliriz, uzak lokaller, repolar olusturabiliriz.
3. Neden bir branch oluşturuyoruz? 
##Asil kodu bozmadan uzerinde calismak icin olusturuz.
4. Pull Request'in amacı nedir?
##Yaptigimiz degisiklikleri digerlerine bildirmek ve degisikliklerin asil koda eklenmeden once uzerinde tartisip geri bildirimler almak.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
##git checkout -b main
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
##fetch: remote dosyalari, commitleri, degisitiklikleri locale indirmeye yarar. Kodun guncel halini alirsiniz. Ama localdeki agaci guncellemez/degistirmez.
merge: degisiklikleri birlestirmeye yarar
pull: once degisiklikleri indirir sonra degisiklikleri birlestirir.
7. Merge conflict nedir?
##Ayni dosyanin ayni satirinda yapilan iki farkli commit merge edilmeye calisilirsa conflict meydana gelir. Hangi commitin kabul edilecegine karar verilmelidir.
8. Merge conflict'i nasıl çözeriz?
##Conflict olusan yerde hangi kodun yer alacagina karar verilmelidir. Conflict isaretleri silindikten ve kod degistirildikten sonra tekrar commit atilir.