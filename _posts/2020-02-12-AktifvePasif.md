---
layout: post
title: Sızma Testlerinde Aktif Ve Pasif Bilgi Toplama
excerpt: "Postlar "
categories: [code]
comments: true
---
<center><h1>Sızma Testlerinde Bilgi Toplama</h1></center><br>

<p>Gündelik hayatımızda yapmak istediğimiz eyleme göre, sonuca ulaşmak için farklı kaynaklardan bilgi alışverişi yaparız. Örnek olarak bilmediğimiz bir yere giderken gidilecek yer hakkında bigli edinmeye çalışırız.Nasıl gidebiliriz, hangi yollardan gidebiliriz,ya da en kısa sürede oraya nasıl ulaşıabiliriz gibi araştırmalar yaparız.Ya da yurtdışında bir ülkeye gitmek istiyoruz. O ülkeye gidebilmek için ne yapmamız gerekir, hangi evraklar gereklidir ya da o ülkenin kültüründe neler vardır gibi araştırmalar yaparız.Yani gidilecek yer ile ilgili bilgi edinmeye çalışırız.Sosyal hayatımızda olduğu gibi, sızma testlerinde de ilk olarak yapılması gereken şey bilgi toplamaktır. Site hakkında bir araştırma yapmadan, bilgi sahibi olmadan sızma girişiminde bulunmak pek de akıllıca bir seçenek değildir. Bir sızma testinde hedef sistem hakkında bilgi toplamak, o sistemi daha iyi tanımak ve bunun sonucunda bir yol haritası belirlemek için oldukça önemlidir.Örnek vermek gerekirse sızılmak istenilen sunucunun kullandığı güvenlik duvarının ismini öğrenmek, o duvarın ne gibi zafiyetler barındırdığı hakkında bilgi araştırması yapabilmenizi sağlayacaktır. İki tür bilgi toplama yönetimi vardır<br>.
<ul type=”disc”>
<li>Pasif Bilgi toplama </li
<li>Aktif Bilgi toplama </li>
</ul></p><br><br>

<h3>Pasif Bilgi Toplama Nedir?</h3><br>

<p>Sızılmak istenilen hedef hakkında internet üzerinden bilgi toplama yöntemidir. Hedef sistemin sunucusu ile bire bir iletişim kurulmadığı için, karşı tarafta herhangi bir log kaydı oluşturmaz. Yani herhangi bir iz bırakmadan bilgi toplanılan yöntemdir.Açık kaynak istihbaratı olarak da adlandırılabilir.</p><br><br>

<h3>Aktif Bilgi Toplama Nedir?</h3><br>

<p>Sızılmak istenilen hedef sistem ile bire bir iletişime geçerek sağlanan bilgi toplama yöntemidir.Pasif bilgi toplama aşamasına nazaran daha çok ve işe yarar bilgi aktif bigli toplama ile elde edilir. Sistem ile direkt bağlantı sağlayarak veri alış verişi gerçekleştiği için karşı sunucuda log kayıtları oluşturur.</p><br><br>



<center><h1>DNS Nedir?</h1></center><br>

<p>Sanal dünyada sistemlerin birbirleri ile iletişim kurabilmelerine yarayan numerik rakamlardan oluşan adresler bulunmaktadır. Bu adresler bir takım sayı dizisinden oluşmaktadır.Bu numaralar sistemin bir nevi kimlik numaralarıdır. Kullanıcının her sistemin adresini numerik olarak akılda tutmasının zor olacağından dolayı DNS’e ihtiyaç duyulmuştur. DNS sunucusu, kullanıcının girdiği alan adını bünyesinde bulunan serverlarda bu alan adına karşılık gelen bir IP adresi olup olmadığını kontrol ederek yönlendirme yapar. Örnek olarak siz arama motoruna Google.com yazdığınızda DNS sunucuları Google.com’a karşılık gelen IP adresine sizi yönlendirir. Arama çubuğuna www.google.com yazmak ile 172.217.169.100 (Google IP Adesi) yazmak aynı şeydir. Başta söylediğimiz gibi bu numerik olan rakamları akılda tutmak, isim olarak akılda tutmaktan daha zor olduğu için DNS protokolünü kullanmak, kullanıcı açısından daha basittir.</p>


