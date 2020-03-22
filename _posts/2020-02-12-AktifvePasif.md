---
layout: post
title: Sızma Testlerinde Aktif Ve Pasif Bilgi Toplama
excerpt: "Postlar "
categories: [code]
comments: true
---
<center><h1>Sızma Testlerinde Bilgi Toplama</h1></center><br>

Gündelik hayatımızda yapmak istediğimiz eyleme göre, sonuca ulaşmak için farklı kaynaklardan bilgi alışverişi yaparız. Örnek olarak bilmediğimiz bir yere giderken gidilecek yer hakkında bigli edinmeye çalışırız.Nasıl gidebiliriz, hangi yollardan gidebiliriz,ya da en kısa sürede oraya nasıl ulaşıabiliriz gibi araştırmalar yaparız.Ya da yurtdışında bir ülkeye gitmek istiyoruz. O ülkeye gidebilmek için ne yapmamız gerekir, hangi evraklar gereklidir ya da o ülkenin kültüründe neler vardır gibi araştırmalar yaparız.Yani gidilecek yer ile ilgili bilgi edinmeye çalışırız.Sosyal hayatımızda olduğu gibi, sızma testlerinde de ilk olarak yapılması gereken şey bilgi toplamaktır. Site hakkında bir araştırma yapmadan, bilgi sahibi olmadan sızma girişiminde bulunmak pek de akıllıca bir seçenek değildir. Bir sızma testinde hedef sistem hakkında bilgi toplamak, o sistemi daha iyi tanımak ve bunun sonucunda bir yol haritası belirlemek için oldukça önemlidir.Örnek vermek gerekirse sızılmak istenilen sunucunun kullandığı güvenlik duvarının ismini öğrenmek, o duvarın ne gibi zafiyetler barındırdığı hakkında bilgi araştırması yapabilmenizi sağlayacaktır. İki tür bilgi toplama yönetimi vardır<br>.
<ul type="disc">
	<li><strong>Pasif Bilgi toplama </strong></li>
	<li><strong>Aktif Bilgi toplama</strong> </li>
</ul><br><br>

<h3><strong>Pasif Bilgi Toplama Nedir?</strong></h3><br>

<p>Sızılmak istenilen hedef hakkında internet üzerinden bilgi toplama yöntemidir. Hedef sistemin sunucusu ile bire bir iletişim kurulmadığı için, karşı tarafta herhangi bir log kaydı oluşturmaz. Yani herhangi bir iz bırakmadan bilgi toplanılan yöntemdir.Açık kaynak istihbaratı olarak da adlandırılabilir.</p><br><br>

<h3><strong>Aktif Bilgi Toplama Nedir?</strong></h3><br>

<p>Sızılmak istenilen hedef sistem ile bire bir iletişime geçerek sağlanan bilgi toplama yöntemidir.Pasif bilgi toplama aşamasına nazaran daha çok ve işe yarar bilgi aktif bigli toplama ile elde edilir. Sistem ile direkt bağlantı sağlayarak veri alış verişi gerçekleştiği için karşı sunucuda log kayıtları oluşturur.</p><br><br>



<center><h1>DNS Nedir?</h1></center><br>

<p>Sanal dünyada sistemlerin birbirleri ile iletişim kurabilmelerine yarayan numerik rakamlardan oluşan adresler bulunmaktadır. Bu adresler bir takım sayı dizisinden oluşmaktadır.Bu numaralar sistemin bir nevi kimlik numaralarıdır. Kullanıcının her sistemin adresini numerik olarak akılda tutmasının zor olacağından dolayı DNS’e ihtiyaç duyulmuştur. DNS sunucusu, kullanıcının girdiği alan adını bünyesinde bulunan serverlarda bu alan adına karşılık gelen bir IP adresi olup olmadığını kontrol ederek yönlendirme yapar. Örnek olarak siz arama motoruna Google.com yazdığınızda DNS sunucuları Google.com’a karşılık gelen IP adresine sizi yönlendirir. Arama çubuğuna www.google.com yazmak ile 172.217.169.100 (Google IP Adesi) yazmak aynı şeydir. Başta söylediğimiz gibi bu numerik olan rakamları akılda tutmak, isim olarak akılda tutmaktan daha zor olduğu için DNS protokolünü kullanmak, kullanıcı açısından daha basittir.</p><br>


<h3><strong>DNS Kayıt Tipleri</strong></h3><br>

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
<h3><strong>OSI Katmanları</strong></h3><br>



<img src="/resimler/bilgi toplama/ip/osi.jpg" alt="osi" widht="300px" height="300px"><br>



<strong>Application Layer(Uygulama Katmanı)</strong>:Kullanıcının bağlantıyı uygulamalar ile sağladığı  katmandır. Örnek olarak <br>Brovser:HTTP <br>File Transfer:FTP <br>Virtual Terminal:Telnet<br>E-Mail:SMTP.<br><br>
<strong>Presentation Layer(Sunum Katmanı)</strong>:Gelen veriyi sistemin okuyabileceği dile çevirir yani translation işlemleri bu katmanda yapılır. Şifreleme,şifre çözme, sıkıştırma ve açma işlemleri bu katmanda yapılır.Verinin güvenliğini bu katmanda böylece sağlamış olur.<br><br>
<strong>Session Layer(Oturum Katmanı)</strong>:Kullanıcının sistem üzerindeki oturum açma işlemlerinin yapıldığı katmandır.Oturumun açılması,yönetilmesi ve yetkilendirilmesi bu katmanda gerçekleşir.Haberleşmeyi ve gelen verinin eksik ya da hatalı olup olmadığını kontrol eder.Örnek olarak NFS,ASP,SQL ve Telnet bu katmanda çalışır. </strong><br><br>
<strong>Transport Layer(Taşıma Katmanı)</strong>:Veriyi segmentler halinde bölerek sınıflandırır.Gelen veriyi de sırasına göre birleştirmeyi sağlar.Karşı sistem ile ortak bir alış-veriş hızı belirler(Flow Control).Verinin karşı tarafa doğru iletilip iletilmediğini de kontrol eder.TCP ve UDP bu katmandadır.<br><br>
<strong>Network Layer(Ağ Katmanı)</strong>:Mantıksal ve Fiziksel adresleme işlemleri bu katmanda yapılır.Verinin nereye iletileceğini yönlendiriciler(Router) ile kararlaştırır. İletilen veri blokları paket olarak adlandırılır. IP bu katmandadır.<br><br>
<strong>Data Link Layer(Veri İletim Katmanı)</strong>:Ağ katmanından alınan verileri hatalarından arındırılmış olarak çerçeveler(frame) halinde fiziksel katmana gönderir.<br><br>
<strong>Physical Layer(Fiziksel Katman)</strong>:Gelen bit verilerini kablo,fiber ve wifi gibi aktarma yolları ile gönderir.<br><br>

<strong>TCP/IP Katmanları</strong><br>
 
<img src="/resimler/bilgi toplama/ip/tcpip.JPG" alt="tcpip"><br>
<strong>Uygulama Katmanı (Application Layer)</strong>: Farklı sunucular arasında gerçekleşen iletişimi sağlar. (HTTP,FTP,TELNET vb.)<br><br>
<strong>Taşıma Katmanı (Transport Layer)</strong>:Verinin nasıl gönderileceği belirlenir.TCP ve UDP protokolleri bu katmanda gerçekleşir.<br><br>
<strong>Ağ Katmanı (Network Layer)</strong>:IP katmanı olarak geçer. Uç sistem ile ağ arasındaki lojik arabirime ilişkin katmandır.<br><br>
<strong>Fiziksel Katman (Physical Layer)</strong>:İletişim ortamının özelliklerini,haberleşme hızını  ve kodlama şemasını belirler.<br><br>


<center><h1>Pasif Bilgi Toplama</h1></center><br>



<strong>Google İle Bilgi Toplama</strong><br>

Google üzerinden yaptığımız aramalarda bizlere girdiğimiz kelimelere göre karşımıza sonuçlar çıkarmaktadır. Bunun yanında Google bizlere Dork diye tabir edilen spesifik arama yapabildiğimiz operatörler sunmuştur. Bu operatörleri kullanarak hedef site hakkında birçok bilgiye erişmek mümkündür. Aşağıda bu operatörler ve ne işe yaradıkları hakkında bilgiler veilmiştir.<br><br>


<strong>site:</strong> Bu operatör site: kısmına yazdığımız hedef site hakkında çıkan sonuçları bize sıralar. <br><br>
<img src="/resimler/bilgi toplama/webs/site.JPG" alt="site"><br><br>


<strong>intitle:</strong>Bu operatör girdiğimiz kelimeleri sayfaların başlığında bularak bize listeler.<br><br>
<img src="/resimler/bilgi toplama/webs/intitle.JPG" alt="intitle"><br><br>

<strong>filetype:</strong> Bu operatör arayacağımız dosya tipine göre bize sonuç sunmaya yarar.<br><br>
<img src="/resimler/bilgi toplama/webs/filetype.JPG" alt="filetype"><br><br>


<strong>inurl:</strong>Bu operatör girilen kelimenin url içerisinde olduğu sayfaları listeler.<br><br>
<img src="/resimler/bilgi toplama/webs/inurl.JPG" alt="inurl"><br><br>


<strong>related:</strong>Bu operatör girilen web sayfasının benzerlerini listeler.<br><br>
<img src="/resimler/bilgi toplama/webs/related.JPG" alt="related"><br><br>

<strong>info:</strong>Bı operatör girilen web sayfası hakkında genel bilgileri içeren siteleri listeler.<br><br>
<img src="/resimler/bilgi toplama/webs/info.JPG" alt="info"><br><br>

<strong>intext:</strong>Bu operatör girilen kelimeyi site sayfaları içerisinde aramaya yarar.<br><br>
<img src="/resimler/bilgi toplama/webs/intext.JPG" alt="intext"><br><br>

Ayrıca işinize yarayabilecek birkaç operatör de aşağıda listelenmiştir.
<ul type="circle">	
<li><strong>map:</strong>Aranılan lokasyona ait konum bilgilerini gösterir.</li>
<li><strong>cache:</strong>Kapanmış olan sitelerin son halini görebilirsiniz.Ayrıca Google üzerinde en son belleğin ne zaman güncellendiğini görebilirsiniz.</li>
<li><strong>link:</strong>Girdiğiniz site linki üzerindeki sayfaların tümünü listeler.</li>
<li><strong>book:</strong>Google kütüphane içinde bulunan kitapları arayabilirsiniz.</li>
<li><strong>author:</strong>Bir kullanıcının,yazarın metinlerini listeler. </li>
<li><strong>groups:</strong>Belirlediğiniz bir grup ile ilgili sonuçları size listeler.</li>
<li><strong>daterange:</strong>Belirlenen tarih aralığındaki sayfaları listeler.</li>
<li><strong>allintext:</strong>Yazılan birden fazla kelimelerin hepsinin içerikte var olduğu sayfaları listeler.</li>
<li><strong>ext:</strong>Filetype ile hemen hemen aynıdır.Girilen dosya türüne göre sonuçları listeler.</li>
<li><strong>allintitle:</strong>Yazılan birden fazla kelimelerin hepsinin başlıkta var olduğu sayfaları listeler.</li>
</ul><br>

