# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

Git, açık kaynaklı bir versiyon kontrol sistemi yazılımıdır. Yazılım geliştirme projelerinde kodların, belgelerin ve diğer dosyaların değişikliklerini takip etmek, kontrol etmek ve yönetmek için kullanılır. Git, birden fazla geliştiricinin aynı projede çalışmasını kolaylaştırmak, hataları önlemek ve verimliliği artırmak için özellikle dağıtılmış bir yapısıyla öne çıkar.

2. Git ile GitHub arasında ne fark var?

Git, bir versiyon kontrol sistemi yazılımıdır. GitHub ise, Git tabanlı bir bulut depolama ve paylaşım hizmetidir. Yani, GitHub, Git ile yapılan projelerin depolanması ve yönetimi için kullanılan bir platformdur. Git, yalnızca yerel veya sunucunuza yüklediğiniz bir yazılımdır, bu nedenle farklı kullanıcılar arasında paylaşmak için merkezi bir yer yoktur. Github ise, Git tabanlı projelerin merkezi ve bulut platformunda paylaşılmasını, yönetilmesini ve işbirliği yapılmasını kolaylaştırır. Ayrıca, Github, diğer geliştiricilerle kolay bir şekilde işbirliği yapmanızı sağlar, kod incelemesi, geri bildirim alma ve takımın projelerini kolay bir şekilde yönetebilirsiniz.

3. Neden bir branch oluşturuyoruz?

Bir branch (dal) oluşturmanın ana nedeni, bir proje üzerinde çalışırken birden fazla kişinin aynı anda proje üzerinde değişiklik yapabilmesini sağlamaktır. Özellikle büyük projelerde birden fazla kişinin aynı anda çalışması gerekebilir ve herkesin birbirinin değişikliklerine ihtiyacı olabilir. Ayrıca branch’ler, farklı özelliklerin veya hataların çözümünün izlenebilirliğini sağlar. Ayrı bir branch’te çalışarak, özellikle yeni bir özelliği veya bir hata düzeltmesini eklerken, ana kaynak kodunu etkilemeden çalışabilirsiniz. Bu sayede, değişikliklerinizi test edebilir ve gerekli tüm düzenlemeleri yapıp, ana koda merge edebilirsiniz.

4. Pull Request'in amacı nedir?

Pull Request, açık kaynaklı proje veya aynı proje üzerinde çalışan birden fazla geliştirici için bir kod inceleme mekanizmasıdır. Bu mekanizma, bir geliştiricinin yaptığı kod değişikliklerini diğer geliştiricilerle paylaşmasını ve bir inceleme sürecine tabi tutulmasını sağlar.
Pull Request’in amacı, daha iyi kod geliştirme süreçleri ve daha kaliteli kodlar yazılmasıdır. Pull Request oluşturarak, diğer geliştiricilerin görüşlerini alabilir ve geri bildirim alarak, iyileştirme yapabilirsiniz. Aynı zamanda, Pull Request sayesinde, herhangi bir sorun veya hataların hızlı bir şekilde tespit edilip çözülmesi sağlanabilir.
Ayrıca açık kaynaklı projelerde, bir Pull Request ile iletilen kod değişikliği, proje sahibi veya yöneticileri tarafından kabul edilebilir veya reddedilebilir. Kabul edilen kod değişiklikleri, projenin ana geliştirme dalına (ana branch) birleştirilir ve proje için yayınlanır.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

Git kullanarak bir Branchten diğerine geçmek için aşağıdaki git komutunu kullanabilirsiniz:

git checkout <branch-adı>

Burada <branch-adı> öğesine geçmek istediğiniz hedef branchin adını yazmanız yeterlidir. Örneğin, eğer “yusuf-colak” adındaki bir branchten “master” branchine geçmek istiyorsanız şu komutu kullanabilirsiniz:
git checkout master

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

git fetch, git merge ve git pull tümü git kullanarak uzak bir depodan (remote repository) verileri almak için kullanılan komutlardır. İşlevleri farklı olmakla birlikte, hepsi bir projenin farklı kopyaları arasındaki farkları birleştirmeye yarar. Aşağıda bu komutların ne yaptığını kısaca açıklayalım:



-->>  `git fetch`: Bu komut, uzak bir depoyu günceller, ancak bu deponun son sürümünü yerel bir kopyanızla birleştirmez. Yani, yerel depoda herhangi bir değişiklik olmaz. git fetch kullanarak, uzak depodaki değişiklikleri görebilirsiniz ve isterseniz sonraki birleştirme işlemi için hazırlık yapabilirsiniz.


-->>  `git merge`: Bu komut, farklı iki branch veya commit geçmişlerini birleştirmek için kullanılır. Yani, git merge yaparak, bir branchtaki değişiklikleri başka bir branchle birleştirebilirsiniz. Bu şekilde farklı iş yapılan branchler arasında ortak bir paydada buluşmanız daha kolay olacaktır.


-->>  `git pull`: Bu komut, uzak bir depoyu güncelleyip, yerel kopyanızda birleştirme işlemini otomatikleştirir. Yani, git pull, git fetch komutu ile aynı işlemi yaptıktan sonra otomatik olarak git merge komutunu da çalıştırır. Bu sayede tek bir komutla güncelleme işlemini tamamlayabilirsiniz.


Özetle, git fetch ile uzak depodan güncelleme yapabilirsiniz, git merge ile farklı branchleri ya da commit geçmişlerini birleştirebilirsiniz, git pull ile de hem güncelleme hem de birleştirme işlemini tek bir komutla gerçekleştirebilirsiniz.

7. Merge conflict nedir?

Merge conflict (birleştirme çakışması), aynı dosyaların farklı branch’lerde değiştirilmesi sonucu ortaya çıkan bir durumdur. Genellikle, iki veya daha fazla kişi aynı dosyada (örneğin bir dosyada veya bir kod bloğunda) değişiklik yaparken aynı satırları düzenler veya değiştirirse bir merge conflict yaşanır.
Bir merge conflict durumunda, git otomatik birleştirme yapamayacaktır ve manuel birleştirme yapmanız gerekecektir. Bu durumda, git farklılıkları gösterir ve değiştirilmiş tüm satırları karşılaştırmanızı ve bir karar vermenizi gerektirir.

8. Merge conflict'i nasıl çözeriz?

Merge conflict’ler çözülmek için genellikle şu adımlar izlenir:

1- Git hesabınıza veya yerel depoya bağlı olarak, değişiklikleri almak için git fetch veya git pull kullanarak öncelikle en son güncellemeleri alın.

2- Branch’lerinizi birleştirin. git merge veya git rebase komutları bu işlem için kullanılabilir. Aynı dosyaların farklı branch’lerde değiştirildiği durumlarda, git size bir hata mesajı verir ve birleştirme çakışması çözmeniz gerektiğini bildirir.

3- Çakışma (conflict) çözümleme aracını açın (birçok kod editörü ve git istemcisi bu araçları sağlar). Çakışmaları çözmek için bu araçları kullanarak farklı değişiklikleri gözden geçirin ve karşılaştırın.

4- Çakışmanın nasıl çözüleceğine karar verin. Bu durumda, size sunulan değişiklikler arasından tercih ettiğinize karar verin veya düzenleme yapın. Değişikliklerinizi kaydedin.

5- Değişiklikleri doğrulayın ve kaydedin. Dosyayı kaydedin ve bir mesajla birlikte git’e gönderin ( commit and push ).