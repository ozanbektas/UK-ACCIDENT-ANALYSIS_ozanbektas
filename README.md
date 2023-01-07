# UK_ACCIDENT_ANALYSIS

## Projemde, öncelikle csv dosyasından tüm verileri çektim. Bu veriler, makine öğrenimi algoritmaları tarafından kullanılacaktı, ancak önce işlenmeye ihtiyaç duyuyorlardı. Bu veriler csv dosyasında çiğ halde bulunuyorlardı ve makine öğrenimi algoritmasına katkısı olmayacak olan kısımları önce sildim.

## Daha sonra, makine öğrenimi algoritmasında önemli parametrelerin ve değişkenlerin görünmesini sağlamak için bir kod yazdım ve tüm verileri görüntüledim. Bu sayede, hangi verilerin algoritmamda bulunması gerektiğini belirleyebilecektim.

## Sonrasında, görüntülenen verilerde kaza şiddetinin hangi durumlarda arttığını anlamaya yönelik bir korelasyon haritası oluşturdum. Bu harita, kaza şiddetini arttıran parametreleri belirlememde önemli bir yardımcı oldu. Bu nedenle, heat map ve eksenler grafiği kullanmaya özen gösterdim, çünkü en iyi ilişkileri heat map üzerinden gözlemleyebiliriz.

## Daha sonra, hangi parametrelerin algoritmamda bulunması gerektiğinden emin olduktan sonra, tüm verilerimi algoritmada işleyebilir hale getirdim. Bu nedenle, değişkenlerimi integer olarak değiştirdim, çünkü algoritmada string olarak bulunmaları mümkün değildi. Bu sayede, verilerimin algoritmada işlenmesine izin verebilecektim.

## Son olarak,Naive Bayes yöntemini kullanarak bir tahmin algoritması yazdım.Linear regression yerine Naive Bayes kullanmamın sebebi geçmişteki kaza raporlarını incelememdi.Linear regression ve Naive Bayes Classification arasındaki temel fark, veri kümesindeki ilişkiyi tahmin etme yöntemleridir. Linear regression, veri kümesindeki ilişkiyi doğrusal bir eğime göre tahmin ederken, Naive Bayes Classification ise veri kümesindeki ilişkiyi geçmiş olayları inceleyerek tahmin eder.Bu yöntemle oluşturduğum algoritmada, 0.85 rating aldım. Bu, Naive Bayes modelleri için ortalama bir değeridir ve algoritmamın performansını ölçmek için kullanılabilir.


# **SONUÇLAR**

## **Trafik akışının değişmesi kazaları nasıl etkiler?**
 - Trafikte araç sayısının artması ve trafiğin yoğunlaşmasıyla kaza oranlarının arttığı saptanmıştır.

## **Kaza oranlarını ne artırır?**
 - Ingilteredeki kazaların şiddeti genelde can kaybıyla sonuçanan yüksek şiddetli kazalardır.
 - Kazalar genelede ortalama haftanın her günü birbirine yakın değerlere sahipken Cumartesi günleri diğer günlere göre biraz daha fazla olmaktadır.Kazaların en çok meydana geldiği yollar çift şeritli hız limiti yüksek yollar yerine tek şeritli ve hız limitinin 30 olduğu yollardır.
 - Önemli noktalardan biri bu yollardaki kontrol durumudur.
 - Kazaların çok yüksek bölümü kontrol noktası bulunmayan yerlerde gerçekleşmektedir.
 - Kazaların olma sıklığı tahmin edilenin aksine gündüz ve gün ışığında olmaktadır ve günün diğer zamanlarına kıyasla yüksek bir orana sahiptir.
 - Kazaların yüksek oranda olduğu hava şartları kötü hava şartlarından ziyade normal rüzgarsız havalarda ve yolların kuru olduğu durumlardadır.
## **Kırsal ve kentsel alanlar nasıl farklılaştı?**
 - Kırsal alanlar yıllar içinde kentleşmiş ve trafik sıklığı artmıştır. 
## **Zaman içinde kaza oranlarını tahmin edebilir miyiz?**
 - Kaza oranlarını tahmin etmek mümkündür. Veri analizimde kullandığım değişkenlerle oluşturduğum makine öğrenmesi algortiması sonucunda kaza oranlarının hangi hava şartları,hangi trafik sıklığı,hangi saat ve haftanın hangi günü olduğuna bağlı olarak kaza oranları ve kaza riski tahmin edilebilir.


 https://app.patika.dev/ozanbektas