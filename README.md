# Retail Sales Analysis Dashboard

## Proje Özeti

Bu projede perakende satış verisi analiz edilerek kategori, bölge ve zaman bazında satış performansı incelenmiştir. 
Amaç, satışların hangi alanlarda yoğunlaştığını belirlemek, düşük performans gösteren alanları tespit etmek ve analiz sonuçlarına dayalı öneriler geliştirmektir. 
Analiz sürecinde spreadsheet araçları kullanılarak görselleştirmeler ve dashboard oluşturulmuştur.

## Amaç

- Satış performansını analiz etmek  
- En yüksek ve düşük performans gösteren kategori ve ürünleri belirlemek  
- Bölgesel satış farklarını incelemek  
- Zaman bazlı satış trendlerini analiz etmek  
- Analiz sonuçlarına göre iş kararlarını destekleyecek öneriler geliştirmek

## Kullanılan Araçlar

- Google Sheets (veri analizi ve görselleştirme)  
- Pivot Table (veri özetleme ve analiz)  
- Grafikler (bar chart, line chart)

## Yapılan Analizler

- Kategori bazlı satış analizi  
- Alt kategori (ürün grubu) bazlı satış analizi  
- Bölge bazlı satış performansı analizi  
- Zaman bazlı satış trend analizi (aylık ve çeyreklik)  
- Kâr ve indirim etkisinin değerlendirilmesi

## Veri Kalitesi Problemleri

Veri setinde tarih sütununda farklı formatlar (DD/MM/YYYY ve MM/DD/YYYY) kullanıldığı tespit edilmiştir. 
Bu durum analiz sırasında hatalara yol açmıştır.
Bu problem, tarih verisinin yeniden parse edilmesi ve tek bir formatta standardize edilmesi ile çözülmüştür.
Ayrıca bazı satırlarda kâr (profit) değerinin satış (sales) değerinden yüksek olduğu gözlemlenmiş olup, bu durum veri kalitesi açısından değerlendirilmiştir.

## Analiz Sonuçları ve Öneriler

- Furniture kategorisi en yüksek satışa sahip olup toplam satışların önemli bir kısmını oluşturmaktadır.
Bu kategoriye yönelik stok ve kampanya stratejileri satışları artırabilir.

- Technology kategorisi hem satış hem de kârlılık açısından güçlü performans göstermektedir.
Bu kategori stratejik olarak büyütülebilir.

- West bölgesi en yüksek satış performansına sahipken, South bölgesi en düşük performansı göstermektedir.
Bu fark, mağaza sayısı, müşteri yoğunluğu veya ürün erişilebilirliği gibi faktörlerden kaynaklanıyor olabilir.

- Satışların belirli alt kategorilerde yoğunlaştığı görülmektedir.
Bu durum ürün çeşitliliği açısından risk oluşturabilir ve daha dengeli bir dağılım için strateji geliştirilmesi gerekebilir.

- Office Supplies kategorisinde yüksek indirim uygulanmasına rağmen satış performansının görece düşük kalması, indirim stratejisinin her zaman beklenen etkiyi yaratmadığını göstermektedir.

- Satışların çeyrekler bazında dalgalı bir seyir izlediği görülmektedir. Belirli dönemlerde yaşanan artışlar sezonluk talep veya kampanya etkisine işaret ediyor olabilir.

## Dashboard

Bu projede satış performansını görselleştirmek amacıyla Google Sheets kullanılarak bir dashboard oluşturulmuştur. 
Dashboard üzerinde kategori, bölge ve zaman bazlı analizler görsel olarak sunulmuştur.

<img width="627" height="359" alt="Ekran Resmi 2026-04-07 04 21 30" src="https://github.com/user-attachments/assets/ee4b0fe5-e0df-4055-bda3-955726ca0956" />

## Sonuç

Bu çalışma ile satış verisi detaylı şekilde analiz edilerek önemli performans farkları ve trendler ortaya çıkarılmıştır. 
Elde edilen analiz sonuçları, iş kararlarını destekleyecek nitelikte olup, özellikle kategori, bölge ve zaman bazlı stratejiler geliştirilmesine katkı sağlayabilir.
Ayrıca veri setinde tespit edilen veri kalitesi problemleri düzeltilerek analiz doğruluğu artırılmıştır.











