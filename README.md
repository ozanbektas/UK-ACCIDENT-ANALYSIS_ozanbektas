# UK_ACCIDENT_ANALYSIS

## Projemde, öncelikle csv dosyasından tüm verileri çektim. Bu veriler, makine öğrenimi algoritmaları tarafından kullanılacaktı, ancak önce işlenmeye ihtiyaç duyuyorlardı. Bu veriler csv dosyasında çiğ halde bulunuyorlardı ve makine öğrenimi algoritmasına katkısı olmayacak olan kısımları önce sildim.

## Daha sonra, makine öğrenimi algoritmasında önemli parametrelerin ve değişkenlerin görünmesini sağlamak için bir kod yazdım ve tüm verileri görüntüledim. Bu sayede, hangi verilerin algoritmamda bulunması gerektiğini belirleyebilecektim.

## Sonrasında, görüntülenen verilerde kaza şiddetinin hangi durumlarda arttığını anlamaya yönelik bir korelasyon haritası oluşturdum. Bu harita, kaza şiddetini arttıran parametreleri belirlememde önemli bir yardımcı oldu. Bu nedenle, heat map ve eksenler grafiği kullanmaya özen gösterdim, çünkü en iyi ilişkileri heat map üzerinden gözlemleyebiliriz.

## Daha sonra, hangi parametrelerin algoritmamda bulunması gerektiğinden emin olduktan sonra, tüm verilerimi algoritmada işleyebilir hale getirdim. Bu nedenle, değişkenlerimi integer ve float olarak değiştirdim, çünkü algoritmada string olarak bulunmaları mümkün değildi. Bu sayede, verilerimin algoritmada işlenmesine izin verebilecektim.

## Son olarak, linear regression yöntemini kullanarak bir tahmin algoritması yazdım. Bu yöntemle oluşturduğum algoritmada, 0.85 rating aldım. Bu, ortalama linear regression modelleri için iyi bir rating değeridir ve algoritmamın performansını ölçmek için kullanılabilir. 