# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Source kodumuzdaki yani repositorymizdeki yapılan değişiklikleri takip etmek ve öğrenmek için kullanılan bir kontrol sistemi.  
2. Git ile GitHub arasında ne fark var?
Git indirdiğimiz yazılım dosyaları bilgisayarımızda yerel olarak kaydetmemizi sağlayan tool developerdır. GitHub ise, bilgisayarda Git tool'u ile çalıştırılan kodlarımızı online'a push etmeye ve orda tutmaya yarayan çevrimiçi servistir. 
3. Neden bir branch oluşturuyoruz?
Default olarak oluşturulan main branchinde değişiklik yapmak projede sorunlar ve karışıklık yaratabileceğinden, kodda yapılacak değişiklikleri takip ve uygulama konusunda sağlayacağı kolaylıktan dolayı farklı bir branch oluştururuz.
4. Pull Request'in amacı nedir?
GitHubdaki Repositoryde çalıştığın/değiştirdiğin/pushladığın kodlardan  diğer proje arkadaşlarını haberdar etmek amacıdır.   
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
Branch arasında değitim yapmak için Switch komutunu kullanırız.Yukarıdaki verilen branchten main branchine gitmek için şunu yapardım:
branch@change /c/git/github ('isim-soyisim')
$ git branch -a
* isim-soyisim
main
isim-soyisim

branch@change /c/git/github (isim-soyisim)
$ git branch main
branch@change /c/git/github (main)

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch: yerel repository'ye uzak repositorydeki yeni yapalın değşiklikleri haber veren komuttur.


7. Merge conflict nedir?

8. Merge conflict'i nasıl çözeriz?
