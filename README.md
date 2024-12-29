 Vaadin framework den https://start.vaadin.com/app/ linkini takip ederek örnek bir proje 
indirip kullanmak istediğiniz ide ye import ederek localhost da çalışan bir spring projesi 
hazırladık.
Ide üzerinden import ederek ayağa kaldırdım.
Daha sonra projenizin sol tarafında yer alan bar’a Hello World ve About tablarının arasına 
“Personel” adında bir tab ekledim ve bu tabın içine içerisinde personel modeli barındıran bir 
grid ekledim. 
Vaadin grid örneği: https://vaadin.com/docs/v14/flow/components/tutorial-flow-grid
 Personel modeli içeriği:  String TC
 String Ad
 String Soyad
 İçerisinde personel modeli barındıran bu gride MVC çok katlı mimarisini kullanarak service
 katmanından dummy 10 tane eleman ekledim. Personel in adı ve soyadı grid kolonlarında 
görüntülendi.
Ekranın en üstüne eklediğiniz bu elemanları ada göre sorgulayan bir arama çubuğu 
(Vaadin TextField) ekleyerek grid data provider üzerinden arama yapabilmesini sağladım.
