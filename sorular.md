# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Aynı proje üzerinde çalışan yazılımcıların asenkron ve farklı cihazlardan çalışmasını sağlayan bir tool.
2. Git ile GitHub arasında ne fark var?
Git tool, github ise cloud servisi sağlayıcısı.
3. Neden bir branch oluşturuyoruz?
Yapacağımız değişiklikler projeyi bozabileceği için branch üzerinde stabil olana kadar çalışılır.
4. Pull Request'in amacı nedir?
Pull request main branchla bizim branchimizi karşılaştırmak için yapılır.
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout -b main
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
fetch remote repoda lokal repoye göre değişiklik olup olmadığını kontrol etmek için, pull remote repodaki değişikliklerin kopyasını lokale getirmek için, merge ise lokal branchteki değişiklikleri maine geçirmek için kullanılır. 
7. Merge conflict nedir?
2 farklı branchin, bir dosyadaki aynı satıra değişiklik yapmasıyla ya da birinde dosyanın silinirken diğerinde editlenmesi dolayısıyla oluşur.
8. Merge conflict'i nasıl çözeriz?
Dosyadaki conflicti bulmak için önce "<<<<<<<" aranır. "<<<<<<<" ve "=======" arasındaki alan main branch, "=======" ve ">>>>>>>" arasında kalan alansa diğer branchin bu dosyada
yaptıkları değişiklikleri gösterir. İstedinlen değişiklik yapılır ve conflict marker olan ">>>>>>>", "=======" ve "<<<<<<<" silinir. Commitlenir.