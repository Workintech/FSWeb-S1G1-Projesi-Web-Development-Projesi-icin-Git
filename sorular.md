## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
	Versiyon kontrol sistemi. Bir kodun önceki versiyonlarını korumak ve daha sonra da görüntüleyebilmek için oluşturulmuş bir sistem.
2. Git ile GitHub arasında ne fark var?
	Git sistemin kendisi iken, GitHub kodların depolandığı yerdir.
3. Neden bir branch oluşturuyoruz?
	Main'i koruyarak kod içinde değişiklikler deneyebilmek için.
4. Pull Request'in amacı nedir?
	Branch'lar arasındaki farklılıkları görüntülemek.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
	git checkout main
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
	git fetch: Remote repo üzerindeki değişiklikler ile lokaldeki değişiklikleri karşılaştırmak için kullanılır.
	git merge: İki branch'ı birleştirmek için kullanılır.
	git pull: Bir deponun remote versiyonunu güncellemek için kullanılır.
7. Merge conflict nedir?
	Merge edilen iki branch'ın birbiriyle çelişen kodlar içermesidir.
8. Merge conflict'i nasıl çözeriz?
	İki branchtan birini tercih etmek gerekir.
