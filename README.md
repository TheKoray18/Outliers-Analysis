# Outliers-Analysis
Veri Setimizde ki değişkenlerin Aykırı Değerlerini analiz ettim ve Aykırı Değer Problemini çözme yötemlerine değindim

Aykırı Gözlem : Veride genel eğilimin oldukça dışına çıkan ya  diğer gözlemlerden oldukça farklı olan gözlemler denir
Aykırı Değer ( Outlier) : Aykırılığı ifade eden numerik değere "aykırı değer" denir.
 - Aykırı Değerler Yanlılığa sebep olurlar.
 
 Aykırı Değer Analizinde ki Yöntemler ;
 
  - Sektör Bilgisi
  - Standart Sapma Yaklaşımı
  - Z-Skoru Yaklaşımı 
  - Boxplot 

Biz burada Boxplot yöntemini kullandık.Boxplot yöntemi en sık kullanılan yöntemlerden birisidir.Ben Boxplot'u Seaborn Veri Görselleştirme kütüphanesi içerisinden import ettim.
Boxplot metodu, değişkenlerin değerlerini küçükten büyüğe doğru sıralar.Yüzdeliklerine , Q1 ve Q3 değerleri kullanarak alt ve üst eşik değerleri hesaplanır.

 - IQR = 1.5 * (Q3 - Q1)

 - Alt Eşik Değeri = Q1 - IQR 
 
 - Üst Eşik Değeri = Q3 + IQR 
 
 Değişkenimizin değerlerinden, Alt Eşik Değeri'nin altında kalan ve Üst Eşik Değerinin de üstünde olan değerlerimiz bizim " Aykırı Değerlerimiz " oluyor. 

