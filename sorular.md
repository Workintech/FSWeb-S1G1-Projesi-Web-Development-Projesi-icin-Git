## Araştırma Soruları

Not: Bu duzenleme terminal nano editorunde yapilmistir  


1. Git nedir? --> Versiyon kontrol sistemidir daha detayli soylemek gerekirse daginik kontrol sisteminin en yayginidir ,

2. Git ile GitHub arasında ne fark var? --> Git bir versiyon kontrol sistemidir, github ise versiyon kontrol sistemiyle calistigimiz projeleri depoladigimiz bir online portaldir.Bu portalda baska
kullanicilara ait projelere de ulasabiliriz.  

3. Neden bir branch oluşturuyoruz? --> kullaniciya projenin farkli versiyonlarina ulasimini saglar bunun da sebebi bir degisiklik yaptigimizda eger hata ile karsilasirsak eski versiyona geri donmek icin

4. Pull Request'in amacı nedir? --> Bir talep olusturmaktir.Bu talep main branch'i olusturan kisiden kodumuzu eklememizi istemektir, 

5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz. --> Once nerede oldugumuzu gormek 
icin git branch yapariz daha sonra main brancha gecmek icin "git checkout main" komutunu kullaniriz 

6. `git fetch`, `git merge` ve `git pull` arasındaki farkları açıklayınız. Bu komutlar ne yapar açıklayınız. --> git fetch remote da degisiklik yapildiginda bu degisiklikleri gormemiz icin locale
indirir, git merge ise remote proje ve local arasinda farklilik oldugunda remote daki degisiklikleri locale entegre etmemizi saglar. git pull da her ikisini ayni anda yapmamizi saglar yani remote da 
bir degisiklik yapildiginda bu degisiklikleri hem indirir hem de localimize entegre eder.

7. Merge conflict nedir? projede degisiklik yapildiginda ve tamamladiktan sonra merge edildiginde alinan cakisma hatasidir.
8. Merge conflict'i nasıl çözeriz? Karsilastirip degisen yerlere bakarak hangisinin dogru olduguna bakariz , bu sekilde cozebiliriz 