Bu operatörler ile kendiniz site açıklarını bulan dorklar oluşturabilirsiniz. Bunların yanında hazır olarak kullanıcılar tarafından yayınlanan dorkların listesi <a href="https://www.exploit-db.com/google-hacking-database">BU SİTEDE </a>mevcuttur.<br><br>



<strong>Bing İle Bilgi Toplama</strong><br><br>
Pasif bilgi toplama sürecinde Google yanında Bing ile de hedef site hakkında bilgi edinmek mümkündür.Parametreleri Google ile hemen hemen aynı olsa da ufak farklar mevcuttur. Parametreler aşağıda listelenmiştir.<br><br>
<img src="/resimler/bilgi toplama/webs/bing.JPG" alt="bing"><br><br>
<ul type="disc">
<li><strong>site:</strong> Google ile aynıdır.Site: kısmına yazdığımız hedef site hakkında çıkan sonuçları bize sıralar.</li> 
 <li><strong>ext:</strong>Belirlenen dosya uzantısını içeriğinde barındıran siteleri listeler.</li>
 <li><strong>filetype:</strong> Google ile aynıdır. Dosya türüne göre sayfalar listeler.</li>
<li><strong>url:</strong>Girilen kelimenin url içerisinde olduğu sayfaları listeler.</li>
<li><strong>intitle:</strong>Google ile aynıdır. Sayfa başlıklarında arama yapmak için kullanılır.</li>
<li><strong>hasfeed:</strong>Belirli bir web sitesi içerisinde RSS veya Atom Feed ile yayınlanmış sayfaları listeler. </li>
<li><strong>feed:</strong>Aranılan kelimeye göre RSS ve Atom Feed içeren sayfaları bulur.</li>
<li><strong>loc:</strong>Aranılan lokasyon içerisinde bulunan web sayfalarını gösterir.</li>
<li><strong>language:</strong>Sadece belirlenen dildeki sayfaları taramaya yarar..</li>
<li><strong>ip:</strong>Belirlenen IP adresinin sayfalarını listeler.</li> 

</ul><br>


<strong>Whois Analizi </strong><br><br> Whois sorgusu, hedef site hakkında bize birçok bilgi sunar. Site sahibinin iletişim bilgileri,adres bilgileri, işletme bilgileri,e-posta bilgileri vb. birçok şeyi whois sorgusu ile öğrenebiliriz. İnternet üzerinden whois analizi yapabilecek bir çok web site mevcuttur.Bunun yanında Linux ile terminal üzerinden kolaylıkla whois sorgusu yapılabilir. İlk örneğimizi Linux üzerinden gösterelim.<br><br>


Öncelikle Terminalimizi açıyoruz ve<strong> whois “site adı” </strong> yazıp enter tuşuna basıyoruz. <br><br>

<img src="/resimler/bilgi toplama/whois/whois1.JPG" alt="whois"><br><br>

<img src="/resimler/bilgi toplama/whois/whois2.JPG" alt="whois2"><br><br>
Gördüğünüz gibi site sahibinin birçok bilgisi karşımıza çıktı.Bunu birde whois.net sitesi üzerinden yaparak gösterelim.<br><br>

Öncelikle whois.net adlı sitemize giriyoruz.Siteye <a href="https://whois.net">BURAYA TIKLAYARAK</a>ulaşabilirsiniz.Daha sonra karşımıza çıkan arama motoruna hedef domain adresini yazıyoruz.Enter tuşuna basıp bekliyoruz. <br><br>

<img src="/resimler/bilgi toplama/whois/whois3.JPG" alt="whois3"><br><br>

<img src="/resimler/bilgi toplama/whois/whois4.JPG" alt="whois3"><br><br>

<strong>Reverse Whois</strong><br><br>
Reverse Whois site sahibinin e-mail adresi üstünden ya da direk site adı girilerek, kayıtlı olan diğer domain adreslerini bulmaya yarar. İnternet üzerinde birçok Reverse Whois sorgusu yapan siteler mevcuttur.Biz bunlardan reversewhois.io adlı siteyi örnek göstereceğiz.<br><br>

İlk olarak sitemize giriyoruz.Siteye <a href="https://reversewhois.io" target="_blank">BURAYA TIKLAYARAK</a> ulaşabilirsiniz. Daha sonra arama çubuğuna e-posta adresi ya da site adresini yazıyoruz ve enter tuşuna basıyoruz.<br><br>

<img src="/resimler/bilgi toplama/whois/rwhois1.JPG" alt="rwhois1"><br><br>

Karşımıza bu site sahibinin üzerine kayıtlı olan diğer site domainlerini listeliyor.<br><br>

<img src="/resimler/bilgi toplama/whois/rwhois1.JPG" alt="rwhois1"><br><br>

<strong>IP Aralığı Tespit Etme</strong><br><br>
İnternet siteleri üzerinden hedef sistemin IP aralıklarını bulabileceğimiz bir çok site mevcuttur. Bunlardan bir kaçını makalemizde örnek olarak göstereceğiz.<b><br>

<strong>Arin.net</strong><br><br>

İlk göstereceğimiz sitenin adı Arin.Net. Siteye <a href="https://www.arin.net" target="_blank">BURAYA TIKLAYARAK</a> ulaşabilirsiniz.<br><br>

İlk olarak sitemize giriş yaptıktan sonra pencerenin sağ üst kısmında bulunan arama kutucuğuna hedef sitenin IP adresini yazıyoruz.Enter tuşuna basıp bekliyoruz. <br><br>

<img src="/resimler/bilgi toplama/aralık/arin1.JPG" alt="arin"><br><br>


Network kısmında bize sitenin hangi IP aralığında olduğunu gösteriyor.<br><br>
<img src="/resimler/bilgi toplama/aralık/arin2.JPG" alt="arin"><br><br>

<h4><strong>Ripe.Net</strong></h4><br>

İkinci sorgulama yapacağımız sitemiz ise Ripe.Net. Siteye <a href="https://www.ripe.net/" target="_blank">BURAYA TIKLAYARAK</a>ulaşabilirsiniz.<br><br>

Sitemize girdiğimizde karşımıza gelen pencerede, sağ üst köşede bulunan arama kutucuğuna hedef IP adresimizi giriyoruz ve enter tuşuna basıp bekliyoruz.<br><br>

<img src="/resimler/bilgi toplama/aralık/ripe1.JPG" alt="ripe"><br><br>


Inetnum kısmında sitenin hangi IP aralığında olduğunu biz gösteriyor.<br><br>

<img src="/resimler/bilgi toplama/aralık/ripe2.JPG" alt="ripe"><br><br>

<strong>Apnic.net</strong><br><br>

Üçüncü sorgulama yapacağımız site ise Apnic.Net.Siteye <a href="https://www.apnic.net/" target="_blank">BURAYA TIKLAYARAK</a> ulaşabilirsiniz.<br><br>

Siteye girdiğimizde sağ üst kısımdaki arama kutucuğuna hedef IP adresini yazıp enter tuşuna basıp bekliyoruz.<br><br>


<img src="/resimler/bilgi toplama/aralık/apnic1.JPG" alt="apnic1"><br><br>
Inetnum kısmında bize IP aralığını gösteriyor.<br><br>
<img src="/resimler/bilgi toplama/aralık/apnic2.JPG" alt="apnic2"><br><br>
<center><h1>Archive.Org Nedir?</h1></center><br>
1996 yılında kurulmuş olan bu site kullanıcılara internet üzerinde kaydettiği dökümanları sunmaktadır.Bu dökümanlar içerisinde resim,video,müzik,kitap,yazılım gibi bir çok seçenek sunmaktadır.Bizim ilgili olduğumuz alan ise bu sitenin aynı zamanda web sitelerinin belirli aralıklarla görüntüsünü kaydetmesidir. Bu yol bize kapanmış bir sitenin, kapanmadan önceki görüntülerine erişme imkânı sağlamaktadır.<br><br>

İlk olarak sitemize giriyoruz.<a href="https://archive.org" target="_blank">Buraya Tıklayarak</a> ulaşabilirsiniz.Sol üst köşeden sarı renkle gösterilmiş olan WEB kısmına tıklıyoruz. Karşımıza WaybackMachine adında bir tarama kutucuğu çıkıyor. <br><br>

<img src="/resimler/bilgi toplama/archive/archive1.JPG" alt="archive1"><br><br>
Bu arama kutucuğuna hedef sitemizin adresini giriyoruz ve enter tuşuna basıyoruz.<br><br>
<img src="/resimler/bilgi toplama/archive/archive2.JPG" alt="archive2"><br><br>
Karşımıza yılların sıralandığı çubuk şeklinde bir tarih sırası ve altında ise  ay ve günlerin olduğu bir tarih paneli çıkıyor. Yılların belirtildiği çubuğun olduğu kısımda ise hangi yıllar ne kadar görüntü almışsa onu ifade eden bir histogram grafiği mevcut. Altında ise ayların içinde mavi ile işaretlenmiş günler mevcut. Bu mavi işaretle gösterilmiş olan günler bize o gün görüntü kaydının alındığını ifade etmektedir.Biz 2005 yılını seçtik ve 23 Şubat tarihli görüntü kaydına tıkladık.<br><br>
<img src="/resimler/bilgi toplama/archive/archive3.JPG" alt="archive3"><br><br>
Gördüğünüz gibi seçtiğimiz tarihdeki sitenin görüntüsünü bizlere sundu.<br><br>
<strong>YouGetSignal İle Bilgi Toplama</strong><br><br>
	
Pasif bilgi toplama sürecinde bize yardımcı olan sitelerden bir diğeri de YouGetSignal adlı web sitesidir.Siteye <a href="https://www.yougetsignal.com" target="_blank"> BURAYA TIKLAYARAK</a> ulaşabilirsiniz.
<br>
İlk olarak sitemize giriş yapıyoruz. Karşımıza tools kısımlı bir pencere çıkıyor. Burada site içerisinde yapabileceğimiz taramalar mevcuttur. Her birinin açıklaması aşağıda verilmiştir.
<img src="/resimler/bilgi toplama/webs/yougetsignal.JPG" alt="yougetsignal"><br><br>

