# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

Git, Açık Kaynak Dağıtılmış Sürüm Kontrol Sistemi(Open Source Distributed Version Control System)'dir.

Açık Kaynak: Orijinal kaynak kodları, herkes tarafından erişilebilen, uygun görülen şekilde değiştirilebilen ve dağıtılabilen yazılım türüdür.

Kontrol Sistemi: Bu, git'in bir içerik izleyici olduğu anlamına gelir, yani git içeriği depolamak için kullanılabilir. Bu genellikle kod’dur. Ancak yazı, resim veya başka herhangi bir dosya türü de olabilir.

Sürüm Kontrol Sistemi: Projeleri oluşturan dosyaların kullanıcılar tarafından yapılan güncellemeleri kayıt altına alınır ve bu güncellemelerin bir kronolojiye göre takip edilmesine imkan tanır.

Dağıtılmış Sürüm Kontrol Sistemi: Git'in sunucuda depolanan remote bir sürümü ve geliştiricinin bilgisayarında depolanan yerel bir sürümü vardır. Bu, kodun merkezi bir sunucuda depolandığı ve tam bir kopyasının tüm geliştiricilerin bilgisayarlarında bulunduğu anlamına gelir.

Geliştiriciler bir proje yarattıklarında (örneğin bir uygulama veya web sitesi) ilk resmi (beta olmayan) sürüme kadar ve hatta sonrasında yeni sürümler yayınlayarak kod üzerinde sürekli değişiklik yaparlar. Sürüm kontrol sistemleri, değişiklikleri merkezi bir depoda saklayarak bu revizyonları düzenli tutar. Bu, geliştiricilerin kodun yerel sürümleri üzerinde çalışabilmelerini, değişiklik yapabilmelerini ve en yeni revizyonu yükleyebilmelerini sağlayarak kolayca işbirliği yapmalarına olanak tanır. Her geliştirici bu yeni değişiklikleri görebilir, indirebilir ve katkıda bulunabilir.

2. Git ile GitHub arasında ne fark var?

Git is a version control system that allows developers to track changes in their code. GitHub is a web-based hosting service for git repositories. In simple terms, you can use git without Github, but you cannot use GitHub without Git.

3. Neden bir branch oluşturuyoruz?

Creating a new branch allows you to isolate your changes from the master branch.

4. Pull Request'in amacı nedir?

Pull requests let you tell others about changes you've pushed to a branch in a repository on GitHub. Once a pull request is opened, you can discuss and review the potential changes with collaborators and add follow-up commits before your changes are merged into the base branch.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

git checkout

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

The key difference between git fetch and pull is that git pull copies changes from a remote repository directly into your working directory, while git fetch does not. The git fetch command only copies changes into your local Git repo. The git pull command does both.

If your workspace has no uncommitted files, and you want to copy the latest changes from a remote repository directly into your working directory, then issue the git pull command.

If you want to pull down the latest changes from a remote repository without overwriting anything in your working directory, then use git fetch, and then do a git merge when the time is right.

7. Merge conflict nedir?

A merge conflict occurs when a version of a file has been submitted that is newer than the version of the file you have started to base your changes on.

8. Merge conflict'i nasıl çözeriz?

There are a few steps that could reduce the steps needed to resolve merge conflicts in Git.

1.The easiest way to resolve a conflicted file is to open it and make any necessary changes.
2.After editing the file, we can use the git add a command to stage the new merged content.
3.The final step is to create a new commit with the help of the git commit command.
4.Git will create a new merge commit to finalize the merge.