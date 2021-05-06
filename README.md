# parxlab_case
Ekte belirtilen veri seti Çin’de bulunan ABD büyük elçiliğine ait geçmiş 5 yılın her ay
alınmış hava verilerini içermektedir. Bu veri içerisinde tarih verisi, kirlilik durumu, ve hava
durumuna ait o anki bazı verileri içermektedir. Bu verilerden faydalanarak bir sonraki saat
hava kirliliğinin tahmin edilmesine yönelik en kapsamlı değerlendirme yapan en başarılı
modelin elde edilmesi beklenmektedir.

No: row number
year: year of data in this row
month: month of data in this row
day: day of data in this row
hour: hour of data in this row
pm2.5: PM2.5 concentration (pollution)
DEWP: Dew Point
TEMP: Temperature
PRES: Pressure
cbwd: Combined wind direction
Iws: Cumulated wind speed
Is: Cumulated hours of snow
Ir: Cumulated hours of rain
Veri setinin açıklaması aşağıdaki gibidir:

Çalışma içerisinde en az 1 ML modeli ve probleme yönelik en az 1 DL modeli
oluşturulmalıdır. Seçilecek DL modeli çok değişkenli model olmalı, birden
fazla inputu değerlendirerek kirlilik tahmin gerçekleştirmelidir.
Yapılan veri hazırlama ve görselleştirme aşamaları gösterilmelidir.
Bu modellerin başarı metrikleri ve sonuçlarının yorumlanması
beklenmektedir.
Elde edilen başarı metriğinin olması gerekene göre kıyaslaması da yapılığ
yorum olarak belirtilmelidir. (Örn: Aslında bu sonuç çıkmalıydı veya bu
değere yakın olmalıydı ...)
Modeller veya hazırlanan veri işleme aşamaları bir Jupyter Notebook da veya
scriptler şeklinde oluşutulabilir.
