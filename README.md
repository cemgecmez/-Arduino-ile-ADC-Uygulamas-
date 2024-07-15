# -Arduino-ile-ADC-Uygulaması-
1. Amaç
Mikrodenetleyicilerde bulunan analog-dijital çevirici modülünü kullanarak sensörden
okunan verilerin anlamlandırılmasını yapmak.

2.Gerekli Malzemeler
• Ardunio Uno Geliştirme Kartı
• 1 adet HC-SR04 Sensör
• 3 adet LED (farklı renklerde Kırmızı, Sarı, Yeşil)
• 3 adet 220Ω direnç
• 16x2 LCD
• 10kΩ potansiyometre
• 1 adet buzzer
• 1 adet 100 Ω direnç

3.Adımlar
• 16x2 LCD bağlantısını ön hazırlık çalışmanıza uygun olarak yapınız.
• HC-SR04 sensörlerini uygun analog pinlere bağlantısını yapınız ve hangi pinlere
bağlağınızı tablo halinde belirtiniz.
• İstediğiniz boş pinlere 3 adet ledi uygun dirençler ile bağlayınuz. Kullandığınız pinleri
tablo halinde belirtiniz.
• HC-SR04 sensörü ile mesafe ölçülecek ve ekranın üst satırında “MESAFE” alt satırında
ölçülen mesafe cm cinsinden verilerek (“x cm”) ortalı şekilde gözükecektir. Mesafe
değiştikçe kendisini sürekli güncelleyecektir.

--- Mesafe aralıkları;
• 1m ile 50 cm arasında ise buzzer ve yeşil led 50 ms aktif 100 ms
pasif çalışacaktır.
• 50 cm -25 cm arasında ise buzzer ve sarı led 50 ms aktif 50 ms
pasif çalışacaktır.
• 25 cm- 10 cm arasında ise buzzer ve kırmızı led 10 ms aktif 10
ms pasif çalışacaktır.
• 10 cm altında ise buzzer ve kırmızı led sabit sarı ve yeşil ledler
50 ms aktif 50 ms pasif çalışacaktır. 