<ul type="disc">
<li><strong>Port Forwarding Tester</strong>:Hedef sitenin belirtilen portunun açık olup olmadığını bulur.</li> 
<li><strong>What Is My Ip Adress?</strong>:Bağlantı sağladığınız bilgisayarın IP adresini gösterir.</li>
<li><strong>Network Location Tool</strong>:Hedef adresin hangi konumda olduğunu harita üzerinde gösterir. </li>
<li><strong>Phone Number Geolocator</strong>:Sadece ABD hatlarını destekleyen numara sorgulama aracı.</li>
<li><strong>Reverse E-Mail Lookup Tool</strong>:Girilen e-mail adresinin kime ait olduğunu sosyal medya üzerinde arama yaparak bulmaya yarar.</li>
<li><strong>Reverse IP Domain Check</strong>:Ters IP sorgulaması yapmaya yarar.</li>
<li><strong>Whois Lookup Tool</strong>:Whois sorgulaması yapmaya yarar.</li>
</ul>

<strong>Netcraft İle Bilgi Toplama</strong><br><br>

Sıkça kullanılan sitelerden bir diğeri de Netcraft. Benim de oldukça hoşuma giden bu web sitesi sayesinde hedef sistemin DNS bilgileri,İşletim Sistemleri ve IP bilgileri gibi daha bir çok bilgiye erişmek mümkün. Biz Netcraft sitesinin Site Report kısmını kullanıyoruz.<a href=https://sitereport.netcraft.com/>BURAYA TIKLAYARAK</a> siteye ulaşabilirsiniz.
Sitemize girdikten sonra karşımıza çıkan arama bölümüne hedef site adını yazıyoruz. <br><br>
<img src="/resimler/bilgi toplama/webs/netcraft.JPG" alt="netcraft"><br><br>

<img src="/resimler/bilgi toplama/webs/netcraft2.JPG" alt="netcraft2"><br><br>
<img src="/resimler/bilgi toplama/webs/netcraft3.JPG" alt="netcraft3"><br><br>

<strong>Shodan İle Bilgi Toplama</strong><br>
Shodan diğer arama motorlarından farklı olarak web sitelerinden ziyade bizlere internete açık olan sunucular hakkında bilgi vermektedirOyun Sunucuları,Veritabanları,Kameralar ve giriş panelleri açık olan bir çok sunucuyu bizlere göstermektedir. Shodan kullanımı aşağıda gösterilmiştir.<br>
Siteye <a href="https://shodan.io">BURAYA TIKLAYARAK</a>ulaşabilirsiniz.
Öncelikle sitemize giriyoruz.

<img src="/resimler/bilgi toplama/webs/shodan.JPG" alt="shodan"><br><br>


Spesifik olarak arama gerçekleştirmeden önce site içerisinde bulunan hazır araçları göstermek istiyorum. Bunun için arama kutucuğunun altında bulunan Explore kısmına tıklıyoruz.


<img src="/resimler/bilgi toplama/webs/shodanexplore.jpg" alt="shodan"><br><br>
Daha sonra karşımıza gelen ekranda farklı araçların olduğunu görüyorsunuz. Databases,Video Games, Industrial Control Systems,Webcam, Netcam, Cams gibi.

<img src="/resimler/bilgi toplama/webs/shodanexplore1.JPG" alt="shodan"><br><br>


Biz örnek olarak bir sunucularına erişim olan Webcam taraması yapacağız. Webcam kısmına tıklıyoruz.<br><br>
<img src="/resimler/bilgi toplama/webs/shodanexplore2.JPG" alt="shodan"><br><br>

Karşımıza sunucusu açık olan Webcam listesini çıkardı. İlk sıradakine tıklıyoruz ve daha detaylı bilgi ediniyoruz.


<img src="/resimler/bilgi toplama/webs/shodanweb2.JPG" alt="shodan"><br><br>

Gördüğünüz gibi karşımıza o sunucunun portları,servis bilgileri ile ilgili bilgileri çıkardı.  Ayrıca tarayıcıya hedefin IP adresini yazarak yönetim paneline ulaşmak da mümkün.<br><br>


Şimdi bizim ilgilendiğimiz bir başka kısma geçelim. Hedef site üzerinden tarama gerçekleştirelim. Sitenin arama kutucuğuna hedef site adımızı giriyoruz.
 
<img src="/resimler/bilgi toplama/webs/shodansite.JPG" alt="shodan"><br><br>

Taramamızı enter tuşuna basıp gerçekleştiriyoruz.<br><br>


<img src="/resimler/bilgi toplama/webs/shodansite2.JPG" alt="shodan"><br><br>


Çıkan sonuçlarda hedef sitenin sahip olduğu açık sunucular hakkında listeleme yaptı. Biz 2. Kısımdaki sunucuya tıklıyoruz.<br><br>

<img src="/resimler/bilgi toplama/webs/shodansite3.JPG" alt="shodan"><br><br>

Sunucu hakkındaki port,servis ve en önemlisi Vulnerabilities yani sunucu açıklarını bizlere listelemiş oldu.<br><br>


Shodan ile tıpkı Google,Bing vb. arama motorlarında olduğu gibi spesifik olarak tarama yapmak da mümkündür. Bu parametreleri kendi seçiminize göre belirleyip daha detaylı aramalar gerçekleştirebilirsiniz.Şimdi bu parametrelerin bir kısmını açıklamalarıyla birlikte veriyoruz.

<ul type="disc">
<li><strong> country</strong>: Belirli bir ülke içindeki sunucuları aramak için kullanılır. </li>
<li><strong>hostname </strong>:Sonuçları belirlediğiniz alan adına göre filtreler.</li>
<li><strong>net </strong>: Sonuçları belirlediğiniz IP adresine göre filtreler.</li>
<li><strong>os </strong>: Belirlediğiniz işletim sistemini içeren sonuçları filtreler.</li>
<li><strong> port</strong>: Belirlediğiniz port sayısının içerdiği sunucuları filtreler.</li>
<li><strong> city</strong>: Belirlediğiniz şehre göre sonuçları listeler.</li>
</ul><br>

<strong>BinaryEdge Üzerinden Bilgi Toplama</strong><br><br>
Diğer sitelerdan farklı olarak üyelik oluşturmamız gereken bir sitedir. Üyelik oluşturmak için <a href="https://app.binaryedge.io/sign-up">BURAYA TIKLAYIN</a>. Üyeliğimizi oluşturup aktif ettikten sonra karşımıza arama paneli çıkacaktır.


<img src="/resimler/bilgi toplama/webs/binary.JPG" alt="binary"><br><br>

Filter By kısmından aramamızı özelleştirebilirz. Ayrıca arama motorunda kullanılabilecek parametrelerin listesi de sayfanın devamında mevcuttur.<br><br>
<img src="/resimler/bilgi toplama/webs/binary1.JPG" alt="binary"><br><br>
Biz öncelikle tarama yapmak istediğimiz hedef site adresini arama kutucuğuna giriyoruz ve arıyoruz.<br><br>
<img src="/resimler/bilgi toplama/webs/binary2.JPG" alt="binary"><br><br>
Hedef sitemizi yazıp search butonuna bastık. Karşımıza 20 adet sunucu bilgileri çıkardı. Bu sunuculardaki portları, servis türleri,konumu gibi bilgilere erişmek mümkün.<br><br>
<img src="/resimler/bilgi toplama/webs/binary3.JPG" alt="binary"><br><br>
<img src="/resimler/bilgi toplama/webs/binary4.JPG" alt="binary"><br><br>
Ayrıca BinaryEdge üzerinden subdomain taraması da yapılabilmektedir. Sitenin Domain kısmına gelip hedef site adresimizi yazdığımızda bize hedef sitenin alt domainlerini listeler.<br><br>
<img src="/resimler/bilgi toplama/webs/binary5.JPG" alt="binary"><br><br>
<img src="/resimler/bilgi toplama/webs/binary6.JPG" alt="binary"><br><br>



<strong>TheHarvester İle Domain Üzerinde E-Mail Keşfi</strong><br><br>

Pasif Bilgi Toplama sürecinde kullanılan araçlardan biri de TheHarvester scriptidir. Kali Linux işletim sistemi üzerinde öntanımlı olarak gelen bu aracın komutları aşağıda gösterilmiştir.<br><br>

<img src="/resimler/bilgi toplama/subdomain/harves1.JPG" alt="harves"><br><br>

<ul type="disc">
<li><strong>-d</strong>:Hedef site adresinin belirtilmesinde kullanılır.</li>
<li><strong>-b</strong>:Belirtilen arama motoru üzerinden taramaları gerçekleştirir.Google,Yahoo vb.All yazarak tamamında arama gerçekleştirebilirsiniz.</li>
<li><strong>-g</strong>:Google dork kullanarak aramaları gerçekleştirir.</li>
<li><strong>-s</strong>:Taramaya belirtilen sayıdan başlar.</li>
<li><strong>-v</strong>:DNS ile Hostname doğrulama yapar ve sanal makineleri arar.</li>
<li><strong>-f</strong>:Sonuçları XML ya da HTML olarak kayıt eder.</li>
<li><strong>-n</strong>:Bulunan aralıklarda ters DNS sorgusu yapar.</li>
<li><strong>-c</strong>:Brute force ile subdomainleri bulur.</li>
<li><strong>-t</strong>:DNS TLD sorgusu yapar.</li>
<li><strong>-e</strong>:Belirlenen DNS sunucusunu kullanarak tarama yapar.</li>
<li><strong>-p</strong>:Belirlenen host üzerinde port taraması yapar.</li>
<li><strong>-l</strong>:Tarama sınırı belirler.</li>
<li><strong>-h</strong>:Bulunan sonuçları SHODAN veri tabanında sorgular.</li>
</ul><br><br>


Öncelikle hedef sitemizi -d parametresi ile belirtiyoruz. Daha sonra aranacak olan tarama motorunu -b ile google yapıyoruz. En son olarak 300 sayfa tarama yapmasını istiyoruz.<br><br>
<img src="/resimler/bilgi toplama/subdomain/harves2.JPG" alt="harves"><br><br>
<img src="/resimler/bilgi toplama/subdomain/harves3.JPG" alt="harves"><br><br>

Gördüğünüz gibi karşımıza, alan adlarına kayıtlı olan e-mail adreslerini listeliyor. <br><br>

