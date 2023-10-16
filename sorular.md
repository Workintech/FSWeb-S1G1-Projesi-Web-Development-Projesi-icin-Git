# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Dağıtılmış Açık Kaynak Kodlarının versiyonlarını geliştiricilerin yerel bilgisayarlarına erişimini sağlayan sistem.

2. Git ile GitHub arasında ne fark var?
Github, Git'in sağlamış olduğu servisleri bulut tabanlı sürücülerde depolamaya yarar. Github vasıtasıyla collab. projelerde çalışılabilir. Git ücretsizdir, Github ise kar amaçlıdır. Özetle; Git'in temel amacı kodları yönetmek iken, Github'ın amacı aynı projeye ait ayrı kodları bir arada tutup ortak çalışmak ve yönetmektir.
3. Neden bir branch oluşturuyoruz?
Çok kişili ve ortak çalışılması gereken projelerde çalışan main branch'ın güvende kalması için diğer geliştiriciler branch oluşturup, bu branchlarda kendi geliştirmelerini yaparlar ve finalde merge ile bu branch veya branchlar toplanıp karışıklık ve crash olmaksızın yeni main branch elde edilmesi için branch oluştururuz. 
4. Pull Request'in amacı nedir?
Başka bir geliştiricinin push etmiş olduğu projeyi kendi yerel bilgisayarımızdaki projeye eklemek.
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout main
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch : kimin projeye ne yaptığını gösterir.
git merge : kendi oluşturduğumuz branchi main branche entegre eder.
git pull : remote'taki projeyi kendi yerel bilgisayarımızdaki projeye ekler.
7. Merge conflict nedir?
conflict, çakışma veya çatışma demektir. iki kişinin aynı kodları değiştirdiği ve branchlarını merge etmek istediklerinde zaten diğerinin o kodu değiştirmiş olmasından dolayı oluşan problemdir.
8. Merge conflict'i nasıl çözeriz?
çalıştığımız feature branchi güncel tutarak. araştırmam sonucu bulduğum bir blog yazısında bu duruma çözüm olarak aşağıdaki satırlar kullanılmış ve nedenleri açıklanmış.

çakışma öncesi için önlemler :

git add -A
git stash
git checkout master
git pull
git checkout feature-1
git rebase master
git stash apply

çakışma gerçekleşmesi durumunda : 

git reset HEAD~1
git add -A
git commit -m “Çakışma giderildi.”
git push --force
git checkout master
git merge feature-1