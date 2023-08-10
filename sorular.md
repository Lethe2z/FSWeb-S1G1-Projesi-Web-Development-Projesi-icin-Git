# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
sürüm kontrol aracı
2. Git ile GitHub arasında ne fark var?
git dağınık bir sürüm kontrol aracı, github ise git'i rahat kullanmak için oluşturulmuş bir web arayüzü.
3. Neden bir branch oluşturuyoruz?
kendimiz istediğimiz değişiklikleri localde yaparken ortak çalışma alanındaki diğer insanlarla paralel bir şekilde çalışmak için.
4. Pull Request'in amacı nedir?
Master'la aramızdaki farkların update'ini almak için.
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout main
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch, tüm commitleri alırız. git merge master'la ya da başka bir branchle localdeki değişiklikleri birleştirmeye yarar. fetch ve merge'ü beraber yapan komut.
7. Merge conflict nedir?
Local'deki değişiklikle birleştirmeye calıştığımız branchteki değişikliklerin çakışması durumudur. 10. satırda birinde a birinde b yazıyorsa bu bir conflicttir.
8. Merge conflict'i nasıl çözeriz?
herhangi birini tercih edebiliriz.
