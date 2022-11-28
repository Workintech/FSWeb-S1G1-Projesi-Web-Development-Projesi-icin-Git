## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz.

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
   Git is an open source distributed version control system which helps to track changes of projects and files.
2. Git ile GitHub arasında ne fark var?
   Git is version control system whereas GitHub is a hosting service lets us manage Git repositories.
3. Neden bir branch oluşturuyoruz?
   We create branch to encapsulate the changes we made on it. That way we maintain the stability of the main.
4. Pull Request'in amacı nedir?
   Pull requests let us tell the others about changes we have pushed to a branch in a repository on GitHub.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
   git checkout main
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
   `git fetch` fetches commits from the target branch and stores them in local repository. `git merge`, does merge a another branch into the current branch. `git pull` does both.
7. Merge conflict nedir?
   A merge conflict usually occurs when the current branch and the branch we want to merge into the current branch have diverged. That is, we have commits in our current branch which are not in the other branch, and vice versa.
8. Merge conflict'i nasıl çözeriz?
   By consuming too much time. We have to decide if there is a better version we want to keep or if we have to handle whole conflict one by one.
