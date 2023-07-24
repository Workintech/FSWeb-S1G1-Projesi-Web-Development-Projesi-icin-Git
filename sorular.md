# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Git açık kaynaklı sürüm kontrol sistemidir. Geliştiriciler kodlardaki değişiklikleri görebilir.

2. Git ile GitHub arasında ne fark var?
Git, geliştiricilerin kodlarındaki değişiklikleri izlemelerine olanak tanıyan bir sürüm kontrol sistemidir. GitHub, git depoları için web tabanlı bir barındırma hizmetidir.

3. Neden bir branch oluşturuyoruz?
Branch ana kodu değiştirmeden, kod üzerinde değişiklikler yapmamıza, hataları düzeltmemize ve yeni kodlar denememize olanak sağlar.

4. Pull Request'in amacı nedir?
Remote da yapılan değişiklikleri kendi projemize almamızı sağlar.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout master komutuyla main branch'e geçeriz.

6. `git fetch`, `git merge` ve `git pull` arasındaki farkları açıklayınız. Bu komutlar ne yapar açıklayınız.
"Git fetch" ve "git pull" arasındaki ana fark "git pull" uzak repodaki değişiklikleri doğrudan çalışma yerinize kopyalar, "git fetch" ise değişiklikleri görürsünüz ama sizin çalışmanıza kopyalamaz. "Git merge" başka branch de yaptığınız değişiklikleri master'a ekleyebilirsiniz. Yani "git pull" "git fetch" ve "git merge" komutlarının ikisinide yapar.

7. Merge conflict nedir?
Git'in iki farklı branch den ya commit den gelen değişiklikleri otomatik olarak birleştirmemesi sonucu oluşur.
8. Merge conflict'i nasıl çözeriz?
Merge conflict çözmek için insan müdahalesi gerekir. Sıklıkla pull request yapılmalı böylece değişiklikler görülmeli. Branch oluşturarak değişiklerimizi master'dan izole ederiz. Commit'ler açıklayıcı olmalı ve takım arkadaşlarıyla iletişim halinde olmalıyız.
