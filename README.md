# ilk_repository

‘git config’; kullanıcı adı, mail, dosya formatları gibi genel yapılandırma ayarlarının yapılacağı komuttur.

$ git config --global user.name "NAME"
$ git config --global user.email "EMAIL"

‘git add’; Projeye eklenmek istenen dosyaları add komutuyla Git içerisine ekler ve git status ile tekrar kontrol edilebilir.

$ git add <dosya_ismi>    // adı yazılan dosyayı;
$ git add *              //proje içerisindeki tüm dosyaları; çalışma dizinine eklemiş oluyor. 

‘git commit’; Bu komut yoluyla projedeki değişikler local repository’e kaydedilir.

$ git commit -m "Projede X işlemi yapıldı."      //Tırnak içerisinde yazan kısım commit mesajıdır ve bu alanı boş bırakılmaması gerekir. 

‘git push’; Commit‘lenmiş değişiklikleri uzak sunucudaki repository‘ye gönderilmesini sağlayan komuttur.

$ git push 

‘git status’; Yapılan değişiklikleri; yani eklenen, silinen dosyaların hangi branch’te olduğunu gösterir. 

$ git status

‘git log’; Projede hangi commit’lerin yapıldığını görüntülememizi sağlar.

$ git log

‘git branch’; Proje içerisinde bulunan brach’lerin oluşumlarını görmek istediğimizde bu komutu kullanırız. Bize Local repository’de bulunan tüm branch’lerin bilgisini verir.

$ git branch 
$ git branch <branch_ismi>  //yeni branch oluşturmak için kullanılır.


