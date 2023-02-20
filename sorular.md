## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
Cevap- Git açık kaynaklı dağıtılmış bir versiyon kontrol sistemidir. 
2. Git ile GitHub arasında ne fark var?
Cevap- Git, bir versiyon kontrol sistemi iken, Github, git barındırma hizmeti sunan bir şirkettir.
3. Neden bir branch oluşturuyoruz? 
Cevap- Orijinal koddan bağımsız olarak, kaynak kodun üzerinde çalışılmasına imkan sağlamak için branch oluşturuyoruz.
4. Pull Request'in amacı nedir?
Cevap- Ilgili repoda çalışan kişileri yaptığımız değişiklerden haberdar etmek için.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
Cevap- git checkout main
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
Cevap- `git pull` ile bir reponun yerel sürümünü güncelleriz(fetch edip merge eder). Dolayısıyla otomatik olarak commitleri birleştirir. Aynı işi `git fetch` + `git merge` ile de yapabiliriz. `git fetch` ile remote repo'dan ilgili branch'i çekebilir daha sonra merge edebiliriz.
7. Merge conflict nedir?
Cevap- Merge conflict, branch'ler merge edilirken ortaya çıkan, aynı noktada(aynı satır vs.) farklı şekillerde değişiklik yapılması durumunda ortaya çıkan çakışmadır.
8. Merge conflict'i nasıl çözeriz?
Cevap- Conflict oluşan noktada gerekli değişiklikleri yaparak çözebiliriz.