<strong>Subdomain Tespiti Nedir Nasıl yapılır?</strong><br><br>
Subdomain sitelerin alt alan adları anlamına gelmektedir. Ana domaine bağlı olan subdomainler hosting satın alınan site tarafından sınırlı ya da sınırsız sayıda size sunulan alt alan adlarıdır. Subdomain taramaları scriptler üzerinden ya da web siteleri üzerinden yapılabilir.Makalenin devamında nasıl yapıldığına dair bilgiler mevcuttur.

<strong>Aquatone İle Subdomain Taraması</strong><br><br>
Aquatone ;Aquatone-discover, Aquatone-scan, Aquatone-gather olmak üzere içinde üç farklı araç barındıran bir scripttir. Her bir araç için farklı bir yükleme yapmaya gerek yoktur.Aquatone kurduğumuzda bu üç araç da birlikte geliyor.
Öncelikle terminalimizi açıyoruz. Daha sonra “ sudo gem install aquatone “ yazıp uygulamamızı indiriyoruz. <br><br>
<hr>Yükleme<hr>
 <img src="/resimler/bilgi toplama/subdomain/aquatone.JPG" alt="aquatone"><br><br>
 
 <strong>Aquatone-Discover</strong><br><br>
Aquatone kullanımında ilk olarak discover ile subdomain adreslerini bulmanız zorunludur. Daha sonra scan ve gather araçlarını kullanabilirsiniz.
Aquatone-discover komutları aşağıda gösterilmiştir.<br><br>
<hr>Komutlar<hr>

  <img src="/resimler/bilgi toplama/subdomain/aquatone-discover1.JPG" alt="aquatone"><br><br>

<ul type="disc">
<li><strong>-(-d) –domain</strong>: Hedef siteyi belirtmek için kullanılır.</li>
<li><strong>--nameservers</strong>: Taramada özel olarak kullanmak istediğimiz NS(Name Server) belirler.</li>
<li><strong--fallback-nameservers</strong>:Yedek DNS sunucusu belirlemek için kullanılır.</li>
<li><strong>--ignore-private</strong>:Özel IP adreslerine çözümlenmiş sunucuları yok sayar.</li>
<li><strong>--set-key</strong>:Aquatone içinde bulunan Shodan,VirusTotal gibi araçları kullanabilmek için API key denilen ürün anahtarı girmek için kullanılır.</li>
<li><strong>--list-collector</strong>: Kullanılan kollektörleri listeler.</li>
<li><strong>--only-collector</strong>:Sadece belirtilen kollektörü çalıştırır.</li>
<li><strong>--disable-collector</strong>:Belirlenen kollektörleri çalıştırmaz.</li>
<li><strong>--threads</strong>:Varsayılan tarama gücünü değiştirmek için kullanılır.Default olarak 5 ile başlar.Yalnız bu sayıyı artırmak, DNS sorgulamaları yaparken daha fazla baskı uygulayacağından; karşı sistem bunu bir saldırı tespiti olarak algılayabilir.</li>
<li><strong>--sleep</strong>:Hedef sistemde şüphe uyandırmamak için belirli aralıkta saniyeler belirlemeye yarar.Yani yapılan sorgulamaların arasına süre koymaya yarar.</li>
<li><strong>--jitter</strong>:Sürekli aynı aralıklarla DNS sorgulaması da dikkat çekebilir.Bu komut ile –sleep değerini belli bir yüzdeliğe bölerek farklı zaman aralıklarında arama yapmasını sağlar.</li> 
<li>--shodan-pages </strong>:İşlenecek Shodan API sayfa sayısını belirtmeye yarar.</li>
<li></strong>--wordlist</strong>: Brute Force uygulamak istediğiniz alan adına wordlist belirlemeye yarar.</li>
<li></strong>--netcraft</strong>:İşlenicek Netcraft sayfa sayısını belirlemeye yarar.</li>
<li></strong>--censys-page</strong>:İşlenecek Censys API sayfa sayısını belirtmeye yarar.</li>
<li></strong>--publicwww-pages</strong>:İşlenicek PublicWWW  sayfa sayısını belirtmeye yarar.</li>
<li></strong>wayback-machine-timeout</strong>:Wayback Machine için saniye cinsinden zaman aşımını belirtmeye yarar.</li>
<li></strong>--gtr-pages</strong>:İşlenecek Google Şeffaflık Raporu sayfa sayısını belirtmeye yarar.</li>
<li><strong>--help</strong>:Kullanılabilecek parametreleri listeler.</li>
</ul><br><br>

İlk olarak alt domain keşfi yapmak için aquatone-discover kullanıyoruz. –d parametresi ile hedef siteyi belirtiyoruz ve taramayı gerçekleştiriyoruz.<br>
<hr>Örnek Tarama<hr>
  <img src="/resimler/bilgi toplama/subdomain/aquatone-discover2.JPG" alt="aquatone"><br><br>
    <img src="/resimler/bilgi toplama/subdomain/aquatone-discover3.JPG" alt="aquatone"><br><br>
  Gördüğünüz gibi sitenin subdomain adreslerini bize listeledi. Bunları /root/aquatone/unime.it adlı dosyanın içine txt ve json dosyası olarak kayıt etti.Artık Aquatone-scan ile port taraması yapabiliriz. <br><br>
  
  <strong>Aquatone-Scan</strong><br><br>

Aquatone-discover ile subdomainleri keşfettikten sonra scan taraması ile portları tarayabilirsiniz.

Aquatone-scan komutları aşağıda gösterilmiştir.<br><br>
<img src="/resimler/bilgi toplama/subdomain/aquatone-scan.JPG" alt="aquatone"><br><br>
<ul type="disc">
<li><strong>(-d) --domain</strong>: Hedef siteyi belirtmek için kullanılır.</li>
<li><strong>(-p) --ports</strong>: Belirlediğiniz portları taramak için kullanılır.</li>
<li><strong>--timeout</strong>:Portları tararken zaman aşımını belirmek için kullanılır.</li>
<li><strong>(t) --threads</strong>: Discover da olduğu gibi; Varsayılan tarama gücünü değiştirmek için kullanılır.</li>
<li><strong>(s) --sleep</strong>: Taramayı belirli saniyeler arasında gerçekleştirir.</li>
<li><strong>(-j) –jitter</strong>: .Sleep değerini belli bir yüzdeliğe bölerek farklı zaman aralıklarında arama yapmasını sağlar.</li>
<li>(-h) --help</strong>:Kullanılabilir komut listesini açar.</li>
</ul><br><br>

<strong>Aquatone-Gather</strong><br><br>

Port taraması yaptıktan sonra en son aşamaya geçilir. Gather ile web sitelerinin görselleri,HTTP  üst bilgilerini almak mümkündür. Aşağıda komutlar hakkında bilgi verilmiştir.<br><br>

<img src="/resimler/bilgi toplama/subdomain/aquatone-gather.JPG" alt="aquatone"><br><br>

<ul type="disc">
<li><strong>(-d) --domain</strong>: Hedef siteyi belirtmek için kullanılır.</li>
<li><strong>--timeout</strong>:İşlemleri yaparken zaman aşımını belirmek için kullanılır.</li>
<li><strong>(t) --threads</strong>: Discover da olduğu gibi; Varsayılan tarama gücünü değiştirmek için kullanılır.</li>
<li><strong>(s) --sleep</strong>: Taramayı belirli saniyeler arasında gerçekleştirir.</li>
<li><strong>(-j) –jitter</strong>: .Sleep değerini belli bir yüzdeliğe bölerek farklı zaman aralıklarında arama yapmasını sağlar.</li>
<li>(-h) --help</strong>:Kullanılabilir komut listesini açar.</li>
</ul><br>

<strong>Dnsmap İle Subdomain Taraması</strong><br><br>

DNS üzerinden subdomain tespiti yapan bir başka aracımız da dnsmap. Kullanımı basit ve sade bir araçtır. Parametreleri ve açıklamaları aşağıda verilmiştir.<br><br>

<img src="/resimler/bilgi toplama/subdomain/dnsmap.JPG" alt="dnsmap"><br><br>

<ul type="disc">
	<li><strong>-w</strong>:Seçtiğiniz wordlist üzerinden tarama yapar.</li>
	<li><strong>-r</strong>:Sonuçları txt biçiminde kayıt etmeye yarar.</li>	
	<li><strong>-w</strong>:Sonuçlar csv biçiminde kayıt eder.</li>
	<li><strong>-d</strong>:Sorgulamalar arası milisaniye değerinde gecikme ayarlamaya yarar.</li>
	<li><strong>-i</strong>:Belirlediğiniz bir IP adresini taramadan çıkartır.</li>
	</ul>
	
Terminalimizi açıyoruz ve dnsmap "hedef site ip" yazıyoruz. Enter tuşuna basıp taratıyoruz.<br><br>
<img src="/resimler/bilgi toplama/subdomain/dnsmap2.JPG" alt="dnsmap"><br><br>
<img src="/resimler/bilgi toplama/subdomain/dnsmap2.JPG" alt="dnsmap"><br><br>	
	
Gördüğünüz gibi hedef sitenin bulunan alt alan adlarını bizlere gösterdi.
	
<strong>Sublist3r İle Subdomain Taraması</strong><br><br>

Subdomain taramasında sıkça kullanılan araçlardan birisi de sublist3r scriptidir. Kullanımı ve komutları aşağıda belirtilmiştir.<br><br>


<img src="/resimler/bilgi toplama/subdomain/sublister.JPG" alt="sublister"><br><br>
<ul type="disc">
<li><strong>-h</strong>:Kullanılabilir komut listesini açar.</li>
<li><strong>-d</strong>: Hedef site adresini belirtmek için kullanılır.</li>
<li><strong>-b</strong>:BruteForce yöntemi ile tarama gerçekleştirir.</li>
<li><strong>-p</strong>:Bulunan subdomainlerin, taranacak portlarını belirtmeye yarar.</li>
<li><strong>-v</strong>:Ayrıntılı bir biçimde tarama modunu açmak için kullanılır.</li>
<li><strong>-t</strong>:Programın BruteForce yaparken kullanacağı güç çekirdeği sayısını belirtmek için kullanılır.</li>
<li><strong>-e</strong>: Spesifik bir tarama motoru üzerinden tarama yapmak için kullanılır.</li>
<li><strong>-o</strong>:Sonuçların kayıt edileceği text dosyasını belirlemek için kullanılır.</li>
</ul> <br><br>

Terminal üzerinden sublist3r -d  “hedef site” -v (detaylı tarama) -p 80 ( açık 80 portlarını bul) olarak örneğimizi yapıyoruz.

