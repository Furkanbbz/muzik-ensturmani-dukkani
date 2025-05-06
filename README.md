# Müzik Enstürmanı Dükkanı Yönetim Sistemi

# Programın amacı nedir?

Programın amacı, bir müzik enstürmanı dükkanının satılacak enstürman ve satın alacak müşterileri ekleyerek satış yapabildiği bir sistem oluşturmaktır. Ayrıca müşterilerin sorunları için destek talepleri de oluşturulabilir.

# Enstürmanlar Sayfası

Bu sayfadan enstürman dükkanında satışı yapılacak olan enstürmanlar oluşturuluyor.

Eklenecek enstürmanın adı, kaç stok ile satılacağı ve adet fiyatı yazılarak "Ekle" butonuna basılarak satışa çıkartılıyor.

Eğer daha sonra eklenen enstürmanın stoğu güncellenmek istenirse "Enstürman Listesi" bölümünden önce eklenen enstürman seçiliyor, sonrasında Stok Ayarla kısmından yeni stoğunu yazarak "Ayarla" butonuna basarak güncellenebilir.

![image](https://github.com/user-attachments/assets/3eab57ae-a910-4e02-bfde-dc7846b59c83)

# Müşteriler Sayfası

Bu kısımda daha önceden satışa sunulmak için eklenen enstürmanların satılabilmesi için, bu enstürmanları alacak müşterileri ekliyoruz. 

Ekleyeceğimiz müşterinin adını soyadını yazıyor ve iletişim bilgisi kısmına mail adresi veya telefon numarası yazıp "Ekle" butonuna basıyor ve yeni müşteriyi ekliyoruz.

Eğer eklediğimiz müşteriyi silmek istersek "Müşteri Listesi" kısmından müşteriyi seçip "Seçili Sil" butonuna basabiliriz.

![image](https://github.com/user-attachments/assets/c140458b-2c32-414d-8e17-c1035276bd89)

# Satış Yap Sayfası

Bu kısımda ise, satış yapmak için eklediğimiz ensütrmanı ve satın alacak müşteriyi seçerek kaç adet satış yapılacaksa adet kısmına yazarak "Satışı Tamamla" butonuna basıyor ve satış yapıyoruz. 

Satış yaptıktan sonra satış yapılan miktar kadar enstürmanın toplam stoğundan düşüyor.

Eğer önceki satışları görüntülemek istersek satış yap sayfasındaki "Önceki Satışlar" kısmına bakabiliriz.

![image](https://github.com/user-attachments/assets/e3560a77-3538-4d4a-b44f-79bd85710039)


# Destek Talepleri Sayfası

Satın alım yapan müşteriler bir sorun yaşadıkları zaman destek talepleri sayfasını kullanabiliyorlar. Müşteri ve enstürman seçip müşterinin enstürmanda yaşadığı sorunu Detay kısmına yazıp talep oluştur butonuna basmalıyız.

Daha sonra oluşturulan taleplerin durumunu değiştirmek veya detaylı görüntülemek için destek talepleri sayfasında yer alan destek talepleri bölümünden tıklayarak seçebilir, talebi istersek silebiliriz.

![image](https://github.com/user-attachments/assets/e6cf241b-b004-4160-a259-541aff07eb28)

# Veriler Kaydedilmesi

Uygulamada bir işlem yapıldığında veriler otomatik olarak kodun çalıştığı klasöre "veriler" isimde bir klasör oluşturularak bu klasör içerisine her işlem katagorisi için ayrı bir dosya açılarak kaydediliyor. (destek_talepleri.json, ensturmanlar.json, musteriler.json, satislar.json, son_idler.json)

![image](https://github.com/user-attachments/assets/d78a5d0d-b4a8-4e80-94e2-81e07a9fec03)

# Uygulama Kurulumu

Uygulamayı kurmak için ilk olarak Visual Studio Code uygulamasını kurup eklentiler kısmından Python'u kuruyoruz. Sonrasında projeyi indirip rardan çıkartıyoruz. muzikdukkani.py adındaki dosyayı visual studio code ile açıp çalıştırıyoruz.
