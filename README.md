# LCWScraper
LCW mağazalarını ve bu mağazaların bilgilerini çeker ve Excel'e aktarır.

Bu uygulamanın çalışması için;
ClosedXML
EPPlus
Selenium.Support
Selenium.WebDriver
Selenium.WebDriver.ChromeDriver
System.Net.Http
Kütüphanelerinin c# projesine kurulması gereklidir.

Uygulama siteyi açar ülke listesinden ülke seçer ve o ülke seçildikten sonra sağ tarafta bulunan mağaza listesini scrollayarak ilerlerken mağazaya ait bütün verileri listeier.
Bunu bütün ülkeler için döngü halinde yapar. Geriye ülke kalmadığı zaman program tuttuğu verileri Excel'e aktarır ve kapanır.