<img src="/resimler/bilgi toplama/subdomain/sublister1.JPG" alt="sublister"><br><br>
<img src="/resimler/bilgi toplama/subdomain/sublister2.JPG" alt="sublister"><br><br>

İlk olarak bize subdomain tespitini yaptı. Daha sonra ise bu subdomain adreslerindeki açık 80 portlarını listeledi.<br><br>

<center><h1>Sızma Testlerinde Aktif Bilgi Toplama</h1></center>

<strong>Ping Nedir Nasıl Atılır?</strong><br><br>
Ping hedef sunucunun aktif olup olmadığını kontrol etmek ve alan adının girilerek IP adresini öğrenmeye yarayan bir komuttur. Windows üzerinden CMD(Komut Sistemi) ile ya da Linux üzerinden terminal ile ping “hedef site adresi” yazılarak ping atılabilir. Biz örneğimizi Linux terminali üzerinden göstereceğiz.<br><br>

Terminalimizi açıyoruz. Ping “hedef site adresi” yazıp enter yapıyoruz. Karşımıza parantez içinde numerik rakamlar çıkıyor. Bu rakamlar girdiğimiz alan adına karşılık gelen IP adresi oluyor.<br><br>
<img src="/resimler/bilgi toplama/aktif/ping.JPG" alt="ping"><br><br>



<strong>Dirb Kullanımı</strong><br><br>
Dirb sitenin arka planında bulunan ve kullanıcıya görünmeyen kısımları, belirlenen kelime gruplarına göre tarama yapan bir araçtır.Default olarak kendi wordlistinin içinde 4612 kelime vardır. İsterseniz kendinizin oluşturduğunuz bir wordlist ile de web içeriklerini ve linklerini taratabilirsiniz.Kali Linux üzerinde kurulu olarak gelen aracın kullanımı aşağıda gösterilmiştir.<br><br>

Öncelikle panelimizi açıyoruz. Daha sonra dirb “http://hedefsite ip/domain “ yazıp enter yapıp bekliyoruz.<br><br>


<img src="/resimler/bilgi toplama/aktif/dirb1.JPG" alt="dirb"><br><br>
<img src="/resimler/bilgi toplama/aktif/dirb2.JPG" alt="dirb"><br><br>
<img src="/resimler/bilgi toplama/aktif/dirb3.JPG" alt="dirb"><br><br>


+ http kısmında wordlist içerisindeki kelimelere göre bulduğu bağlantı linklerini bize sıralıyor. Tek tek tıklayarak hangi bağlantılar olduğunu kontrol edebilirsiniz.<br><br>


<strong>Dirbuster Kullanımı</strong><br><br>

Web sitelerinin kullanıcı tarafından erişilmesine gizlenen(Admin Panelleri vb.) sayfalarını bulmanın bir diğer yolu da Dirbuster kullanmaktır. Kali Linux içerisinde ön tanımlı olarak gelir. Terminal üzerinde dirbuster yazarak ya da uygulamalar kısmından Dirbuster yazarak araca ulaşabilirsiniz. Görsel arayüzü olan bir araçtır. Kullanımı aşağıda gösterilmiştir.<br><br>


<img src="/resimler/bilgi toplama/aktif/dirbuster.JPG" alt="dirbuster"><br><br>
Aracımızı açtığımızda böyle bir arayüz ile karşımıza çıkıyor. Target kısmını tarayacağımız sayfa için ben doldurdum. Açıklamalarını aşağıya bırakıyorum.<br><br>
<img src="/resimler/bilgi toplama/aktif/dirbuster1.JPG" alt="dirbuster"><br><br>
Bu kısma hedef sitemizin adresini yazıyoruz. Dilersek sadece IP olarak da yazabiliriz. Sadece IP adresinin başına “http://” veya “https://” eklemeniz yeterli olacaktır.<br><br>

<img src="/resimler/bilgi toplama/aktif/dirbuster2.JPG" alt="dirbuster"><br><br>

Work Metgod kısmında ilk seçenek sadece GET ile olan istekleri listeliyor. Biz Auto Switch ile HEAD and GET ile olan istekleri listelemesini seçiyoruz.<br>
Number Of  Threads kısmında programın çalışma yükünü ayarlıyoruz. Sisteminiz ne kadar iyiyse tarama gücünü de o kadar yükseltebilirsiniz. Daha hızlı sonuç alırsınız.<br><br>

<img src="/resimler/bilgi toplama/aktif/dirbuster3.JPG" alt="dirbuster"><br><br>
Select Scanning Type kısmında eğer kendimiz bir Wordlist ile tarama yapmak istiyorsak List based brute force diyoruz. Browse kısmından wordlistimizi seçip tamam diyoruz. Ama biz şuan Pure Brute Force yani aracın kendi içerisinde olan wordlist ile arama yapıyoruz.<br><br>
Char Set kısmında aracın kendi bruteforce yönteminini uygularken kullanılacak karakter setini seçiyoruz. Örnek olarak A’dan Z’ye 0 - 9 arası gibi. Büyük küçük harf ayarlaması da yapılabilir. .<br><br>
Min ve Max Length kısmında ise bu kelimelerin minimum ve maksimum uzunluğunu belirliyorsunuz. .<br><br>

<img src="/resimler/bilgi toplama/aktif/dirbuster4.JPG" alt="dirbuster"><br><br>

Bu kısımda ise bizim için önemli olan File Extension bölümü. Burada hedef sitenin hangi dilde yazıldığını belirtmemiz mecburidir. Daha sonra Start diyerek aramaya başlıyoruz. .<br><br>

<img src="/resimler/bilgi toplama/aktif/dirbscan.JPG" alt="dirbuster"><br><br>
Scan İnformation kısmında genel tarama durumu hakkında bilgiler gösterilmektedir. Result List kısmına tıklıyoruz.<br><br>
<img src="/resimler/bilgi toplama/aktif/dirbscan2.JPG" alt="dirbuster"><br><br>
Burada bize bulunan sayfaları karışık olarak tek tek listeliyor. Results Tree Wiew kısmına tıklıyoruz.<br><br>
<img src="/resimler/bilgi toplama/aktif/dirbscan3.JPG" alt="dirbuster"><br><br>
Burada ise bulunan sayfaları dizinler halinde gösteriyor. Bulunan sayfaya gitmek için sağ tıklayıp open in browser diyerek ulaşabilirsiniz.<br><br>


<strong>Dmitry Kullanımı</strong><br><br>
Kali Linux üzerinde kurulu olarak gelen bilgi toplama araçlarımızdan bir diğer de Dmitry scriptidir. Bu araç sayesinde alt domainler,whois sorgusu, e-mail adres sorgusu gibi bir çok işlemi yapabiliyoruz. Şimdi bu aracı nasıl kullanacağımıza geçelim. Terminal üzerinden Dmitry yazarak aracımıza ulaşabiliriz.Eğer parametre belirtmeden site adresi girip taratırsanız tüm taramaları gerçekleştirir.
<img src="/resimler/bilgi toplama/aktif/dmitry.JPG" alt="dmitry"><br><br>
Aracın parametreleri aşağıda açıklanmıştır.<br><br>
<ul type="disc">
<li><strong>-o</strong>: Tarama sonrası sonuçları kaydetmek için kullanılır.</li>
<li><strong>-i</strong>: IP adresi üzerinden WHOIS sorgusu gerçekleştirir. </li>
<li><strong>-w</strong>: Alanadı üstünden WHOIS sorgusu gerçekleştirir.</li>
<li><strong>-n</strong>: Netcraft üzerinden bilgileri toplar.</li>
<li><strong>-s</strong>:Kullanılan alt alan adlarını bulur.</li>
<li><strong>-e</strong>:Alan adına kayıtlı e-posta adreslerini bulur..</li>
<li><strong>-p</strong>:TCP port taraması yapar...</li>
<li><strong>-f</strong>:Filtrelenmiş port taraması yapar.</li>
</ul>

Terminal üzerinden kendi taramamızı gerçekleştirmek için Dmitry -w(domain ile whois sorgusu)  -s(subdomain tespiti) “hedef site” yazıp taratıyoruz.
<img src="/resimler/bilgi toplama/aktif/dmitry1.JPG" alt="dmitry"><br><br>

<img src="/resimler/bilgi toplama/aktif/dmitry2.JPG" alt="dmitry"><br><br>


Gördüğünüz gibi bize whois ve subdomain bilgilerini sundu. 
	
<strong>DNS Üzerinden Bilgi Toplama</strong><br><br>
Makalemizin başında belirttiğimiz gibi DNS oldukça önemlidir. Düzgün yapılandırılmamış bir DNS sunucusu saldırganın oldukça fazla bilgi edinebilmesine olanak sağlar. DNS sorgusunu kullanacağımız siteler ve araçlar makalenin devamında gösterilmiştir.<br><br>

<strong>Robtex Üzerinden DNS Sorgulaması</strong><br><br>
DNS sorgulaması yapacağımız ilk sitemiz Robtex. Bilgi toplama evresinde oldukça işe yarayan bu siteye <a href=”https://www.robtex.com/”>BURAYA TIKLAYARAK</a> ulaşabilirsiniz.
Sitemize erişim sağladıktan sonra arama kutucuğuna hedef site adresimizi yazıyoruz ve taratıyoruz<br><br>
<img src="/resimler/bilgi toplama/aktif/robtex1.JPG" alt="robtex"><br><br>
<img src="/resimler/bilgi toplama/aktif/robtex2.JPG" alt="robtex"><br><br>

Taramayı bitirdikten sonra karşımıza sonuçları listeliyor. Alt kısımda bulunan yeşil kutucuklara tıklayarak (Records,Seo,Whois) detaylı bilgilere erişebilirsiniz. Bu sitenin güzel yanlarından biri iste DNS modelini GRAPH kısmında grafiksel olarak gösteriyor olması.<br><br>
<strong>Mxtoolbox Üzerinden DNS Sorgulaması</strong><br><br>

DNS üzerinden sorgulama yapacağımız bir diğer sitemiz ise Mxtoolbox adlı web sitesi. Siteye <a href=” https://mxtoolbox.com/> BURAYA TIKLAYARAK</a> ulaşabilirsiniz.<br<br>
Öncelikle sitemize giriş yaptıktan sonra arama kutucuğuna hedef site adresimizi giriyoruz ve MX Lookup kutucuğuna tıklıyoruz..<br><br>

 
<img src="/resimler/bilgi toplama/aktif/mx.JPG" alt="mx"><br><br>

