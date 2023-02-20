## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
Git, açık kaynak kodlu bir versiyon kontrol sistemidir. Yazılım geliştirme sürecinde kaynak kodlarının takibini ve yönetimini kolaylaştırmak için kullanılır. 
2. Git ile GitHub arasında ne fark var?
Git ve GitHub farklı şeylerdir.Git, bir versiyon kontrol sistemi yazılımıdır.GitHub ise, Git tabanlı bir bulut tabanlı depolama ve işbirliği platformudur. GitHub, kullanıcıların Git kullanarak yaptıkları değişiklikleri çevrimiçi olarak saklamalarına, yönetmelerine ve paylaşmalarına olanak tanır. Aynı zamanda, insanlar açık kaynaklı projeler için katkıda bulunabilirler, diğer geliştiricilerle işbirliği yapabilirler ve birbirlerinin projelerine katkıda bulunabilirler.

3. Neden bir branch oluşturuyoruz? 
Bir geliştirici yeni bir özellik veya işlev eklemek istediğinde, bir branch oluşturup bir özelliği veya işlevi test edebilir. Bu şekilde, ana projeye herhangi bir olumsuz etki bırakmadan özellik veya işlevin test edilmesi ve geliştirilmesi mümkün olur.
4. Pull Request'in amacı nedir?
Pull requrest , bir değişiklik önerisinde bulunmak veya mevcut brach'ın ana projeye entegre edilmesi için diğer geliştiricilerin incelemesi veya onaylamamsını istemek için kullanılır.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
Bir branchten diğerine geçmek için kullanılan Git komutu "git checkout" komutudur. git checkout main komutuyla geçilir.
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch: Bu komut, uzak bir Git deposundan tüm değişiklikleri yerel kopyaya indirir, ancak yerel branch'leri otomatik olarak güncelleştirmez.
git merge: Bu komut, iki farklı branch'i birleştirir. Örneğin, "feature" branch'inde yaptığınız değişiklikleri "master" branch'ine eklemek istediğinizde, "git merge feature" komutunu kullanabilirsiniz.
git pull: Bu komut, "git fetch" ve "git merge" komutlarını birleştirir. Yani, uzak depodan değişiklikleri indirir (git fetch) ve ardından bu değişiklikleri yerel depoya birleştirir (git merge).
7. Merge conflict nedir?
Merge conflict (Birleştirme çakışması), Git'te birden fazla geliştiricinin aynı dosyayı veya aynı satırları değiştirdiği ve bu değişikliklerin birleştirilmeye çalışıldığı durumlarda ortaya çıkan bir durumdur.
8. Merge conflict'i nasıl çözeriz?
Kullanıcı, burada hangi değişikliği kullanmak istediğini belirleyip, dosyayı elle düzenlemeli ve sonrasında "git add" ve "git commit" komutlarını kullanarak değişikliği kaydetmelidir. Bu şekilde, merge conflict çözülmüş olur ve birleştirme işlemi tamamlanabilir.