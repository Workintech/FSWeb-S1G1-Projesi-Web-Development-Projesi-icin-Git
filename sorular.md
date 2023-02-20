## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
Ücretsiz ve açık kaynaklı, büyük yazılımcı gruplarının bir arada çalışmasını kolaylaştıran bir versiyon kontrol sistemidir.
	
2. Git ile GitHub arasında ne fark var?
Git lokal sistem içerisinde komut istemcisi üzerinden çalışan bir sistem iken GitHub, Git programını kullanarak bulut sisteminde git repositorylerini saklamaya ve paylaşmaya yarayan bir Web servisidir. 

3. Neden bir branch oluşturuyoruz? 
Ana programı ve diğer branchleri etkilemeden program üzerinde değişiklikler yapmamızı sağlamak amacıyla branch oluştururuz.

4. Pull Request'in amacı nedir?
Branch üzerinde yaptığımız değişiklikleri yayınlamak.

5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
git checkout branchadı 
Eğer branch daha önce oluşturulmamışsa: git checkout -b branchadı

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
'git fetch' değişiklikleri lokal repoda tutar ancak branch ile birleştirmez. Yaptığımız değişiklikleri branch'e aktarmak için 'git merge' kullanırız. 
'git pull' tek işlemde 'git fetch' ve 'git merge' komutlarının birleşmiş hali olarak çalışır.

7. Merge conflict nedir?
Aynı satırlarda farklı değişiklerin yapılması üzerine branchlerin otomatik mergelenememe durumudur. 

8. Merge conflict'i nasıl çözeriz?
Merge conflict olan dosyayı bir text editor yardımı ile açar ve '<<<<<<<' conflict işaretçisini buluruz. Yapılan değişiklikleri düzenledikten (hangi değişikliğin yapılacağına ve ya birlikte yapılacaksa nasıl yapılacağına dair düzenlemeler) sonra conflict markerları siler ve dosyayı bu haliyle mergeleriz.