Hedef adresi analiz ettikten sonra bizlere hangi bilgilere ulaşabileceğimizi MX Lookup sekmesinde gösteriyor.Whois sorgusu,DNS kayıtları, Ters DNS sorgusu, Domain durumu gibi bir çok bilgiye erişmek mümkün.<br><br>

<img src="/resimler/bilgi toplama/aktif/mx2.JPG" alt="mx"><br><br>

Örnek olarak biz veri paketlerinin hangi aşamalardan gittiğini görmek için Trace kısmını seçtik. Daha sonra kutucuğumuzun içinde TRACE yazısı belirdi. Bu kutucuğa tıkladığımızda bize istediğimiz bilgileri verdi.<br><br>

<img src="/resimler/bilgi toplama/aktif/mx3.JPG" alt="mx"><br><br>

<strong>DNSstuff Üzerinden DNS Sorgulama</strong><br><br>

Şimdiki web sitemizin adı ise DNSstuff. Siteye <a href=” https://tools.dnsstuff.com/”> BURAYA TIKLAYARAK</a> ulaşabilirsiniz. Sitenin içerisinde DNS kayıt bilgileri,Whois sorgusu, IP sorgusu gibi farklı özellikler mevcut. <br><br>

<img src="/resimler/bilgi toplama/aktif/stuff.JPG" alt="mx"><br><br>

Biz örnek olarak DNSreport aracını kullandık. Hedef adresimizi arama kutucuğuna girdikten sonra taratmasını yaptırdık. Araç DNS sorgulamalarını yaptıktan sonra bizlere sonuçları raporladı. Burada Pass olan kısımlar herhangi bir sorunun olmadığını, Warn ile gösterilen kısımlar ise olası istismar kaynaklarını belirtiyor.<br><br>
<img src="/resimler/bilgi toplama/aktif/stuff1.JPG" alt="mx"><br><br>


<strong>Dnsdumpster ile DNS Taraması</strong><br><br>
Site üzerinden DNS sorgulaması yapacağımız son sitemiz Dnsdumpster.Siteye <a href=”https://dnsdumpster.com/”>BURAYA TIKLAYARAK</a> ulaşabilirsiniz. Siteye girdikten sonra arama kutucuğuna hedef site adresimizi yazıyoruz ve search kutucuğuna basarak taratıyoruz.<br><br>

 <img src="/resimler/bilgi toplama/aktif/dumpster.JPG" alt="mx"><br><br>


Tarama yaptıktan sonra karşımıza DNS kayıtlarını sıralıyor. Konum bilgisi,A kayıtları, MX kayıtları, TXT kayıtları ve DNS trafiğini haritalar üzerinde gösterdi.<br><br>

 <img src="/resimler/bilgi toplama/aktif/dumpster1.JPG" alt="mx"><br><br>
 
 <strong>DIG İle DNS Taraması</strong><br><br>
Linux üzerinde kurulu olarak gelen Dig ile DNS taraması yapmayı ele alacağız. Terminal üzerinden dig yazarak araca ulaşabilirsiniz. Kullanımı ve komutları aşağıda gösterilmiştir.<br><br>

 <img src="/resimler/bilgi toplama/aktif/dig.JPG" alt="dig"><br><br>

<ul type="disc">
<li><strong>-4 </strong>:Taramayı yalnızca IPv4 kullanarak yapar. </li>
<li><strong>-6</strong>: Taramayı IPv6 kullanarak yapar.</li>
<li><strong>-b </strong>:Taramanın kaynak IP adresini ayarlar. Dilerseniz port belirtebilirsiniz. </li>
<li><strong>-c </strong>:Sorgu sınıfını ayarlar. </li>
<li><strong>-f</strong>:Belirlediğiniz dosya üzerinden tarama gerçekleştirir. </li>
<li><strong>-i</strong>: Ters IPv6 sorgusu yapar.</li>
<li><strong>-k </strong>:Belirlenen dosya içerisindeki anahtarı kullanarak tarama gerçekleştirir. </li>
<li><strong>-m </strong>:Hata ayıklama modunu etkinleştirir. </li>
<li><strong>-p </strong>:Taramayı belirtilen porta göre yapar. </li>
<li><strong>-q </strong>: Taranacak olan alan adını belirtmeye yarar.</li>
<li><strong>-t </strong>:Sorgulanacak kayıt türünü belirtmeye yarar.</li>
<li><strong>-v </strong>: Aracın sürüm numarasını gösterir.</li>
<li><strong>-x </strong>: Ters DNS sorgulaması yapar.</li>
<li><strong>-y</strong>: Seçilen anahtar ile TSIG kullanarak sorgulama yapar.</li>
</ul><br>


Dig scripti ile DNS sorgulamasını yapalım. Terminalimize dig “hedef site adresi” yazıp enter tuşuna basarak taratıyoruz. Burada -q kullanarak hedef site belirtmenize gerek yoktur. Birden fazla parametre kullanımı olacaksa -q kullanılması karışıklık olmaması açısından tavsiye edilir.<br><br>

 <img src="/resimler/bilgi toplama/aktif/dig.JPG" alt="dig"><br><br>
 
Gördüğünüz gibi DNS kayıtlarını bizlere listeledi.<br><br>

<strong>NSLookup İle DNS Sorgulama</strong><br<br>


Hem Windows hem de Linux üzerinde kurulu olan bu araç ile DNS sorgulaması yapmak mümkündür. Kullanımı oldukça basittir. Terminal üzerinde nslookup -type=”sorgulama biçimi” “hedef site adresi” yazarak sorgulama yapabilirsiniz. Burada -type= kısmına sorgulamak istediğiniz DNS kaydını belirtebilirsiniz. Örneğin Nameserver kaydı sorgulamak için -type=ns yazmanız yeterlidir. Biz tüm DNS kayıtlarını sorgulamak istiyoruz. Bu yüzden any(tüm kayıtları sorgula) yazıyoruz.<br><br>
 <img src="/resimler/bilgi toplama/aktif/ns.JPG" alt="dig"><br><br>

Hedef sitenin DNS kayıtlarını bizlere sundu. Dilerseniz kendi belirlediğiniz DNS serveri üzerinden de sorgulama yapabilirsiniz. Bunun için komutların sonuna istediğimiz DNS sunucusundan sorgulanması için DNS adresi ekliyoruz. Örnek olarak biz Google DNS kullanarak sorgulayacağız.<br<br> 
<img src="/resimler/bilgi toplama/aktif/ns2.JPG" alt="dig"><br><br>
Server kısmında hangi DNS serveri üzerinden sorguladığımızı bize gösteriyor.<br><br>

<strong>Dnsenum ile DNS Sorgulama</strong><br><br>

Sıradaki DNS sorgusu için kullanacağımız aracımız dnsenum. Aracı yüklemek için terminal üzerinden apt-get install dnsenum yazıp enter tuşuna basıp yükleme işlemini gerçekleştirebilirsiniz. Aracımızın parametreleri ve açıklamaları aşağıda gösterilmiştir.<br><br>
<img src="/resimler/bilgi toplama/aktif/enum.JPG" alt="dnsenum"><br><br>

<ul type=”disc”>
<li><strong>--dnsserver </strong>:Belirlediğiniz DNS server üzerinden sorgulama gerçekleştirir. </li>
<li><strong> --enum</strong>:--threads, -s 15 -w komutlarını birlikte kullanır.</li>
<li><strong>-h</strong>: Yardım menüsünü açar.</li>
<li><strong>--noreverse</strong>: Ters sorgulamayı geçer.</li>
<li><strong>--private</strong>:Özel ips’leri kaydeder. </li>
<li><strong>--subfile</strong>:Belirlenen dosyaya tarama sonuçlarındaki alt alan adlarını kaydeder. </li>
<li><strong>-t</strong>: TCP ve UDP zaman aşımını ayarlar.</li>
<li><strong>--threads</strong>:Sorgulama yaparken kullanılacak iş parçacığı miktarını ayarlar.</li>
<li><strong>-v</strong>: Ayrıntılı bir biçimde tarama gerçekleştirir.</li>
<li><strong>-p </strong>: Taranacak Google sayfa sayısını belirler.</li>
<li><strong> -s</strong>: Google üzerinden yazılacak maksimum alt alan adı sayısı belirler.</li>

<li><strong> -f</strong>: Subdomainleri dışarıdan belirtilen bir dosya ile okur ve brute force gerçekleştirir.</li>
<li><strong> -d</strong>: Whois sorgulamalarını yaparken aradaki gecikme süresini belirler.</li>
<li><strong>-w</strong>: Whois sorgusunu C sınıfı ağ aralığıyla gerçekleştirir..</li>
<li><strong> -o</strong>: Sonuçları xml dosyası olarak kaydetmeye yarar.</li>
</ul>
<br>

Sorgulamamızı yapmak için terminalimizi açıyoruz ve dnsenum “hedef site adresi” yazıp enter tuşuna basıp taratmamızı gerçekleştiriyoruz.<br><br>
<img src="/resimler/bilgi toplama/aktif/enum2.JPG" alt="dnsenum"><br><br>
DNS kayıtlarını bizlere sunmuş oldu.<br><br>

<center><h1>NMAP Kullanımı</h1><br></center>
<img src="/resimler/bilgi toplama/nmap/logo.JPG" alt="logo"><br><br>

Aktif Bilgi Toplama yönteminin en çok tercih edilen aracı NMAP dersek yalan söylemiş olmayız.Bilgisayar Ağları Uzmanı Gordon Lyon tarafından C/C++ ve Python dilleri kullanılarak geliştirilmiştir. Diğer araçlara nazaran daha farklı ve daha detaylı tarama yöntemleri olan NMAP, bu aşamada en çok işimize yarayacak olan araçtır. Hedef sistemin portlarının durumu,işletim sistemleri,firewall kontrolü,versiyon bilgileri gibi bir çok keşfi yapmak mümkündür.İçinde hedef sistemin zafiyetini bildiren scriptler de bulunduran NMAP  kullanımına geçmeden önce temel mantığının nasıl olduğuna az çok yardımcı olacak olan, Three-way Handshake (Üçlü El Sıkışma) nedir onu anlatalım.<br><br>
İnsanlar sosyal hayatta tanışırken isimlerini birbirlerine sırayla söylerler ve memnun olduklarını dile getirirler.Sistemlerin tanışması da tıpkı bunun gibidir. Sistemler de tanışırken birbirlerine bazı paketler gönderirler.Bu paketler sayesinde iki sistem arasında iletişim kurulmuş olur. Örnek olarak makalenin devamında bahsedeceğimiz klasik TCP Connect taramasında Three-way Handshake’in nasıl gerçekleştiğini gösterelim.<br><br>

