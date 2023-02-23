# AddressBook_SUNUM
Merhaba, Address Book projesi  İstanbul - Beşiktaş Wissen Akademi'de Kursiyerlik yaptığım süreçte oluşturduk.Bu projede Trendyol,Getir gibi uygulamalardaki adres ekleme bölümünden esinlendik. Amacımız adres kaydı yapmaktır. Ayrıca gerçek hayata yaklaşmak ve istihdam sürecindeki hazır bulunuşluğu maksimum seviyeye getirebilmektir.

Burada projenin ekran resimlerini ve kaynak kodlardan bazı kod parçalarını aşağıda görebilirsiniz.

PROJE HAKKINDA TEKNİK BİLGİLER:

Proje Visual Studio .Net 6 ASP.NET MVC CORE ile yazıldı.
Proje Entity Framework Core Code-First yaklaşımıyla yazılmıştır.
Projede AspnetCore Identity kullanarak üyelik sistemini yazdık.
Proje Visual Studio 2022 IDE'sinde yazılmıştır.
Projeyi 5 katman (EL,DAL,BLL,UI, AddressBookNeighborhoodsLoad) olarak yazdık. -AddressBookNeighborhoodsLoad katmanı Console uygulaması olup Mahalle datasını eklemektedir. (70bin data bulunuyor)
Projede İlleri ve İlçeleri Excel dosyasını back-endde okuyarak veritabanına proje ilk ayağa kalktığında ekledik.
Projede Adres listesi ve Adres Ekle - Adres Sil ekranları bulunuyor.
Adres Ekle sayfasındaki işlemleri AJAX ile yapmaktayız. Örneğin; ili seçtiğinde ilçeler sayfa yenilenmeden gelir. İlçeyi seçtiğinde mahalleler sayfa yenilenmeden gelir.
Mahalleyi seçince o mahallenin posta kodunu APi'den çektik. https://api.ubilisim.com/postakodu/il/34
Proje gelişmeye açık olup zaman buldukça yeni sayfalar ya da yeni özellikler eklenecektir.
Ekran resimleri ve kaynak kodlardan bir parça aşağıda görebilirsiniz.

Bilgilerimizi girerek kayıt oluyoruz.
![Adressbook1](https://user-images.githubusercontent.com/73429501/220843724-70edccc8-803f-427a-b320-ff13e63cd31f.JPG)
![Addressbook2](https://user-images.githubusercontent.com/73429501/220843739-bd140c9e-226f-4d92-a3b1-da8707c360d3.JPG)
Burada adres bilgilerini girip kayıt oluyoruz.
![addressbook3](https://user-images.githubusercontent.com/73429501/220843746-871b62d1-05fb-4fda-9823-b378818cc8a4.JPG)
Adress eklendi bildirimi aldık.
![Addressbook4](https://user-images.githubusercontent.com/73429501/220843751-74d9c51c-4611-4faf-8d9e-373ae9a458ff.JPG)
Listelenen adresler aşağıda gözükmektedir.
<img width="960" alt="Listelenenadresler" src="https://user-images.githubusercontent.com/73429501/220844461-ed25c4f7-0542-4fb5-87cc-058071fdfa46.png">
![Addressbook5](https://user-images.githubusercontent.com/73429501/220843759-dab02bc3-fb12-4aa0-9ff5-6077a4ffb4d4.JPG)
![Addressbook6](https://user-images.githubusercontent.com/73429501/220843762-b2cf7672-c991-4a10-a86a-d3448a362bdc.JPG)
