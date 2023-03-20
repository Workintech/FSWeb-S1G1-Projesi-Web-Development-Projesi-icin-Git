# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Git, temel olarak versiyon kontrol sistemidir. Git sayesinde, yazılım geliştirme süreçlerinde versiyonların kopyaları alınarak, gruplar arası sistemli bir çalışma yürütülebilir. 
2. Git ile GitHub arasında ne fark var?
Git, lokal olarak çalışan versiyon kontrol sistemi ve terminaldir. Github ise gitleri çevrimiçi paylaşmaya ve proje düzenlemeye yarayan çevrimiçi hizmettir.
3. Neden bir branch oluşturuyoruz?
Branch oluşturmanın amacı, geliştirilen projenin ana kodunu değiştirmeden değişiklikler yapmak ve sonrasında uygun olursa bu değişiklikleri tekrardan ana kodla birleştirmektir. 
4. Pull Request'in amacı nedir?
Pull request'in amacı, fork edildikten sonra local olarak değişiklik yapılan dosyayı tekrardan proje sahibine birleştirmesi ve onaylaması için geri göndermektir.
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout main 
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git pull ile origindeki kodlar locale çekilir ve otomatik olarak merge edilir, git fetch ile ise sadece origindeki kodlar çekilir ancak merge edilmez. Anladığım kadarıyla git merge temel olarak git pull ile aynı sonuca varıyor, yani localdeki kodu origin ile birleştiriyor.
7. Merge conflict nedir?
iki veya daha fazla geliştirici aynı dosyada aynı satırı değiştirirse ve git merge edemezse, merge conflict ortaya çıkar
8. Merge conflict'i nasıl çözeriz?
Dosyada çakışan satırların teşhis edilip düzeltilmesi gerekir. git status ile hangi branchte olduğumuzu görürüz, conflict olan satırlar düzenlendikten sonra commit edilir. 