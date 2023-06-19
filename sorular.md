# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

Git, Açık Kaynak Dağıtılmış Sürüm Kontrol Sistemi olarak tanımlanır. Bu tanımı parça parça incelersek:
-Açık Kaynak: orijinal kaynak kodlarının herkes tarafından erişilebilir ve değiştirilebilir hale getiren yazılım türü
-Kontrol Sistemi: depolama özelliği (içerik izleyici)
-Sürüm Kontrol Sistemi: güncellemeleri kronolojik olarak kayıt altına alan sistem
-Dağıtılmış Sürüm Kontrol Sistemi: merkezi sunucuda depolanan remote sürüm ve geliştiricelirn bilgisayarında depolanan tam kopya, yerel bir sürüm

2. Git ile GitHub arasında ne fark var?

GitHub, bulut tabanlı git'i içinde barındıran kar amaçlı bir şirkettir. 

3. Neden bir branch oluşturuyoruz?

Çoktan çalışan ve kullanımda olan bir projede değişiklik yapmak veya bu projeye yeni bir özellik eklemek/çıkarmak istendiğinde çalışan kodun bozulmaması ve kullanılmaya devam etmesi için orijinali dokunulmadan durur. Program aynen bir branch'e kopyalanır ve tüm değişiklikler ve testler bu branch'te yapılır.

4. Pull Request'in amacı nedir?

Remote repo'ya sunulan/önerilen değişiklikler. Bu değişiklikler repo'nun diğer kullanıcıları tarafından kabul edilebilir veya reddedilebilir.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

git checkout main

6. `git fetch`, `git merge` ve `git pull` arasındaki farkları açıklayınız. Bu komutlar ne yapar açıklayınız.

-git fetch: remote repo'dan local branch'e "commit etmeden" değişiklik çekmek. pull'dan farkı: fetch değişiklikleri local'a commit etmeden önce gözden geçirmemize izin veriyor
-git merge: branch'teki değişiklikler tamamlanınca ve kod test sürecini geçince bu yenilikleri orijinal kodla birleştirme işlemi
-git pull: bir developer'ın kendi local'ından remote repo'ya push'ladığı commit'leri diğer developer aynı remote repo'dan kendi local projesine çekmek için kullanır

7. Merge conflict nedir?

Merge edilmiş birden fazla branch arasındaki farklılıktan kaynaklanan çakışma. Eğer aynı satırda veya aynı dosyada farklı değişiklikler yapılırsa veya biri bir dosyayı düzenlerken diğeri silerse meydana gelir.

8. Merge conflict'i nasıl çözeriz?

-Aynı satırda farklı değişiklikler: önce repo'muza gidip (cd [repository-name]) nerede conflict olduğunu öğreniyoruz (git status)
Conflict marker'ı (<<<<<<<) kodumuzda aratıyoruz. Conflict uyarısı kod içinde şu şekilde gözüküyor:
If you have questions, please
<<<<<<< HEAD
open an issue
=======
ask your question in IRC.
>>>>>>> branch-a

Base branch'te yazan kısım HEAD ile ======= arasında. ======= ile >>>>>>> arasındaki kısım diğer bir branch'te yapılan değişiklik.
Son halinin ne olmasını istiyorsak (birini seçebilir veya iki değişikliği birleştirebiliriz) tüm conflict marker'ları silip istediğimiz şeyi yazıyoruz.
Son olarak değişiklikleri stage'lemek (git add .) ve commit'lemek (git commit -m ""Resolved merge conflict") gerekli.

-Silinen dosyalar: önce repo'muza gidip (cd [repository-name]) nerede conflict olduğunu öğreniyoruz (git status)
Eğer silinmesi hataysa ve geri yüklemek istiyorsak: git add [dosya-adi]
Eğer silinmesini istiyorsak: git rm [dosya-adi]