# Unity Kanser Hücresi Sınıflandırma Projesi

Bu proje, kanser hücrelerini iyi huylu veya kötü huylu olarak sınıflandırmak için Unity'yi Python ile eğitilmiş bir modelle entegre eder. Sınıflandırma, verileri işleyen ve sonucu Unity'ye döndüren bir Flask sunucusu aracılığıyla yapılır.

## Proje Açıklaması
Bu proje, kanser hücrelerinin görselleştirildiği Unity tabanlı bir uygulamayı içermektedir. Bu hücrelerin üzerine tıklandığında veriler, hücreleri iyi huylu veya kötü huylu olarak sınıflandırmak için eğitilmiş bir makine öğrenimi modelini barındıran bir Flask sunucusuna gönderilir.

## Özellikler
- **Etkileşimli Kanser Hücreleri:** Unity'de tıklanabilir kanser hücresi varlıkları.
- **Flask Sunucu Entegrasyonu:** Unity'den Flask sunucusuna işlenmek üzere veri gönderir.
- **Makine Öğrenimi Modeli:** Kanser hücrelerini sınıflandırmak için eğitimli bir Python modeli kullanır.
- **Gerçek Zamanlı Geri Bildirim:** Unity'de sınıflandırma sonucunu (iyi huylu/kötü huylu) görüntüler.

### Ön Koşullar
- Unity 2020.3 veya üstü
- Python 3.8 veya üstü
- Flask 2.0 veya üstü
