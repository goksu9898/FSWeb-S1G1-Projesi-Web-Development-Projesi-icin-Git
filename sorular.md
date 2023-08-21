# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Git, yazılım geliştirmek için kullanılan dağıtık versiyon kontrol sistemidir.

2. Git ile GitHub arasında ne fark var?
Git, bir versiyon kontrol sistemidir. GitHub ise versiyon kontrol sistemi ile oluşturulan, kullanılan projelerin depolandığı yerdir. 

3. Neden bir branch oluşturuyoruz?
Proje üzerinde daha rahat değişiklik, geliştirme yapılabilmesine fayda sağlar. Projenin son çalışan halini bozmamak için kullanırız.

4. Pull Request'in amacı nedir?
Projede ortak çalışılan kişi ya da kişilere yapılan değişiklikleri kontrol ettirmek, onaylatmak için gönderilen taleptir.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın? 
git checkout komutunu kullanırız. main branchine geçiş yapmak için ise git checkout main komutu kullanılır. 

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
Git fetch uzak branchteki kodların yerel branche indirilmesini sağlayan komuttur. Git pull ise uzak branchteki kodları yerel branche aktarıp birleştiren komuttur. Git merge iki branch arasındaki değişikliklerin birleştirilmesini sağlar. Git merge komutunda yerel branchteki değişiklikler uzak branchteki kodlara entegre edilir. 

7. Merge conflict nedir?
İki veya daha fazla kullanıcınının aynı dosya veya satırı değiştirdiğinde ortaya çıkan, çakışan kod durumudur. 

8. Merge conflict'i nasıl çözeriz?
Çakışmayı düzeltmek için dosyamızı açıp çakışan satırları düzeltmemiz gerekir. Git status komutu sayesinde çakışan satırlar veya dosyalar tespit edilebilir. Dosyamızın veya satırların son halinin nasıl olacağına karar verip kaydettikten sonra tekrar commit komutu ile conflicti çözebiliriz.