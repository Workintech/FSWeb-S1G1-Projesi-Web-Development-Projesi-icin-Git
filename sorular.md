## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
c-1. Git, yazılım geliştirme süreçlerinde kullanılan, hız odaklı, dağıtık çalışan bir sürüm kontrol ve kaynak kod yönetim sistemidir.
2. Git ile GitHub arasında ne fark var?
c-2. Bir de projeyi birden fazla kişi yapıyorsa bu yapılanlar nasıl birleştirilecek diye düşünürsek Git bu konuda hayatımızı ciddi anlamda kolaylaştırmıştır. Github ise projelerimizin saklandığı (depolandığı) uzak sunucudur.
3. Neden bir branch oluşturuyoruz? 
Branch oluşturmak kullanıcıya çalıştığı projenin farklı versiyonlarına erişmesini sağlar. Kullanıcı, projesine bir yenilik eklemek istediğinde, yaptığı değişiklik projenin çalışmasını olumsuz etkileyebilir. Bu gibi durumlarda projemizin o anki halini bozmamak için branch kullanabiliriz.
4. Pull Request'in amacı nedir?
c-4.Pull request talebi, temelde branch'dan sorumlu kişiden kodunuzu eklemesini istemektir. Ayrıca o kişinin kodda tam olarak neyi değiştirdiğinizi görmesine de yardımcı olur.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
c-5. git checkout main
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
c-6.
git fetch, “yerel depomu uzaktaki deponun içeriğine güncelle” anlamına gelir.
Pull, bir deponun yerel sürümünü remote olarak güncellemek için kullanılan bir git komutudur. Varsayılan olarak, git pull geçerli yerel çalışma branch’ını (o an için kullanılan branch’ı) günceller ve diğer tüm branch’lar için remote-tracking branch’larını (uzaktan takip branch’ları) günceller.
Merge, git'in çatallanmış bir geçmişi tekrar bir araya getirme yoludur. git merge komutu, git branch tarafından oluşturulan bağımsız geliştirme satırlarını almanızı ve bunları tek bir branch'ta birleştirmenizi sağlar.
7. Merge conflict nedir?
İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır. Bu durumda çakışma yaşayan kişi gerekirse ekipteki diğer kişi ile beraber oturup çakışmayı çözdükten sonra merge işlemine devam etmelidir
8. Merge conflict'i nasıl çözeriz?
Bu durumda çakışma olan dosyayı elle düzeltmemiz gerekiyor. Herhangi bir editör hatta Notepad ile bile bunu yapabiliriz. Genellikle çakışmanın sebebi iş arkadaşınızla aynı satır üzerinde değişiklikler yapmanızdır. Hangi değişikliği seçeceğinize karar veremiyorsanız elbette bunu iş arkadaşınızla tartışmanız gerekir. Çakışmayı giderdikten sonra bunu git’e de bildirmeniz gerekiyor. Bunun için özel bir komut yok.