<h3>DNS Kayıt Tipleri</h3><br>

<p>DNS kayıtları zone file dosya türleri kapsamına girmektedir. Domain ayarlarının yapılabilmesi için DNS sağlayıcınızının değiştirilebilir kayıtlarıdır.Bu kayıtlar aşağıda belirtilmiştir.</p><br><br>

<strong>A (Host) Kayıtları  </strong> : Host adının karşılık geldiği IP adresine yönlendirmeye yarayan kayıt türüdür. Girilen domain adınızın hangi IP adresine karşılık geldiğini belirtmeye yarar.<br><br>
<strong>CNAME Kayıtları</strong>: Birden fazla kullanılan host adlarını belirlenen bir adrese yönlendirmeye yarar.<br><br>
<strong>Mail Exchange (MX) Kayıtları </strong>: Alan adınıza gönderilen e-posta iletilerinin hangi sunucuya yönlendirileceğini belirlemek için kullanılan kayıt türüdür.<br><br> 
<strong>NS Kayıtları</strong>: Bağlantı halinde olan DNS serverları tanımlayan kayıt türüdür.Alan adının hangi server üzerinde çalışacağını belirtmeye yarar.<br><br>
<strong>Pointer (PTR) Kayıtları</strong>: A kayıtlarının tam tersi olarak çalışırlar. IP adresinin hangi isme karşılık geldiğini belirtmeye yarar. <br><br>
<strong>Text (TXT) Kayıtları</strong>: Herhangi bir metni bir hostname ile ilişkilendirmeye yarar. Standart bir TEXT dosyasıdır.<br><br>
<strong>AAA (Adres) Kayıtlar</strong>: A kaydı ile aynı işlemi yaparlar. Tek farklı ipv6 için kullanılıyor olmasıdır.<br><br>
<strong>SOA (Start Of Autory) Kayıtları</strong>: DNS Server’in hangi Zone’dan sorumlu olduğunu gösteren kayıt türüdür. Zone bilgisi,donanım bilgisi,versiyonu, name server gibi bilgiler bu kayıt içinde bulunur.<br><br>

<h1><center>TCP/IP ve OSI Nedir?</center></h1><br>

<p>TCP/IP (Transmission Control Protocol/Internet Protocol)   ve OSI (Open  Systems Interconnection) internet ortamında sistemlerin birbirleri ile iletişim halinde bulunabilmesine ve veri alışverişi yapabilmelerine olanak sağlayan iletişim protokolleridir. Dünya genelinde en çok kullanılan iletişim protokollerinin başında TCP/IP gelmektedir.Birçok protokolün bir araya gelmesiyle oluşan TCP/IP  4 katmandan  OSI ise 7 katmandan oluşmaktadır. Makalenin bu kısmında ilk olarak OSI Katmanları incelenmiştir. </p><br><br>
<h3>OSI Katmanları</h3><br>

