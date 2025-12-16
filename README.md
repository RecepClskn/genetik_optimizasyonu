# genetik_optimizasyonu

AD: Recep

SOYAD: Çalışkan

OKUL NUMARASI: 2312721004



--Genetik Algoritma ile Tarım Arazisinde Gübre ve Sulama Ayarı--

Bu projede, bir tarım arazisinde bitki verimini maksimize etmek amacıyla
kısıtlı bir optimizasyon problemi **Genetik Algoritma (GA)** kullanılarak çözülmüştür.



--Amaç fonksiyonu aşağıdaki gibidir:

\[
y = 10x₁ + 6x₂ - 0.5x₁^2 - 0.2x₂^2
\]



--Değişkenlerimiz ise bu şekilde:

1-x₁: Gübre miktarı (kg/da), 0 ≤ x₁ ≤ 50

2-x₂: Sulama miktarı (L/da), 0 ≤ x₂ ≤ 100  


--Kısıtlamalar

1-x₁ + 0.1x₂ ≤ 60

2-x₂ ≥ 20  



--Kullandığımız Yöntem:

Bizim problemimiz,doğrusal olmadığı ve kısıtlamaları olduğu için Genetik Algoritmayı tercih ettik.
Algoritmada, gübre ve sulama miktarları sürekli değerler aldığından karar değişkenleri reel sayılarla ifade ettik.
Ebeveyn seçimi aşamasında, daha iyi çözümlerin seçilme olasılığını artırırken popülasyon çeşitliliğini koruyan turnuva seçimi yöntemini kullandık.
Yeni çözümler üretmek amacıyla aritmetik çaprazlama uygulanmış, popülasyondaki çeşitliliğin sürdürülmesi için Gauss mutasyonunu tercih ettik.
Problemde yer alan kısıtlar, ceza fonksiyonu aracılığıyla uygunluk fonksiyonuna entegre edildi.
Ayrıca, her nesilde elde edilen en iyi çözümün korunmasını sağlamak amacıyla elitizm yöntemini uyguladık.



--Algoritmada Kullandığımız Parametreler:

Parametreler ve Değerleri

Popülasyon Büyüklüğü = 100,
İterasyon Sayısı = 150,
Çaprazlama Oranı = 0.8,
Mutasyon Oranı = 0.05,
Turnuva Boyutu = 3



--Sonuç Kısmı:

Genetik Algoritma, kısıtlar altında optimum çözümü başarıyla bulmuştur.
Elde edilen sonuçlar, teorik olarak beklenen sınır çözümü ile uyumludur.

Algoritmanın yakınsama davranışı, iterasyonlara göre en iyi uygunluk
değerlerinin grafiği ile gösterilmiştir.


