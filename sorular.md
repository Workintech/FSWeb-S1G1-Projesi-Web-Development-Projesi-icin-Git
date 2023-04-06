# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

2. Git ile GitHub arasında ne fark var?

3. Neden bir branch oluşturuyoruz?

4. Pull Request'in amacı nedir?

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

7. Merge conflict nedir?

8. Merge conflict'i nasıl çözeriz?

  CEVAPLAR

1- Git kısaca bir döküman  üzerinde yaptığınız değişiklikleri adım adım izleyen, istediğinizde kayıt eden ve isterseniz bunu internet üzerindeki bir bilgisayarda veya yerel bir cihazda  saklamanızı ve yönetmenizi sağlayan bir sistemdir.

2- Git, açık kaynaklı bir sürüm kontrol sistemidir ve Github, Git deposu için bir barındırma hizmetidir.

3-Branchler projelerimizi dallara ayırmamızı sağlarlar. Örnek vermemiz gerekirse; projemize yeni bir özellik eklemek istiyoruz ama bu özelliğin kodumuzu bozma tehlikesi var o anda hemen imdadımıza "branchler" yetişiyor. Yani projemizin o anki haline bir şey olmadan geliştirmeye devam etmek ama bir yandan da diğer özelliği geliştirip denemek istiyoruz ve bunun için branch kullanıyoruz.

4-Fork ettiğimiz bir projenin üzerinde çalışıp, projede yaptığımız değişiklikleri, projenin sahibine pull request olarak gönderebiliriz. Yani ben projede değişiklikleri yaptım,sen de bu bu değişiklikleri onayla ve projene merge et, ben de katkı sağlamış olayım demek.

5- git checkout: Branch’ler arası veya commit'ler arası geçiş yapmak istediğimizde kullanılır. Şuan ki branch  "*Git (okyanus-aydogan)*"

diğer branch e geçmek için : "git checkout main" ve artık biz "main" branch inde oluruz.

6- git fetch: Kodu uzak depodan yerel depoya çeken bir komut.

​    git  pull: Uzak depoda yakın zamanda yapılan değişiklikleri indiren ve bunları yerel bir depoda birleştiren bir komut.

​    git merge: Git’de yaptığımız merge işlemi başka bir branch’deki değişiklikleri üzerinde çalıştığınız kendi branch’inize entegre etme         					 işlemi diyebiliriz.

7- Merge Conflict: İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak  merge edemezse bu durumda çakışma olacak. Biz buna merge conflict diyoruz. 

8- Çakışma yaşadığımız zaman sıkıntılı Git bize çakışma yaşadığımız değişiklikleri  gösterir ama Meld adlı bir uygulama ile bu hataları daha iyi görebiliriz. Hataları gördükten sonra "vim" kullanıp sıkıntılı olan yerleri düzeltiyoruz. Daha sonra "git add .....(dosya ismi)" komutunu kullanıyoruz. Yaptığımız kodu lokalimiz de saklamak için "git commit" komutunu ---> git commit -m "merge conflict düzeltildi"

Bir git deposunda veya herhangi bir versiyon kontrol sisteminde sürekli aynı dosyayı değiştirirsek  çakışma sürekli karşımıza çıkacaktır. Bunu yüzlerce kod yazan bir dosyada düşünürsek bizim için çok kötü bir duruma dönüşecektir. Bu durumu göze alarak dikkat etmeliyiz. 

