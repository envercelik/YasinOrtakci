# Android Ders Notları
2020 Mobil programlama dersine ait, tüm uygulamalar, ödevler ve notlar

| Ders Notu   |      Uygulama      |  Ödev |
|----------|:-------------:|------:|
|[Hafta 1](#hafta1)| [Ders uygulamalarına ait tüm kodlar](https://github.com/envercelik/YasinOrtakci/tree/main/App00OrjinalDersKodlar%C4%B1) | |
|[Hafta 2](#hafta2)|[FirstApplication](https://github.com/envercelik/YasinOrtakci/tree/main/App01FirstApp)|[Calculator](https://github.com/envercelik/YasinOrtakci/tree/main/App02Odev1Calculator) |
|[Hafta 3](#hafta3) |[SecondApplication](https://github.com/envercelik/YasinOrtakci/tree/main/App03SecondApplication) |- |
|[Hafta 4](#hafta4) |[LayoutTypes](https://github.com/envercelik/YasinOrtakci/tree/main/App05LayoutTypes) |[Layouts](https://github.com/envercelik/YasinOrtakci/tree/main/App04Odev3Layouts) |
|[Hafta 5](#hafta5) |[IntendApplication](https://github.com/envercelik/YasinOrtakci/tree/main/App06IntentApplication)  |  [Intend](https://github.com/envercelik/YasinOrtakci/tree/main/App07Odev4Intend) |
|[Hafta 6](#hafta6) |[CallApplication](https://github.com/envercelik/YasinOrtakci/tree/main/App08CallApplication) |  [Permission](https://github.com/envercelik/YasinOrtakci/tree/main/App09Odev5Permission) |
|[Hafta 7](#hafta7) |[LoginApplication](https://github.com/envercelik/YasinOrtakci/tree/main/App10LoginApplication)|[SQLite](https://github.com/envercelik/YasinOrtakci/tree/main/App11Odev6SQLite) |
|[Hafta 8](#hafta8) |[GoogleMap](https://github.com/envercelik/YasinOrtakci/tree/main/App12GoogleMap)   |   [GoogleMaps](https://github.com/envercelik/YasinOrtakci/tree/main/App13Odev7GoogleMaps)|
|[Hafta 9](#hafta9) |[JSONApplication](https://github.com/envercelik/YasinOrtakci/tree/main/App14JSONApplication) |   [JSON](https://github.com/envercelik/YasinOrtakci/tree/main/App15Odev8JSON)|
|[Hafta 10](#hafta10)|[JSOUPApplication](https://github.com/envercelik/YasinOrtakci/tree/main/App17JsoupApplication) |[JSOUP](https://github.com/envercelik/YasinOrtakci/tree/main/App18Odev9JSOUP) |
|[Hafta 11](#hafta11) |[AsyncTaskApplication](https://github.com/envercelik/YasinOrtakci/tree/main/App19AsyncTaskApplication) |  [AsyncTask](https://github.com/envercelik/YasinOrtakci/tree/main/App20Odev10AsyncTask) |
|[Hafta 12](#hafta12) |[FragmentApplication1](https://github.com/envercelik/YasinOrtakci/tree/main/App21FragmentApplication1) <br> [FragmentApplication2](https://github.com/envercelik/YasinOrtakci/tree/main/App22FragmentApplication2)|   - |
|[Hafta 13](#hafta13) |[FragmentApplication3](https://github.com/envercelik/YasinOrtakci/tree/main/App23FragmentApplication3) <br> [FragmentApplication4](https://github.com/envercelik/YasinOrtakci/tree/main/App24FragmentApplication4)  <br> [FragmentApplication5](https://github.com/envercelik/YasinOrtakci/tree/main/App25FragmentApplication5) |  [Fragment](https://github.com/envercelik/YasinOrtakci/tree/main/App26Odev11Fragment) |
|[eklenecek](#) |[eklenecek](#)   |  - |




# Hafta 1 
<br>
<h2 id="hafta1">Android Nedir</h2>

- Andorid, linux çekirdeği üzerine geliştirilmiş açık kaynak kodlu işletim sistemidir.

- Mobil (taşınabilir) cihazlar hedeflenmiştir.

- Google ve Open Handset Alliance birliği tarafından geliştirilmektedir. <br><br><br>


<h2>Android'in Mimari Yapısı</h2>

[![2000px-Android-System-Architecture-svg.png](https://i.postimg.cc/prm9jMN1/2000px-Android-System-Architecture-svg.png)](https://postimg.cc/8fVP83zh)

<h4>Applications :</h4> Kullanıcı ile etkileşim sağlanan katmandır. Bildiğimiz, kullandığımız uygulamalar bu katmanda yer alır. Örneğin instagram,whatsapp,browser...

<h4>Application Framework :</h4> Bir üst katmandaki uygulamalarımızın çalışması için gerekli kütüphaneler topluluğudur. Uygulamalarımızı geliştirmek için bu kütüphanleri kullanırız.

<h4>Libraries :</h4> C ile yazılmış sistem kütüphanleridir. Örneğin SQLite local bir veritabanı oluşturma imkanı tanır. Opengl/es grafik işlemleri için gerekli kütüphanedir.

<h4>Android Runtime :</h4> Java ile yazılmış çekirdek kütüphaneler ve işletim sistemini donanımdan ayıran sanal makine bulunur.

<h4>Linux Kernel :</h4> Android mimarisinin en alt katmanıdır. Donanım sürücüleri burada bulunur. Örneğin kamera sürücüsü , güç yönetimi... <br><br><br>



<h2>Android'in Gelişimi</h2>

- <strong>Android 1.0 (Apple Pie HTC Dream) : </strong>  Kamera desteği , wi-fi,bluetooth,browser,alarmlı saat ,youtube ...

- <strong>Android 1.1 (Banana Bread ) : </strong> Sistem hataları düzeltildi, api geliştirildi.

- <strong>Android 1.5 (Cupcake) : </strong> Kamera kaydı, video gösterimi, Picasa,Widget'ları kişiselleştirebilme, animasyonlu ekran özellikleri... 

- <strong>Android 1.6 (Donut) : </strong> Ekran çözünürlüğünün yükseltilmesi , geliştrililmiş android market ,galeride çoklu silme...

- <strong>Android 2.0-2.1 (Eclair) : </strong> html5,bluetooth 2.1 , sanal klavye ,  geliştirilmiş google maps , arayüz özelleştirme...

- <strong>Android 2.2 (Froyo) : </strong> 720p ekran çözünürlüğü, usb bağlantı, wi-fi tarama , flash player 10.1 ...

- <strong>Android 2.3 (Ginger bread) : </strong> Çoklu kamera ve çoklu dokunmatik desteği , video arama ...

- <strong>Android 3.0 (Honey comb) : </strong> sadece tabletlere özel sürümümü (şuan hem telefonlara hem tabletlere uyumlu tek sürüm yayınlanıyor)

- <strong>Android 4.0 (Ice cream sandwich) : </strong> Yüz tanıma fonksiyonları, NFC ile dosya paylaşımı...

- <strong>Android 4.1 (Jelly bean) : </strong> Aynı anda iki uygulama açma , takılmadan kayan ekran, enerji verimliliği , performans...

- <strong>Android 4.4 (Kitkat) : </strong> Görsel arayüzde bir çok değişiklik, ram optimizasyonu , Dalvik alternatifi ART sanal makinası...

- <strong>Android 5.0 (Lollipop) : </strong>

- <strong>Android 6.0 (Marshmallow) : </strong>

- <strong>Android 7.0 (Naugat) : </strong>

- <strong>Android 8.0 (Oreo) : </strong>

- <strong>Android 9.0 (Pie) : </strong>

- <strong>Android 10.0 (10) : </strong> 3 eylül 2019

- <strong>Android 11.0 (11) : </strong> 8 eylül 2020

**Not :** Her android versiyonu bir api numarası ile gelir.

**Not :** Uygulama oluşturulurken minumum api belirlenir (sonradan değiştirilebilir). Uygulamamızı bu api numarasının altında android versiyonu yüklü telefonlar kullanamaz.

**Not :** Belirlediğimiz minumum api'den sonra gelen özellikleri kullanamayız. (Kullanabiliriz ama bir çok test yapmamız gerekir önceki verisyonlarda çalışıyor mu diye)
<br><br><br>


<h2>Bilinmesi Gerekenler</h2>

<h4>Xml</h4>

- Android'te tasarım ve veri kaynağı olarak xml(extensible markup language) kullanılır.
- Xml veri taşıma standardıdır.(farklı sistemler arasında ortak dil olarak kullanılır)
- Aynı zamanda bir işaretleme,görüntüleme dilidir. (Android'te bu amaçla kullanılır)
- Xml ile kendi etiketlerimizi (tag) oluşturabiliriz. (Android için kullanılan etiketler bu sayede tanımlanmıştır)
- Her xml dosyasında sadece bir kök(root) eleman bulunabilir. Bu kök içerisinde aynı düzeyde elemanlar tanımlanabilir.

<h4>Java</h4>

- Andorid'te tasarımlara işlev kazandırmak içim java pogramlama dili kullanılır. Alternatif : kotlin

**xml ile java kodları arasındaki bağlantı R.java konfigürasyon dosyası üzerinden sağlanır.**


**Not :** Java ile android uygulamalar geliştirebilmek için jdk(java development kit) ve android sdk(software developtment kit) sistemde kurulu olmalıdır.

**Not :** Bu dersin kapsamı dışında olan bir çok android uygulama geliştirme alternatifi bulunmaktadır.

<hr><hr>


<h1  id="hafta2">Hafta 2</h1>

- Kullanıcının gördüğü arayüzlere Activity denir. Bir class ın Activity olabilmesi için AppCompatActivity classını extend etmesi gerekir.
- Her activity onCreate method undan çalışmaya başlar.
- setContentView() methodu ile Activity nin hangi xml dosyası ile çalışacağı set edilir.
- Android uygulamalarının 3 ana parçası bulunur. AndroidManifest.xml  dosyası , java  ve res  klasörleridir.
- AndroidManifest.xml : uygulamanın genel konfigürasyon dosyasıdır. İzinler,uygulama ikonu , Activityler, Intendler,tema vs ... burada tanımlıdır.
- java klasörü : tüm java kodları burada bulunur.
- res klasörü  : görüntü,ses,uygulamanın kullandığı metinler,arayüz tasarımları , renk bilgileri... kısaca uyugulamanın kullandığı tüm kaynaklar buradadır.
- res klasörü altında bulunan mipmap klasöründe aynı görüntünün faklı çözünürlükte 6 kopyası bulunur. Uygulamanın açıldığı ekranın çözünürlüğüne göre uygun olan otomatik olarak    seçilir.
- res klasörü altında bulunan values klasöründe uygulamanın metinsel verileri tutulur.
- res klasörü altında bulunan layout klasöründe arayüz tasarımları bulunur.
- java kodunda R sınıfı ile res klasörü arasında bağlantı kurulur.
- Gradle uygulama geliştirme sürecini otomotize eden bir araçtır. Örneğin uygulamamızda kullanacağımız bir kütüphaneyi gradle a belirtir. Gradle otomotik olarak indirip uygulamaya dahil eder.
- Ekranda görünen her nesne bir view nesnesidir. Bir view elamanına tıkladığımızda eğer varsa onClick methodu tetiklenir.
- Intendler activiteler arası geçiş yapan ayrıca veri taşıyabilen nesnedir.


<hr><hr>
<h1  id="hafta3">Hafta 3</h1>

- View nesnelerine (TextView,EditText,Button...)  setOnClickListener() methodu ile dinleyici bir sınıf set edebiliriz.
- setOnClickListener() methodu parametre olarak View.OnClickListener interface'sini implemente eden bir sınıf alır.
- View nesnesine tıklandığında bu sınıfa ait olan onClick methodu tıklanan view nesnesini parametre alarak çağrılır.
- Kısaca view nesnesine tıklandığında dinleyici sınıfın onClick methodu çağrılır.

Bu örnekte dinleyici sınıf anonim olarak tanımlanmış

```
buttonComputeMass.setOnClickListener(new View.OnClickListener() {
    @Override
    public void onClick(View view) {
        
    }
});
```

- Hocanın CalculatorActivity'de uyguladığı yöntem bundan faklı bir şey değil.Nesnelere dinleyici sınıf set etmek için setOnClickListener() methoduna this parametresi  gönderiyor. This CalculatorActivity'i referans ediyor.CalculatorActivity'de View.OnClickListener interfacesini implemente eden bir sınıf olduğundan değişen bir şey olmuyor.


<hr><hr>
<h1  id="hafta4">Hafta 4</h1>

- Android cihaz üreten bir çok üretici firma olduğundan piyasada çok faklı çözünürlükte android cihazlar bulunmaktadır.
Bu nedenle uygulama tasarımlarının responsive yani cihaz çözürlüğüne göre boyutlanması gerekir. Bu amaçla linearLayout,
RelativLayout,FrameLayout,Constraintlayout... gibi bir çok layout çeşidi oluşturulmuştur. Tasarım amacına uygun olarak 
istenen layout çeşidi ile tasarım yapılabilir.

<h4>LinearLayout</h4>
    
- Elemanlar yatay veya dikey olarak konumlanırlar.
- Eğer orientation niteliğine vertical değeri verilirse dikey , horizontal değeri verilirse yatay olarak sıralanırlar.
- Her satıra veya her stuna sadece bir eleman yerleşebilir.
- Diğer bir önemli özelliği ise layout_weight'dir. Bu özellik ile elemanların kaplayacağı alan ağırlık  olarak verilir.
Örneğin yatay sıralanan bir linearLayout'ta 2 eleman olsun. 1.elmanın layout_weight değeri 1  olsun. 2.elemanın laout_weight
değeri 2 olsun. Bu durumda ekran yatayda üçe eşit parçaya bölünür. Birince elemana 1 parça 2.elemana ise 2 parça verilir.
Not : elemanların genişlik değeri 0dp olmalıdır. 
Not : Benzer mantık dikey linearLayout için de geçerlidir.


<h4>ConstraintLayout</h4>

- Her eleman kendisine verilen constraint(sınır) değerlerine göre konumlandırılır.


<h4>RelativeLayout</h4>

- Her eleman diğer bir elemana veya ekranın kenar ve köşelerine göre göreceli olarak konumlandırılır.

- <strong>layout_above :  </strong> Hangi görsel öğenin id’si verilmişse onun üstünde görünür
- <strong>layout_below :  </strong> Hangi görsel öğenin id’si verilmişse onun altında görünür
- <strong>layout_toLeftOf :  </strong> Hangi görsel öğenin id’si verilmişse onun solunda görünür
- <strong>layout_toRightOf :  </strong> Hangi görsel öğenin id’si verilmişse onun sağında görünür <br><br>

- <strong>android:layout_alignParentBottom:</strong> İçine koyulduğu layout’un en altına yerleşmesine yarar. (true-false)
- <strong>layout_alignParentLeft:</strong> İçine koyulduğu layout’un en soluna yerleşmesine yarar. (true-false) 
- <strong>android:layout_alignParentRight:</strong> İçine koyulduğu layout’un en sağına yerleşmesine yarar. (true-false)
- <strong>android:layout_alignParentTop :</strong> İçine koyulduğu layout’un en üstüne yerleşmesine yarar. (true-false)
- ...






<h4>FrameLayout</h4>

- Ekran 9 parçaya bölünür. Elemanların hangi parçaya yerleşeceği layout_gravity özelliği ile belirtilir.
  örneğin : layout_gravity = "bottom|right"  özelliği elemanı 9.parçaya yerleştirir.
  
  
<h4>GridLayout</h4>
 
 - Ekran matris yapısı gibi hücrelere bölünür. Elemanlar kendilerine verilen satır ve stun numarasına göre konumlandırılır.
 örneğin : layout_column="0" layout_row="0" ile eleman 1. hücreye yerleştirilir.
 
 
<h4>TableLayout</h4>
 
 - Html'deki table yapısına benzerdir. Tabloya satır eklemek için ```<TableRow>``` etiketi , satırsaki elemanın ağırlığını belirlemek için ise layout_span özelliği kullanılır.
 


<hr><hr>
<h1  id="hafta5">Hafta 5</h1>

<h4>Intend </h4>

- Activity'ler arası geçiş
- Activity'ler arası veri transferi
- Broadcast Receiver çağırma
- Service çağırma
- Sistemde bulunan diğer uygulamaları çağırma (sms,browser,mail,sosyal medya...) 
- ... gibi amaçlar ile kullanılır.

<strong>Not : </strong> Her uygulama faklı özelliklere sahip olduğundan intend tipimiz ve  intend'e set etiğimiz veriler , intendimizi
karşılamasını istediğimiz uygulamaya uygun olmalıdır.

<strong> Intend ile başka bir activity'den veri alıp geri dönebiliriz</strong>

- startActivityForResult() ile veri almak istediğimiz Activity'e geçiş yapılır.
- Bu method gerekli intend ve request_code paramtrelerini alır.
- request_code herhangi bir int sayıdır ve doğrulama amacıyla kullanılır. <br><br>
- setResult() ile veri aldığımız activity'den geri döneriz.
- Bu method gerekli datayı set ettiğimiz intend ve sabit int bir değer (ör :RESULT_OK) paramtrelerini alır. <br><br>
- Gelen datayı karşılamak için onActivityResult() override edilir.
- requestCode ve ResultCode parametreleri ile gelen datanın istekte bulunduğumuz data olup olmadığı kontrol edilir.
- kontrol geçilirse data parametresi istekte bulunduğumuz datadır.



<hr><hr>
<h1  id="hafta6">Hafta 6</h1>

<h4>Permissions</h4>

Api 23 (Marshmallow) öncesi tüm izinler uygulama indirilirken verilirdi. Api 23 ve sonrası için başlangıç izinleri yerine
anlık izinlere geçildi.

<h5>İzin Algoritması</h5>

Örneğin uygulama kameraya erişmek istesin.

- 1- Öncelikle izin kontrolu yapılır. (Kullanıcı bu uygulama için daha önceden kamera erişim izni vermiş mi ?)
- 2- Platform kontrolü yapılır. (Api 23 öncesi mi sonrası mı ? - buna şuan(2020) gerek yok- yerine ActivityCompat geldi)
- 3- Gerekli izin ile ilgili açıklama yapılır (isteğe bağlı)
- 4- izin isteğide bulunulur
- 5- izin isteğine verilen yanıt kontrol edilir. (izin verilmişse kameraya erişilir.) <br><br>

- 1- checkSelfPermission()
- 2- if(Build.VERSION.SDK_INT >=23)  
- 3- shouldShowRequestPermissionRationale() --> Kullanıcının kafası karışıksa true döner - açıklama yaparız. <br>
<stong>Kafası karışık olma durumu :</strong><br>
Uygulama ilk kez çalıştırılıyorsa false döner . (kullanıcının kafası karışık değil) <br>
Uygulama 2.kez veya daha fazla çalıştırılmışsa <br>
--> Eğer izne daha önceden olumsuz yanıt verilmiş ise ve bir daha sorma **işaretlenmişse** false döner . (Kafa karışık değil) <br>
--> Eğer izne daha önceden olumsuz yanıt verilmiş ise ve bir daha sorma **işaretlenmemişse** true döner (Kafa karışık -açıklama yaparız) <br>
- 4- requestPermissions() --> gerekli izinler dizi olarak verilir. Ayrıca doğrulama amaçlı reuest_code verilir.
- 5-onRequestPermissionResult()-->  verilen tüm izinleri bu method karşılar. Bu nedenle override edilmesi gerekir. Request code ile kullanıcının verdiği iznin istediğimiz izin olup olmadığı kontrol edilir.

Not : Anlık izinler sadece dangerous permission için gereklidir.  Ör : kamera,konum,galeri…



<hr><hr>
<h1  id="hafta7">Hafta 7</h1>
<h4>SQLite</h4>

- SQLite local veritabanı oluşturmak için kullanılan kütüphanedir. Android mimrasine gömülü olarak geldiğinden ekstra olarak uygulamaya eklemeye gerek yoktur.

- Local veritabanı : dışarıya açık olmayan , verilerin cihaz hafızasında tutulduğu  , uygulamaya özel olan veritabandır.

- Bir SQLite veri tabanı oluşturmak için **SQLiteOpenHelper** soyut sınıfını miras alıp ihtiyacımıza uygun olarak özelleştiririz.

- Veritabanının adı bu sınıfın Constructor'ına verilir.

- onCreate() methodu sadece uygulama yüklenirken bir kere çalıştırılan methoddur. Bu nedenle ihtiacımız olan tabloları bu method içerisinde oluştururuz.

- Tablo oluşturma, tabloya eleman ekleme ,silme,güncelleme... işlemleri için **SQLiteDatabase** nesnesi kullanılır.

- **ContentValues** nesnesi, veritabanına eleman ekleme,güncelleme için gerekli veri formatıdır.

- **Cursor nesnesi**, sorguya göre veritabanından çekilen kayıtları tutmak için kullanılır.



<hr><hr>
<h1  id="hafta8">Hafta 8</h1>
<h4>Google Maps</h4>

-Ugulamamızda google maps servisini kullanabilmek için google'dan bir api key almamız gerekir.

- Andorid'de google maps için hazır template bulunur. Bu template seçildiğinde bir kaç dosya oluşur ve konfigurasyon ayarlanır.
  Values klasöründe oluşan google_maps_api.xml  dosyasında api key oluşturmak için uygulamaya özel bir url bulunur.
  Bu url den api key alınır ve  aynı dosyada bulunan your_key_here yazan yere yapıştırılır. Uygulama artık maps servisini kullanmaya hazır durumdadır.
  
- **onMapReady()** harita hazır duruma geçtiğinde çalışan mehoddur. Bu method içerisinde örneğin kullanıcının konumunu gösterebiliriz.

- **GeoCoder :** enlem boylamı adrese(sokak,caddde,bölge...) veya tersi işlem yapmaya yarayan sınıftır. Bu sınıfın **getFromLocationName()** methodu, verilen string ifadeye 
göre Address listesi döndürür. Address listesi bir int parametre ile sınırlandırılabilir. Örneğin 2 parametresini verirsek string ifadeye göre en populer 2 address döner.

- **Address :** enlem,boylam,ülke ismi,sokak adı,cadde adı,posta kodu... gibi değerleri tutan sınıftır.

- **LatLng :**  enlem ve boylamı tutan  sınıftır.

- mMap nesnesi, harita üzerinde işlemler yapmak için **GoogleMaps** referansıdır. Harita hazır olduğunda haritamız bu referansa initialize edilir.

- mMap nesnesinin: <br>
**addMarker()**  methodu ile herhangi bir konuma marker ekleyebiliriz. MarkerOption parameteresi alır. <br>
**moveCamera()** methodu ile kamerayı başka konuma yönlendirebiliriz.  <br>
**setMapType()** methodu ile haritanın tipini değiştirebiliriz. <br>
**setMyLocationEnabled()** methodu ile kullanıcının konumunu gösterebiliriz. (izin gerekli) 




<hr><hr>
<h1  id="hafta9">Hafta 9</h1>
<h4>JSON</h4>

- Json (JavaScript Object Notation) : veri taşıma formatıdır.
- Hem makineler hem de insalar için kolay anlaşılan bir yapısı vardır.
- Programlama dillerinden bağımsızdır ve bir çok programlama dili tarafından desteleniyor.
- 2 veri yapısı kullanır. <br>
  1 : Anahtar-değer iklilerini içeren bir koleksiyon (Json object) <br>
  2 : Sadece değerler içeren bir dizi

- Bir Json objesi {} dir. Arasında anahtar-değer ikilileri bulunur.

- Bir Json dizisi [] dir. Arasında dizi değerleri bulunur.

- Değerler bir string,number,true,false,null,Json object , Json dizisi olabilir.

- Bir Json verisini internetten çekebiliriz. Bunun için URI connection nesnesi kullanılabilir (şuan tercih edilmiyor) veya
  Bu amaçla olşuturulmuş bir kütüphaneyi uygulamamıza ekleyebiliriz. Örneğin : Volley kütüphanesi
  
- İnternnetten json verisi çekmek için internet izni olması gerekir. 
  ```<uses-permission android:name="android.permission.INTERNET"/> android manifeste eklenir.```
- Verilerin düzngün çkilebilmesi için  android manifest application tagının altına ```android:usesCleartextTraffic="true"``` eklenir.
- volley kütüphanesini kullanabilmek için  ``` implementation 'com.android.volley:volley:1.1.1'```   satırı   build.gradle(Module) dependencies altında eklenir.


<h5> Volley kütüphanesi :</h5> 

- **StringRequest  :** bir client olarak sunucudan json verisi çekmek için kullanılır. Dönen değer bir RequestQueue 'e eklenmesi gerekir.

- **parametreler :** request methodu , veri çekilecek adres(url) , gelen cevapları dinleyen ResponseListener nesnesi, hataları dinleyen ErrorListener nesnesi

- ResponseListener'ın onResponse methoduna gelen veriler parametre olarak atanır. Json verisinin parse işlemi
  bu method içerisinde gerçekleşir.
  
- parse işlemi gelen json verisine ögre değişir.

- Örneğin Json verimiz bu şekildeyse : 

```
- {
  "Companies": [
    {
      "Heading": "Cloud NX",
      "Detail": "For cloud solution, waiting for you",
      "ImageURL": "http://web.karabuk.edu.tr/yasinortakci/dokumanlar/web_dokumanlari/image1.png"
    },
    {
      "Heading": "Microsoft",
      "Detail": "Best solution for system programs",
      "ImageURL": "http://web.karabuk.edu.tr/yasinortakci/dokumanlar/web_dokumanlari/image2.png"
    },
    {
      "Heading": "Oracle",
      "Detail": "Spatial database is supported now",
      "ImageURL": "http://web.karabuk.edu.tr/yasinortakci/dokumanlar/web_dokumanlari/image3.png"
    }
  ]
} 

```
- onResponse() içerisine bu kodu yazarak ilk nesnenin değerlerini alabiliriz.

```
- JSONObject jsonObject=new JSONObject(response);
  JSONArray jsonArray=jsonObject.getJSONArray("Companies");
  
  //Bu kod parçasıyla dizide bulunan ilk Json objesi alınır. (loop ile tüm veriler alınabilir.)
  JSONObject company=jsonArray.getJSONObject(0);
  String heading = company.getString("Heading");
  String detail = company.getString("Detail");
  String imagerUrl = company.getString("ImageURL");
                  

```



<h5>Picasso kütüphenesi : </h5>

- İmage indirmek için kullanılan kütüphanedir. 
implementation 'com.squareup.picasso:picasso:2.71828'

- **kullanım :** 
```Picasso.get().load("http://i.imgur.com/DvpvklR.png").into(imageView);```





  
<hr><hr>
<h1  id="hafta10">Hafta 10</h1>
<h4>JSoup</h4> 
  
- Html kodunu parse eden kütüphanedir. 

- Html kodu url üzerinden JSoup kütüphanesi veya volley gibi bir kütüphane kullanılarak çekilebilir.

- JSoup ile url'den veri çekme : <br>

``` 
Document doc = Jsoup.connect("https://en.wikipedia.org/").get();
``` 

- Elimizde String tipinde html kodu olduğunu düşünelim.(örn: volley ile çektik) Öncelikle Document nesnesine dönüştürmeliyiz. <br>

```
String html = "html kodu";
Document doc = Jsoup.parse(html);
```

- Document nesnesinden ihtiyacımız olan Elementleri(tagları) seçmek için css seçicileri (css selector) kullanırız.

```
Elements elementler=doc.select("css seçici komutu");
```

- elementler css seçici komutumuza göre Document nesnesinden seçilen tagları tutan dizidir.

- Element nesnesine ait methodlar ile tagdan istediğimiz veriyi çekebiliriz. Veya varsa alt elementleri seçebiliriz.

- örn : ```element.text()``` ile tag'a ait metin alınabilir.

- örn : ```element.attr("href")```  tag'ın href niteliğinin değeri alınabilir.

- örn : ```element.nextElementSibling();```  aynı düzede bulunan diğer tag'a geçer.

- örn : ```element.children();``` element'in içinde bulunan elementleri döner. (bir alt elementler)


- css seçici komutu, html koduna ve seçilmek istenen elementlere göre değişir.

- örn : ```doc.select("span.containerDuyuruBaslikLabel");```  class'i containerDuyuruBaslikLabel olan span tagları seçilir.

- örn : ```doc.select("div.HaberBoxHeader a");```  class'i HaberBoxHeader olan divlerin altında bulunan 'a' taglari seçilir. 

- [Selector Syntax](https://jsoup.org/cookbook/extracting-data/selector-syntax)

- [Element sınıfı](https://jsoup.org/apidocs/org/jsoup/nodes/Element.html)


<hr><hr>
<h1  id="hafta11">Hafta 11</h1>
<h4>AsyncTask</h4> 


- AsyncTask, UI thread'i dondurmamak için bazı işlemleri (ör : 10 sn'e süren download işlemi) arka planda (başka bir thread'de) yapan abstract-generic bir sınıftır.

- Bu sınıfı kullanmak için miras alır ve amacımıza uygun olarak özelleştiririz.

- **onPreExecute() :** thread execute edilince ilk çalışan methoddur. Gerekli ön işlemler bu method içerisinde yapılır. ör : progress bar oluşturma

- **doInBackground() :** arka planda yapılması istenen işlem (ör : bir metni indirme) bu mehod içerisinde yapılır.

- **onProgressUpdate() :** doInBackground() methodu ile birlikte çalışır. Yapılan işin miktarı gösterilir. Ör : yapılan işin %10'u tamamlandı. publishProgress() methodu ile çağrılır.

- **onPostExecute():** İşlem tamamlandığında çalışan methoddur. (doInBackground() methodu bittiğinde çalışır.doInBackground() geri dönüş değeri bu methoda paramtre olarak verilir. )

Not : AsyncTask sınıfı generictir. <> arasına alınan parametreler override edilen methodların parametrelerini belirler.

Ör : AsyncTask<String,Integer,String>

- 1.parametre(String) : doInBackground() methodunun parametresidir. 
- 2.parametre(Integer): onProgressUpdate() methodunun parametresidir.
- 3.parametre(String) : doInBackground() methodunun geri dönüş tipi ve onPostExecute() methodunun paramtresidir.




  
  


<hr><hr>
<h1  id="hafta12">Hafta 12</h1>
<h4>Fragment</h4>


- Fragment kendi layout'u ve sınıfı olan , activity'nin görevlerini yerene getirebilen,  activity'e benzer yapıdır.

- Activity'e göre çok daha az kaynak tüketir ve daha performanslı çalışır.

- Fragmentler bir Activity'e bağlı olarak çalışırlar. Tek başına çalışamazlar.

- Bir Activity birden fazla fragment'e sahip olabilir.

- Fragment bir view'dır. Bir fragment view 'a hangi class ile çalışacağı belirtilmelidir. 

- Fragment bir activity değildir. Bu nedenle fragment class içersinden, activitiye özel methodlara doğrudan erişilemez.

- Fragmentler statik veya dinamik olarak yüklenebilirler.

- statik : fragment activity başlatıldığında yüklenir.

- dinamik : fragment çalışma zamanında, örneğin bir butona tıklandığında oluşturulur.

- onCreateView()  :  fragmentin layoutun'u döndürür. Layout ile ilgili gerekli initialize işlemleri bu method içerisinde yapılır.



- ***Activity içerisinden dinamik olarak fragment yükleme :*** 

```
LoginFragment loginFragment = new LoginFragment();
getSupportFragmentManager().beginTransaction().add(R.id.container,loginFragment).commit();
```


- ***Fragment içerisinden dinamik olarak fragment yükleme(değiştirme) :*** 


```
RegisterFragment registerFragment = new RegisterFragment();
getFragmentManager().beginTransaction().replace(R.id.container,registerFragment).commit();
```

- registerFragment : yüklenecek fragment
- R.id.container : fragmenin yükleneceği alanın id si


- Not : eğer aynı container'a bir fragment varken add ile başka fragment eklersek öncekinin üzerine eklenir.Bu nedenle replace methodu kullanılır.





<hr><hr>
<h1  id="hafta13">Hafta 13</h1>
<h4>Fragment Devamı</h4>

<h5>Fragment ile activity arasında veri alışverişi :</h5>

- Önemli bilgi : Bir Activity başlatıldığında içerisinde tanımlı fragmentlerin **onAttach()** methodu çalışır. Kapatıldığında ise **onDetach()** methodu çalışır.
  Bu methodların **context** parametresine, fragment hangi Activity'den yüklenmişse onun context'i atanır.

- Activity'e fragmentten veri göndermek için Activity'e ait bir method kullanılabilir. Veri bu methoda parametre olarak verilir.
 (Color uygulamasında bu yöntem kullanılarak renk verisi alınıyor.)

- Peki fragment'ten Activity'e ait bir methodu nasıl çağırırız ?  Bunun için onAttach methoduna atanan context parametresini kullanırız.

- Kısaca onAttach methodunda Activity'nin context'i alınır. Bu context ile Activity'nin methodları kullanılarak veri gönderilir.

**Ek bilgiler :** <br>

- interface sınıflar için bir arayüz - çatı görevi görür.

- Eğer bir sınıf bir interface'yi implemente eder ise onun methodlarını tanımlamak(sağlamak) zorundadır.

- Eğer bir sınıf bir interfaceyi implemente eder ise bu interface'nin referansı bu sınıfın nesnelerinin referansı olarak kullanılabilir.(polymorphism)



<h5>Fragmentler(static olanlar) arası veri alışverişi : </h5>


- Veri gönderen fragment, veriyi Activity'e ait methoda parametre olarak verir. (önceki örnekte olduğu gibi)

- Activity'de veri gönderilecek fragmenti id'sine göre bulur  ve veriyi bu fragment'e ait methoda parametre olarak verir.


id sine göre fragmenti bulma örnek kod : 

```
ReceiverFragment receiverFragment =(ReceiverFragment) getSupportFragmentManager().findFragmentById(R.id.fragment_reciever);
receiverFragment.setName(name);
```



<h5>Fragment ile dinamik olarak oluşturulan fragment arası veri alışverişi :</h5>

Yukarıdaki örneğe benzerdir ama veri gönderilecek fragment, id'sine göre bulunmaz. newInstance() methodu ile oluşturulur.

Veri ise bu newInstance() methoduna parametre olarak verilir.

Örnek kod :

- new instace ile fragment örneği oluşturma <br>

```
ReceiverFragment receiverFragment=ReceiverFragment.newInstance(name);
```
- fragment'in dinamik olarak yüklenmesi <br>
```
getSupportFragmentManager().beginTransaction().replace(R.id.fragment_container,receiverFragment).commit();
```


**- veri alan fragment :** <br>

- new instance methodu :

```
public static ReceiverFragment newInstance(String name) {
        ReceiverFragment fragment = new ReceiverFragment();
        Bundle args = new Bundle();
        args.putString("name", name);
        fragment.setArguments(args);
        return fragment;
}
```

- veri, onCreate'de bu kod ile alınır ve global değişkene atanabilir. <br>
```name = getArguments().getString("name");```

















 
  


    















