<img src="/resimler/bilgi toplama/ip/osi.jpg" alt="osi"><br>
<strong>Application Layer(Uygulama Katmanı)</strong>:Kullanıcının bağlantıyı uygulamalar ile sağladığı  katmandır. Örnek olarak <br>Brovser:HTTP <br>File Transfer:FTP <br>Virtual Terminal:Telnet<br>E-Mail:SMTP.<br><br>
<strong>Presentation Layer(Sunum Katmanı)</strong>:Gelen veriyi sistemin okuyabileceği dile çevirir yani translation işlemleri bu katmanda yapılır. Şifreleme,şifre çözme, sıkıştırma ve açma işlemleri bu katmanda yapılır.Verinin güvenliğini bu katmanda böylece sağlamış olur.<br><br>
<strong>Session Layer(Oturum Katmanı)</strong>:Kullanıcının sistem üzerindeki oturum açma işlemlerinin yapıldığı katmandır.Oturumun açılması,yönetilmesi ve yetkilendirilmesi bu katmanda gerçekleşir.Haberleşmeyi ve gelen verinin eksik ya da hatalı olup olmadığını kontrol eder.Örnek olarak NFS,ASP,SQL ve Telnet bu katmanda çalışır. </strong><br><br>
<strong>Transport Layer(Taşıma Katmanı)</strong>:Veriyi segmentler halinde bölerek sınıflandırır.Gelen veriyi de sırasına göre birleştirmeyi sağlar.Karşı sistem ile ortak bir alış-veriş hızı belirler(Flow Control).Verinin karşı tarafa doğru iletilip iletilmediğini de kontrol eder.TCP ve UDP bu katmandadır.<br><br>
<strong>Network Layer(Ağ Katmanı)</strong>:Mantıksal ve Fiziksel adresleme işlemleri bu katmanda yapılır.Verinin nereye iletileceğini yönlendiriciler(Router) ile kararlaştırır. İletilen veri blokları paket olarak adlandırılır. IP bu katmandadır.<br><br>
<strong>Data Link Layer(Veri İletim Katmanı)</strong>:Ağ katmanından alınan verileri hatalarından arındırılmış olarak çerçeveler(frame) halinde fiziksel katmana gönderir.<br><br>
<strong>Physical Layer(Fiziksel Katman)</strong>:Gelen bit verilerini kablo,fiber ve wifi gibi aktarma yolları ile gönderir.<br><br>

<h3>TCP/IP Katmanları</h3><br>
 
<img src="/resimler/bilgi toplama/ip/tcpip.JPG" alt="tcpip"><br>
<strong>Uygulama Katmanı (Application Layer)</strong>: Farklı sunucular arasında gerçekleşen iletişimi sağlar. (HTTP,FTP,TELNET vb.)<br><br>
<strong>Taşıma Katmanı (Transport Layer)</strong>:Verinin nasıl gönderileceği belirlenir.TCP ve UDP protokolleri bu katmanda gerçekleşir.<br><br>
<strong>Ağ Katmanı (Network Layer)</strong>:IP katmanı olarak geçer. Uç sistem ile ağ arasındaki lojik arabirime ilişkin katmandır.<br><br>
<strong>Fiziksel Katman (Physical Layer)</strong>:İletişim ortamının özelliklerini,haberleşme hızını  ve kodlama şemasını belirler.<br><br>


<center><h1>Pasif Bilgi Toplama</h1></center>



<h3>Google İle Bilgi Toplama</h3><br>

Google üzerinden yaptığımız aramalarda bizlere girdiğimiz kelimelere göre karşımıza sonuçlar çıkarmaktadır. Bunun yanında Google bizlere Dork diye tabir edilen spesifik arama yapabildiğimiz operatörler sunmuştur. Bu operatörleri kullanarak hedef site hakkında birçok bilgiye erişmek mümkündür. Aşağıda bu operatörler ve ne işe yaradıkları hakkında bilgiler veilmiştir.<br><br>

<img src="/resimler/bilgi toplama/webs/site.JPG" alt="site"><br>
<strong>site:</strong> Bu operatör site: kısmına yazdığımız hedef site hakkında çıkan sonuçları bize sıralar. <br><br>

<img src="/resimler/bilgi toplama/webs/intitle.JPG" alt="intitle"><br>

<strong>intitle:</strong>Bu operatör girdiğimiz kelimeleri sayfaların başlığında bularak bize listeler.<br><br>

<img src="/resimler/bilgi toplama/webs/intitle.JPG" alt="intitle"><br>
<strong>filetype:</strong> Bu operatör arayacağımız dosya tipine göre bize sonuç sunmaya yarar.<br><br>