<img src="/resimler/bilgi toplama/nmap/threeway.JPG" alt="logo"><br><br>
Öncelikle bizim sistemimiz tarafından iletişim kurmak istediğimiz sisteme SYN bayrakları taşıyan bir paket yollanır..Eğer karşı sistemdeki iletişim kurulan port açıksa, sistemin çalıştığını ve gelen mesajı okuduğunu gösteren SYN-ACK bayrağı içeren bir paket yollar. Gelen SYN-ACK paketine mesajı doğrulamak için sistemimiz tarafından ACK bayraklı bir veri paketi yollanır. Böylece Three-way Handshake işlemi gerçekleşmiş, sistemler birbirini tanımış ve iletişim sağlanmış olur.<br>

Bu TCP bayrakların neler olduğunu açıklayalım.<br>
<ul type=”disc”>
<li><strong>URG</strong>:Diğer paketlerin işlenmesinden önce, gönderilen paketi işleme alması için öncelik belirten bayraktır.</li>
<li><strong>ACK</strong>:Onay bayrağıdır.Paketlerini alındığını ve teslim edildiğini belirtir.</li>
<li><strong>PSH</strong>: Gönderilen paketi karşı tarafın paketlemesi yerine gönderildiği gibi işleme almasını belirtir.</li>
<li><strong>RST</strong>:Sıfırlama işlemi anlamına gelir.Bu bayrak oturumun sıfırlanmasını belirtir. </li>
<li><strong>FIN</strong>:Daha fazla veri gönderiminin olmayacağını belirten, sistem tarafından en son gönderilen  pakette bulunan bayraktır..</li>
<li><strong>ECE</strong>:TCP eşinin ECN yeteneği olup olmadığını sorgulayan bayraktır.</li></ul>
<br>

NMAP ile ilk taramamızı gerçekleştirmeden önce şunları bilmekte fayda olduğunu düşünüyorum. İlk olarak “nmap” komutundan sonra alanadı girerseniz NMAP otomatik olarak DNS Lookup işlemi yapar. Bu da karşı sistemde log kaydı oluşturmaya neden olabilir. Bu yüzden direk IP adresi girilerek tarama yapılması tavsiye edilir. Bir ikinci konu ise NMAP port taramalarını yaparken dikkat edilmesi gereken husus port belirtilmesidir. Toplamda 65535 farklı port bulunmaktadır. NMAP ise en çok kullanılan 1024 portun taramasını gerçekleştirir. Siz kendiniz spesifik olarak bir port ya da port aralığı belirterek aramanızı özelleştirebilirsiniz.<br><br>
Tarama sonuçlarında portların açık, kapalı ya da filtreli olma durumlarını açıklayalım.

<ul type=”disc”>
<li><strong>Open </strong>:Portların açık olduğunu belirtir. Bu port üzerinden işlem yapılabilir.</li>
<li><strong> Closed</strong>:Portların kapalı olduğunu belirtir.Bu port üzerinden işlem yapılamaz. </li>
<li><strong> Filtered</strong>:Dönen verilerin filtrelendiğini belirtir. Karşı sistemde bir firewall olma durumu yüksektir. </li>
<li><strong> Unfiltered</strong>: Bir tarama türü olan ACK Scan ile yapılan taramada bu sonuç çıkabilir.Portların erişilebilir olduğunu ama açık veya kapalı olduğunu anlamadığını belirtir.</li>
<li><strong>Open | Filtered </strong>: Yine tarama türlerinden UDP,IP,FIN,NULL, ve XMAS Scan ile yapılan taramalarda dönen bu cevapta portların açık veya filtreli olduğunu anlamadığını belirtir.</li>
<li><strong>Closed | Filtered</strong>: IDLE Scan ile yapılan taramada portların kapalı ve ya filtrelenmiş olduğunu anlamadığını belirtir.</li>
</ul><br>

Ayrıca NMAP üzerinden tarama gerçekleştirirken birden fazla IP taraması ya da IP aralığı belirterek tarama yapmak mümkündür. Kullanımı aşağıda gösterilmiştir.<br><br>
<ul type=”disc”>
<li><strong>nmap 192.168.2.2 </strong>:Tek bir IP için taramayı gerçekleştirir. </li> 
<li><strong>nmap 192.168.2.2 , 192.168.2.1</strong>:Manuel olarak birden fazla belirtilen IP adreslerini tarar. IP adresinlerinin arasına virgül koyarak taranacak olan IP adreslerini belirtebilirsiniz. </li> 

<li><strong>nmap 192.168.2.5-15 </strong>:5 ila 15 dahil aralarındaki IP adresileri üzerinde tarama gerçelşeştirir. </li> 
<li><strong>nmap 192.168.2.0/24 </strong>: Subnet (256) taraması gerçekleştirir.</li> 
<li><strong> nmap –iL örnek.txt</strong>:Belirttiğimiz örnek.txt dosyası içerisindeki adresleri tarar. </li>
</ul><br>

Bunların yanında taramamızı detaylandırmak için kullanabileceğimiz bazı parametreler mevcuttur. Bu parametrelerin en çok kullanılanları aşağıda gösterilmiştir.<br><br>
<ul type=”disc”>
<li><strong>-v</strong>:Tarama sonuçlarını daha detaylı bir biçimde listeler.</li>
<li><strong>--reason </strong>: Tarama sonuçlarının hangi sebeple oluştuğunu gösterir.</li>
<li><strong>--traceroute</strong>:Hedefe giderken hangi yönlendiricilerden geçtiğini gösterir.</li>
<li><strong> -p</strong>:Hangi portların taranacağını manuel olarak seçmeye yarar. </li>
<li><strong>-n </strong>:Taramayı DNS çözümlemesi yapmadan gerçekleştirmesini belirtir.</li>
<li><strong> -F</strong>: Hızlı tarama moduyla taramayı gerçekleştirir.</li>
<li><strong> -open</strong>:Sadece açık olan portları listeler. </li>
<li><strong>-p-</strong>:Muhtemel tüm portları(65535) tarar. </li>
<li><strong> -top-ports</strong>: En çok kullanılan portları tarar. Eğer yanına bir sayı belirtirseniz, en çok kullanılan o sayının içerisindeki portları tarar. </li>
<li><strong> T(0-5)</strong>:NMAP içerisinde 6 farklı tarama hızı vardır. Normal taramalar T3 hızında yapılır. Karşı sistem tarafından dikkat çekmemek için bu tarama hızını düşürebilirsiniz. T0 en yavaş ve T5 en hızlı tarama yöntemidir. </li>
<li><strong>-O </strong>: Hedef sistemin hangi işletim sistemine sahip olduğunu gösterir.</li>
<li><strong> -oN </strong>:Tarama sonuçlarını txt olarak kaydetmek için kullanılır. Parametreden sonra kayıt edilme ismi ve txt uzantısı girilir.</li>
<li><strong>-oX </strong>: Tarama sonuçlarını xml olarak kaydetmek için kullanılır.Parametreden sonra dosya adı ve xml uzantısı girilir. </li>


NMAP ile ping atarak host taraması gerçekleştirelim. Bunun için terminalimize nmap –sP “hedef site ip” yazıp taratıyoruz.<br><br>


<img src="/resimler/bilgi toplama/nmap/p.JPG" alt="logo"><br><br>

Nmap scan report for kısmında bize host adresini gösteriyor. Biz sanal makine üzerinden test yaptığımız için direk IP adresini gösterdi. Aşağıda opsiyonel olarak yapabileceğiniz ping taramaları gösterilmiştir.<br>
<ul type=”disc”>
<li><strong> -PS</strong>: TCP Syn paketleri kullanarak taramayı gerçekleştirir.</li>
<li><strong> -PA</strong>: TCP  ACK paketleri kullanarak taramayı gerçekleştirir.</li>
<li><strong> -PU</strong>: UDP paketleri kullanarak taramayı gerçekleştirir. </li>
<li><strong> -PY</strong>: SCTP INIT paketleri kullanarak taramayı gerçekleştirir.</li>
<li><strong> -PE </strong>: ICMP Echo paketleri kullanarak taramayı gerçekleştirir.</li>
<li><strong> -PP</strong>:ICMP Zaman Damgası paketleri kullanarak taramayı gerçekleştirir .</li>
<li><strong> -PM</strong>:ICMP  Adres Maskesi  paketleri kullanarak taramayı gerçekleştirir.</li>
<li><strong> -PO</strong>: IP Protocol  paketleri kullanarak taramayı gerçekleştirir.</li>
<li><strong> -PR</strong>:ARP paketleri kullanarak taramayı gerçekleştirir.</li>
</ul>


Örnek olarak NMAP ile standart bir tarama gerçekleştirelim. Daha sonra tarama çeşitlerini detaylı olarak inceleyeceğiz.Terminal üzerinden “nmap hedef IP” yazıp enter tuşuna basarak taratıyoruz.<br><br>

<img src="/resimler/bilgi toplama/nmap/1.JPG" alt="logo"><br><br>


Taramanın sonunda bizlere hangi portların açık,hangilerinin filtreli olduğu ve hangi servisi kullandıklarını listeledi.<br><br>


<strong>TCP Syn Scan</strong><br><br>

TCP SYN bayraklı paket gönderilerek yapılan tarama türüdür. Eğer karşı port açıksa SYN+ACK bayrağı döner.İstemci gelen veriyi RST bayraklı veri paketi ile cevaplar. Yani Three-way Handshake gerçekleşmemiş olsa bile Log kayıtlarında gözükme ihtimali vardır.<br><br>

<img src="/resimler/bilgi toplama/nmap/syn.JPG" alt="logo"><br><br>
Eğer port kapalıysa karşı taraftan RST+ACK bayrağı döner.İletişim sonlandırılır.<br><br>
<img src="/resimler/bilgi toplama/nmap/syc2.JPG" alt="logo"><br><br>

Terminal üzerinden taramamızı gerçekleştiriyoruz. Nmap -sS “hedef IP” yazıyoruz. --reason parametresi ile de sonuçların neden gerçekleştiğini göstermesini istiyoruz.<br><br>
<img src="/resimler/bilgi toplama/nmap/2.JPG" alt="syn"><br><br>


Tarama sonucunda hangi portların açık,hangilerinin kapalı olduğunu bizlere gösterdi. Cevap alınamayan portları filtered olarak raporladı. Cevap alınan portlarda ise neden açık olduğunu yani gelen cevapları bizlere gösterdi.<br><br>

