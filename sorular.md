# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Git ücretsiz, açık kaynak kodlu, genellikle koordinasyon amacıyla dosyalardaki değişiklikleri tarayan,
yazılım geliştirme süreç ve aşamalarında kullanılan bir kaynak kod yönetim ve sürüm kontrol sistemidir.
2. Git ile GitHub arasında ne fark var?
Git kodumuzu ve gelişim sürecini takip etmemize yardımcı olan bir versiyon kontrol sistemi iken, Github, Git repositorilerinin depolandığı
ve erişilebildiği bir bulut depolama temelli servistir.
3. Neden bir branch oluşturuyoruz?
Branchler iş akışı düzenimizi kontrol etmemize yardımcı olur. Değişikler yaparken bu değişiklikler üzerinde master koda müdahale
etmeden çalışabilmemizi sağlar. Kodumuzun doğruluğundan ve güvenilirliğinden emin olduktan sonra, merge ile master branch'e ekleme
yapmamıza, bu sayede hem organize çalışmamıza hem de hatadan kaçınmamıza yardımcı olur.
4. Pull Request'in amacı nedir?
Pull Request, yeni kodumuzu ve değişikliklerimizi repository'de ki kodla birleştirme ve diğer insanlara ne tür değişikler yapmış olduğumuzu
açıklama aşamasıdır. Projeye eklemek istediğimiz kodu paylaşmamıza yardımcı olur.
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout komutu kullanırım. git checkout main
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch lokal repository de herhangi bir değişiklik yapmadan remote repository'de değişiklikler olduğunu söyleyen komuttur.
git merge farklı branchleri bir araya getirerek birleştirmemizi sağlar.
git pull ise lokal repositoryi remote repositorye göre günceller ve güncel hale getirir. 
Yani bu durumda git pull = git fetch + git merge
7. Merge conflict nedir?
Merge etmeye çalıştığımız farklı branchlerin her ikiside aynı satır veya dosyada değişikler yapmış ise merge conflict oluşabilir.
Yani kodumuz için baz aldığımız source kodun yeni bir versiyonu başkası tarafından submit edilmişse ortaya çıkan durumdur.
8. Merge conflict'i nasıl çözeriz?
İlk olarak Merge conflict'i neyin yarattığını anlamamız gerekir. Görsel işaretleyicileri takip ederek hatanın nereden kaynaklandığını
bulabiliriz. Çakışan noktaları bulduğumuzda gerekli değişiklikleri yaparak branchleri birbiri ile çalışacak hale getirebiliriz. Bu
noktada diğer geliştiriciler ile fikir alışverişi yapmamız gerekebilir. Düzenlemeler sonrasında git add komutu ile fixi yaptığımızı
belirtebilir ve yeni bir git commit komutu ile bir merge commiti oluştururuz ve işlem sonlanmış olur.
 