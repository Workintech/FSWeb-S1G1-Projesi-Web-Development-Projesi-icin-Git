# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Bir versiyon kontrol sistemidir.
2. Git ile GitHub arasında ne fark var?
Git bir versiyon kontrol sistemiyken, GitHub bulut tabanlı bir git barındırma, bir depolama sistemidir.
3. Neden bir branch oluşturuyoruz?
Uzerinde calisilan kaynak kodun kopyasini olusturarak, ana kodu bozmadan calismamizi saglar. Yeni branch'imizde yaptıgimiz gelistirmelerin calistigindan emin oldugumuzda onu ana branch'imize push'lariz. Bazen de ana kodumuzu bozmadan gonul rahatligiyla denemeler yapmak icin branch olustururuz.
4. Pull Request'in amacı nedir?
Buyuk takimlarda yetkisi olmayan kisi yaptigi degisiklikleri ana branch'e push'lamasin diye kullanilir. Yaptigin degisiklikleri pull request'le, o projeyi cok iyi bilen kisiye atarsin. Bu kisi ya degisiklikleri decline eder, ya da kabul edip merge eder. 
Ayrica, pull request'te hatali olan bir seyi geri almak daha kolaydır. Bu yuzden bir projede tek developper da varsa pull request'i kullanabiliyoruz.
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
$ git checkout
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
`git fetch`: takim arkadaslarimizin kendi branch'lerinde degisiklik yapip yapmadigini bu komutla goruruz. Bu komutu girdigimizde, github'daki butun yeni commmit'lerin listesini bilgisayarimiza cekeriz. Ama bunlar otomatik merge olmaz. Sadece history bilgisini kenara kaydetmis oluruz.
`git merge`: Farkli branch'leri birlestirmeye yarar.
`git pull`: fetch ile merge'un birlesmis hali. git pull dedigimizde once fetch eder, sonra merge eder. 
7. Merge conflict nedir?
Aynı dosyanin ayni satirinda birbirinden farkli commit'ler olması durumu.
8. Merge conflict'i nasıl çözeriz?
Ikı koda da bakariz. Hangisinin dogru olacagina karar vererek onu kabul ediyoruz.
    