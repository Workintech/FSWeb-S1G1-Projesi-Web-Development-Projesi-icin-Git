# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
	Cevap: Git, Açık Kaynak Dağıtılmış Sürüm Kontrol Sistemi(Open Source Distributed Version Control System)'dir.Buradaki terimleri açıklayayım.

	Açık kaynak:Orijinal kaynak kodlar herkes tarafından görülebilir ve gerekirse değiştirilebilir.
	kontrol sistemi: Buradan git'in kodları depolamak için kullanıldığını çıkarabiliriz.
	Sürüm kontrol sistemi : Kullanıcıların yaptığı değişiklikler kayıt altına alınır.Bu değişiklikleri kimin ne zaman yaptığını görüntüleyebiliriz.
	Dağıtılmış: Codes can be distributed from remote to local!

2. Git ile GitHub arasında ne fark var?

3. Neden bir branch oluşturuyoruz?
	Bir projede çalışırken yapacağımız işi projenin diğer kısımlarından ayırıp daha rahat çalışmak. Böylece diğer kısımlarda yapılan değişiklikleri görmezden gelebiliriz. Ayrıca çalıştığımız branchta ana projeye geçmeden önce testler yapabiliriz ve hata çıkarsa düzeltebiliriz. 

4. Pull Request'in amacı nedir?
	Çalıştığımız branchteki değişklikleri mergelemeden  önce pull request yapıp diğer kullanıcıların bu değişiklikleri görmelerini sağlayıp projenin yaptığımız kısmını tartışabiliriz. Gözümüzden kaçan detayları hataları veya eksiklikleri diğer kullanıcılar görüp bizi uyarabilirler.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
	Komutları açıklayalım.
	git fetch: projede değişiklik olup olmadığın bakar, diye yorumladım ben
	git pull: Değişiklikleri yerele yükler. 
	git merge: iki branchı birleştirir.

7. Merge conflict nedir?
	Merge conflicts occur when competing changes are made to the same line of a file, or when one person edits a file and another person deletes the same file
	Eğer iki farklı kişi iki farklı branchte aynı satırı değiştirmeye kalkarsa, merge conflict yaşanır.
8. Merge conflict'i nasıl çözeriz?
	"with a new commit."
	