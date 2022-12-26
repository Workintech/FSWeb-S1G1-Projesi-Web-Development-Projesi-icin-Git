## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
Git, versiyon kontrolü yapabilmemiz için yazılımcılar tarafından geliştirilen, geriye dönük, projenin belirli bir kısmında (başında,sonunda, tamamında farketmez) ve birçok kişi tarafından 
katkı sağlanabilen genel sistemin kendisidir. 
2. Git ile GitHub arasında ne fark var?
Git genel sisteme yani tüm bu kontrolleri, düzeltmeleri eklemeleri yapmamızı sağlayan yazılıma-sisteme verilen isimken, github ise tüm versiyonları, 
projelerimizi saklayabildiğimiz, onları görüntüleyip local olarak indirip düzeltip tekrar kullanıma sunabildiğimiz platform/portalın kendisidir.  
3. Neden bir branch oluşturuyoruz?
Temel/default olarak belirlediğimiz projemizin geliştirmelerden etkilenmesini istemiyorsak bir branch oluşturup geliştirmeden önceki kaynak kopyamızı korumamızı sağlar.
Bu sayede aslında bir nevi checkpoint oluşturmuş olup geliştirmelerden önce veya sonra bu oluşturulan branch üzerinden devam edebiliriz, bu kaynak kopya üzerinden çeşitli güncellemeler yapabiliriz. 
4. Pull Request'in amacı nedir?
Bir proje forklanır. Local editörde istenilen geliştirmeler yapılır. Ardından tekrar bu yeni kaynak bilgisayarımızdan githuba pushlanır. Projenin ana geliştiricisinin yaptığımız değişimlerden haberdar
olması için aslında bir uyarı-notification aracıdır. Proje üzerinde yaptığımız değişimleri resim, video, iş akışı gibi madde madde açıklayabiliriz. Proje oluşturucuları geliştirmeleri beğenirse mergelenip
tek bir branch üzerinden ilerlenebilir. 
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
git checkout 'branch_ismi'---git checkout 'main branch'
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch--Uzak sunucuda bulunan branch’lerin bilgisini lokalimize indirir.
git merge-- çalıştığımız branchlerin tamamlandıktan sonra tekrardan birleşip tek bir proje haline gelmesini1 sağlar.
git pull-- O an çalıştığımız yerel branchin remote olarak güncellenmesini sağlar.
7. Merge conflict nedir?
Kaynak dosya çeşitli geliştiriciler tarafından branchler halinde güncellenip tekrardan pushlanıp ana sağlayıcıya gönderilir ve tek bir proje haline gelir. Bu branchler birçok yazılımcı tarafından
mergelenip kaynak dosyaya pushlanmaya çalışıldığı için veya biri geliştirmeye devam ederken bir diğeri aynı dosyayı sildiğinde zaman zaman çakışmalar olur. 
8. Merge conflict'i nasıl çözeriz?
Çeşitli sebeplerden dolayı merge conflict olabilir.
Bir merge-conflicti çözmek için, son birleştirmede tutmak istediğimiz değişiklikleri seçmek için çakışan dosyayı Github üzerinden veya editör üzerinden manuel olarak düzenlememiz gerekir. 
