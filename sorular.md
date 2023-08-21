# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

Git, yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol 
sistemidir. Git sayesinde yapacağınız projelerin adım adım versiyonlarının 
kopyalarını alarak daha sonra ihtiyaç duyduğunuzda aldığınız kopyalara 
yani versiyonlara kolayca dönebiliyorsunuz.

2. Git ile GitHub arasında ne fark var?

it bir versiyon kontrol sistemidir. GitHub ise bu versiyon kontrol sistemi 
ile kullandığımız projeleri depolayabildiğimiz bir portal diyebiliriz

3. Neden bir branch oluşturuyoruz?

Branch oluşturmak kullanıcıya çalıştığı projenin farklı versiyonlarına 
erişmesini sağlar. Kullanıcı, projesine bir yenilik eklemek istediğinde, 
yaptığı değişiklik projenin çalışmasını olumsuz etkileyebilir. Bu gibi 
durumlarda projemizin o anki halini bozmamak için branch kullanabiliriz 
 
4.Pull Request'in amacı nedir?

Pull request açtığınızda, proje üzerinde değişiklik yaptığınızı 
gösterirsiniz ve proje sahibinin katkınızı gözden geçirip çekmesini ve 
birleştirmesini talep edersiniz

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout komutu ile değşitirriz

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
Git Fetch ve Git Pull arasındaki temel fark, git fetch’in kaynaktan en 
yeni meta veri bilgilerini geri yüklemek için yerel git’inizi gösteren 
komut olmasıdır. Herhangi bir dosya aktarmaz. Daha çok değişikliklerin 
mevcut olup olmadığını bulmak için verileri incelemek gibidir, oysa git 
pull tüm değişiklikleri deponuza çekmekle birlikte aynı şeyi yapar

 7. Merge conflict nedir?

İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak 
merge edemezse bu durumda conflict yani çakışma olacaktır.

8. Merge conflict'i nasıl çözeriz 

çakışma yaşayan kişi gerekirse ekipteki diğer kişi ile beraber oturup 
çakışmayı çözdükten sonra merge işlemine devam etmelidir.