<strong>TCP Connect Scan</strong><br><br>
Makalenin başında belirttiğimiz gibi klasik Three-way Handshake olayının gerçekleştiği tarama türüdür.Log kayıtlarında görünür. İstemci tarafından SYN bayraklı veri paketi gönderilir. Port açıksa karşı taraftan SYN+ACK bayraklı veri paketleri gelir.Tekrar istemci tarafından ACK bayraklı veri paketi gönderilerek tarama gerçekleşir.<br><br>

<img src="/resimler/bilgi toplama/nmap/syc1.JPG" alt="connect"><br><br>

Port kapalıysa karşı taraftan RST+ACK paketi gelir.İletişim sonlandırılır.<br><br>

<img src="/resimler/bilgi toplama/nmap/syc2.JPG" alt="syc"><br><br>


Terminal üzerinden -sT parametresi ile tarama gerçekleştirilir. <br><br>
<img src="/resimler/bilgi toplama/nmap/3.JPG" alt="st"><br><br>



<strong>FIN Scan</strong><br><br>

Hedef sistemde TCP ile bağlantı isteği olmadan yapılan arama türüdür.İstemci tarafından FIN bayraklı bir veri paketi gönderilir.Eğer karşı taraftan yanıt gelmez ise bu o portun açık olduğunu gösterir.<br><br>

<img src="/resimler/bilgi toplama/nmap/fn.JPG" alt="fn"><br><br>
Eğer gönderilen FIN bayraklı veri paketine karşılık olarak RST+ACK bayraklı veri paketi gelirse o portun kapalı olduğunu gösterir.

<img src="/resimler/bilgi toplama/nmap/fn2.JPG" alt="fn"><br><br>
Terminal üzerinden taramamızı gerçekleştirmek için -sF parametresini yazıyoruz. Burada -v kullanma amacımız sonuçları daha detaylı bir biçimde sunması için.<br><br>
<img src="/resimler/bilgi toplama/nmap/fin.JPG" alt="fn"><br><br>

<strong>XMas Tree Scan</strong><br><br>
İstemci tarafından TCP frame içine URG,PSH ve FIN bayrakları ile paket veri paketi gönderimi  yapılır.Eğer yanıt gelmez ise karşı portun açık olduğu anlaşılır.<br><br>
<img src="/resimler/bilgi toplama/nmap/xmas1.JPG" alt="xmas"><br><br>

Eğer gönderilen veri paketine karşılık RST+ACK bayraklı bir veri paketi geliyorsa o port kapalıdır.<br><br>
<img src="/resimler/bilgi toplama/nmap/xmas2.JPG" alt="xmas"><br><br>
Terminal üzerinden taramamızı gerçekleştirmek için -sX parametresini kullanıyoruz.<br><br>	
<img src="/resimler/bilgi toplama/nmap/xmas.JPG" alt="xmas"><br><br>

<strong>Null Scan</strong><br><br>

Herhangi bir bayrak içermeyen veri paketleri yollayarak taramayı gerçekleştirir. Eğer karşı sistemden bir cevap alınmazsa o portun açık olduğu anlaşılır.<br><br>
<img src="/resimler/bilgi toplama/nmap/null1.JPG" alt="null"><br><br>
Eğer port kapalıysa karşı sistemden RST+ACK bayraklı veri paketi dönüşü gelir.
<img src="/resimler/bilgi toplama/nmap/null2.JPG" alt="null"><br><br>

Terminal üzerinden -sN komutu ile tarama gerçekleştirilir.<br><br>

<img src="/resimler/bilgi toplama/nmap/null.JPG" alt="null"><br><br>


<strong>Ping Scan</strong><br><br>


İstemci tarafından hedef sisteme tek bir ICMP Echo istek paketi yollayarak gerçekleştirdiği tarama türüdür. Eğer port açık ise karşı sistemden ICMP ECHO Reply veri paketi dönecektir.<br><br>

<img src="/resimler/bilgi toplama/nmap/pingscan1.JPG" alt="ping"><br><br>

Eğer port kapalı veya ICMP filtresi var ise karşı sistemden herhangi bir cevap alınmayacaktır.<br><br>
<img src="/resimler/bilgi toplama/nmap/pingscan2.JPG" alt="ping"><br><br>

Terminal üzerinden -sP parametresi ile tarama gerçekleştirilir.<br><br>
<img src="/resimler/bilgi toplama/nmap/ping.JPG" alt="ping"><br><br>
<strong>UDP Scan</strong><br><br>ı
İstemci tarafından hedef sisteme UDP paketleri gönderilir.Eğer port açık ise aynı şekilde UDP paketi göndererek cevap verir.<br><br>

<img src="/resimler/bilgi toplama/nmap/udp1.JPG" alt="udp"><br><br>
Eğer port kapalı ise gönderilen UDP paketine karşılık ICMP Port Unreachable cevabı gelecektir.<br><br>
<img src="/resimler/bilgi toplama/nmap/udp2.JPG" alt="udp"><br><br>
Eğer UDP paketine karşılık herhangi bir cevap gelmezse port Open | Filtred kabul edilecektir. NMAP tanıtımının başında bu açıklamalar mevcut.<br><br<
<img src="/resimler/bilgi toplama/nmap/udp2.JPG" alt="udp"><br><br>
Terminal üzerinden -sU parametresi ile tarama gerçekleştirilir.<br><br>
<img src="/resimler/bilgi toplama/nmap/udp.JPG" alt="udp"><br><br>

<strong>ACK Scan</strong><br><br>
İstemci tarafından TCP ACK bayraklı veri paketini gönderildiği tarama türüdür.Hedef sistemden RST bayraklı paket gelirse port Unfiltred olarak kabul edilir.<br><br>
<img src="/resimler/bilgi toplama/nmap/ack1.JPG" alt="ack"><br><br>

Eğer gönderilen ACK bayraklı veriye karşılık herhangi bir cevap gelmezse veya ICMP mesajı dönerse o port Filtred olarak kabul edilir.<br><br>
<img src="/resimler/bilgi toplama/nmap/ack2.JPG" alt="ack"><br><br>
Terminal üzerinden -sA parametresi ile kullanılır.<br><br>
<img src="/resimler/bilgi toplama/nmap/ack.JPG" alt="ack"><br><br>


<strong>Window Scan</strong><br><br>

İstemci tarafından TCP ACK bayraklı veri paketinin yollanarak iletişimin başlatıldığı tarama türüdür. ACK taramasından farklı olarak portların açıklık durumunu gösterir.Hedef sistemden RST+win=”sayı” 0’dan farklı ise portun açık olduğu anlaşılır.<br><br>
<img src="/resimler/bilgi toplama/nmap/win1.JPG" alt="win"><br><br>
Eğer hedef sistemden gelen yanıtta win değeri 0 ise o port kapalı olarak kabul edilir.<br><br>
<img src="/resimler/bilgi toplama/nmap/win2.JPG" alt="win"><br><br>
Terminal üzerinden tarama gerçekleştirilirken -sW parametresi kullanılır.<br><br>
<img src="/resimler/bilgi toplama/nmap/win.JPG" alt="win"><br><br>
<strong>NMAP İle İşletim Sistemi Taraması </strong><br><br>

NMAP ile hedef sistemin işletim sistemi tespitini yapmak da mümkündür.Bunu için teriminale -O yazarak taramamızı gerçekleştiriyoruz.<br><br>

<img src="/resimler/bilgi toplama/nmap/os.JPG" alt="os"><br><br>

Runing kısmında bize işletim sistemini gösteriyor. Biz sanal makine üzerine testlerimizi yaptığımız için birden fazla göstermesi normal.<br><br>

<strong>NMAP İle Versiyon Keşfi</strong><br><br>
Bir başka tarama özelliğimiz ise çalışan servislerin versiyon tespitini yapmak. Versiyon tespiti yapılırken eğer root iseniz NMAP önce TCP SYN taraması yapıyor, daha sonra portlar ile iletişime geçerek bilgi toplamaya başlıyor.Eğer root değilseniz bu işlemi TCP Syn Scan ile başlatmak yerine TCP Connect Can ile başlatıyor daha sonra portlar ile iletişime geçiyor.<br><br>

<img src="/resimler/bilgi toplama/nmap/version.JPG" alt="version"><br><br>
Version kısmında bizlere çalışan servislerin versiyonlarını gösterdi. Bu versiyon bilgileri ile daha sonra NSE(Nmap Script) ile zafiyet keşfi yapacağız.<br><br>

<strong>NMAP İle Agresif Tarama</strong><br><br>
Bir başka tarama yöntemi de agresif taramadır. Bu tarama yöntemi ile hedef sistemin port taraması, versiyon tespiti, traceroute tespiti,işletim sistemi tespiti gibi birçok işlemi tek parametre ile yapmak mümkün.Bunun için terminalimizden -A parametresi ile taramamızı gerçekleştiriyoruz.<br><br>
<img src="/resimler/bilgi toplama/nmap/a1.JPG" alt="agresif"><br><br>
<img src="/resimler/bilgi toplama/nmap/a2.JPG" alt="agresif"><br><br>

<strong>NMAP NSE Script</strong><br><br>

NMAP içerisinde kendine has özel script dosyaları mevcuttur. Bu dosyaları kullanarak taramaları gerçekleştirebileceğiniz gibi kendiniz manuel olarak girdiğiniz bir script ile de tarama gerçekleştirebilirsiniz. NMAP içerisinde çok fazla sayıda script dosyası bulunmaktadır.Bunların listesine <a href=”https://nmap.org/nsedoc/”>BURAYA TIKLAYARAK</a>  ulaşabilirsiniz. Categories kısmından ise bulmak istediğiniz script türünü özelleştirebilirsiniz.<br><br>

<img src="/resimler/bilgi toplama/nmap/nsecategori.JPG" alt="kategori"><br><br>
 Örnek olarak kategori kısmında bulunan vuln(zafiyet) taraması gerçekleştirelim.Terminal üzerinden nmap -script vuln “hedef IP” yazıp taramamızı başlatıyoruz.<br><br>
<img src="/resimler/bilgi toplama/nmap/nse1.JPG" alt="kategori"><br><br>
<img src="/resimler/bilgi toplama/nmap/nse2.JPG" alt="kategori"><br><br>

NMAP içerisinde bulunan tüm zafiyet scriptlerini hedef IP üzerinde taradı ve VULNERABLE: kısmında bu zafiyetin ne olduğu hakkında bilgi verdi. <br><br>
Seçtiğimiz bir script ile sorgulama yapmak istersek terminale --script “script adı” “hedef IP” yazıp taramamızı gerçekleştiririz. 
