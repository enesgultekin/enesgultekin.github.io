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

<strong>Reverse Whois<br></strong>
Reverse Whois site sahibinin e-mail adresi üstünden ya da direk site adı girilerek, kayıtlı olan diğer domain adreslerini bulmaya yarar. İnternet üzerinde birçok Reverse Whois sorgusu yapan siteler mevcuttur.Biz bunlardan reversewhois.io adlı siteyi örnek göstereceğiz.<br><br>

İlk olarak sitemize giriyoruz.Siteye<a href="https://reversewhois.io">BURAYA TIKLAYARAK</a> ulaşabilirsiniz. Daha sonra arama çubuğuna e-posta adresi ya da site adresini yazıyoruz ve enter tuşuna basıyoruz.<br><br>

<img src="/resimler/bilgi toplama/whois/rwhois1.JPG" alt="rwhois1"><br><br>

Karşımıza bu site sahibinin üzerine kayıtlı olan diğer site domainlerini listeliyor.<br><br>

<img src="/resimler/bilgi toplama/whois/rwhois1.JPG" alt="rwhois1"><br><br>

<strong>IP Aralığı Tespit Etme</strong><br>
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

Üçüncü sorgulama yapacağımız site ise Apnic.Net.Siteye <a href=”https://www.apnic.net/” target=”_blank”>BURAYA TIKLAYARAK</a> ulaşabilirsiniz.<br><br>

Siteye girdiğimizde sağ üst kısımdaki arama kutucuğuna hedef IP adresini yazıp enter tuşuna basıp bekliyoruz.<br><br>


<img src="/resimler/bilgi toplama/aralık/apnic1.JPG" alt="apnic1"><br><br>
Inetnum kısmında bize IP aralığını gösteriyor.<br><br>
<img src="/resimler/bilgi toplama/aralık/apnic2.JPG" alt="apnic2"><br><br>
<center><h1>Archive.Org Nedir?</h1></center><br>
1996 yılında kurulmuş olan bu site kullanıcılara internet üzerinde kaydettiği dökümanları sunmaktadır.Bu dökümanlar içerisinde resim,video,müzik,kitap,yazılım gibi bir çok seçenek sunmaktadır.Bizim ilgili olduğumuz alan ise bu sitenin aynı zamanda web sitelerinin belirli aralıklarla görüntüsünü kaydetmesidir. Bu yol bize kapanmış bir sitenin, kapanmadan önceki görüntülerine erişme imkânı sağlamaktadır.<br><br>

İlk olarak sitemize giriyoruz.<a href="https://archive.org">Buraya Tıklayarak</a> ulaşabilirsiniz.Sol üst köşeden sarı renkle gösterilmiş olan WEB kısmına tıklıyoruz. Karşımıza WaybackMachine adında bir tarama kutucuğu çıkıyor. <br><br>

<img src="/resimler/bilgi toplama/archive/archive1.JPG" alt="archive1"><br><br>
Bu arama kutucuğuna hedef sitemizin adresini giriyoruz ve enter tuşuna basıyoruz.<br><br>
<img src="/resimler/bilgi toplama/archive/archive2.JPG" alt="archive2"><br><br>
Karşımıza yılların sıralandığı çubuk şeklinde bir tarih sırası ve altında ise  ay ve günlerin olduğu bir tarih paneli çıkıyor. Yılların belirtildiği çubuğun olduğu kısımda ise hangi yıllar ne kadar görüntü almışsa onu ifade eden bir histogram grafiği mevcut. Altında ise ayların içinde mavi ile işaretlenmiş günler mevcut. Bu mavi işaretle gösterilmiş olan günler bize o gün görüntü kaydının alındığını ifade etmektedir.Biz 2005 yılını seçtik ve 23 Şubat tarihli görüntü kaydına tıkladık.<br><br>
<img src="/resimler/bilgi toplama/archive/archive3.JPG" alt="archive3"><br><br>
Gördüğünüz gibi seçtiğimiz tarihdeki sitenin görüntüsünü bizlere sundu.<br><br>
<strong>YouGetSignal İle Bilgi Toplama</strong><br><br>
	
Pasif bilgi toplama sürecinde bize yardımcı olan sitelerden bir diğeri de YouGetSignal adlı web sitesidir.Siteye <a href=https://www.yougetsignal.com> BURAYA TIKLAYARAK</a> ulaşabilirsiniz.
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
<img src="/resimler/bilgi toplama/aktif/robtex3.JPG" alt="robtex"><br><br>



