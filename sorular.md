## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
Git, Açık Kaynak Dağıtılmış Sürüm Kontrol Sistemi(Open Source Distributed Version Control System)'dir.
2. Git ile GitHub arasında ne fark var?
Git; bir projenin bir çok kişi ile aynı anda yapılabilmesini sağlar.Github ise projelerimizin saklandığı (depolandığı) uzak sunucudur. Github’a projelerinizi ekleyebilir aynı zamanda istediğiniz public olan farklı projelere Github üzerinden erişerek projeyi bilgisayarınıza indirebilirsiniz.
3. Neden bir branch oluşturuyoruz? 
Branch oluşturmak kullanıcıya çalıştığı projenin farklı versiyonlarına erişmesini sağlar. Kullanıcı, projesine bir yenilik eklemek istediğinde, yaptığı değişiklik projenin çalışmasını olumsuz etkileyebilir. Bu gibi durumlarda projemizin o anki halini bozmamak için branch kullanabiliriz. Branch, sadece projenizi değiştirirken ya da güncellerken eski halini korumak ile kalmıyor. Projenize bir versiyon çıkarttığınız zaman her yeni versiyon için repository oluşturmak yerine her bir versiyon için farklı branchler açabilirsiniz. Böylece versiyonları bir arada kolayca takip edebilir ve erişebilirsiniz.
4. Pull Request'in amacı nedir?
Pull request talebi, temelde branch’dan sorumlu kişiden kodunuzu eklemesini istemektir. Ayrıca o kişinin kodda tam olarak neyi değiştirdiğinizi görmesine de yardımcı olur.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz. (?)

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch‘i herhangi bir zamanda refs/remotes/<remote>/ altındaki remote branch’inizi update etmek için kullanabilirsiniz. Bu operasyon refs/heads altındaki lokal branchleri değiştirmez. Aynı zamanda üzerinde çalıştığınız kopyayı değiştirmeden işlem yapma açısından da güvenlidir. Hatta bazı programcılar git fetch için bir cron job olulşturup periyodik bir şekilde arkaplanda fetch çalıştırabilir.
git pull ise local bir branchi remote versiyona güncellemek için kullanırız. Aynı zamanda diğer remote brachleri de update etmek için yararlıdır.
git merge işlemi başka bir branch'deki değişiklikleri üzerinde çalıştığınız kendi branch'inize entegre etme işlemidir. Git merge işlemi sırasında değişikliklerin çoğunu sizin için otomatik olarak entegre eder
7. Merge conflict nedir?
İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır. 
8. Merge conflict'i nasıl çözeriz?
Çakışma oluştuğunda ilk yapmanız gereken şey çakışmanın neden olduğunu anlamak olmalıdır. Örneğin takım arkadaşınız aynı dosyada sizin de değiştirdiğiniz bir satırı mı değiştirdi veya aynı dosyada bir satır mı sildi veya sizinle aynı isimli yeni bir dosya mı oluşturdu?

git status komutunu çalıştırdığınızda Git size branch'inizde entegre edilmemiş dosyalar olduğunu söyleyecektir. Bu durumda çakışma yaşayan kişi gerekirse ekipteki diğer kişi ile beraber oturup çakışmayı çözdükten sonra merge işlemine devam etmelidir.