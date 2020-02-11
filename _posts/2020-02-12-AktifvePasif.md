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
 <li>Pasif Bilgi toplama </li>
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
<ul type=”circle”>	
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

Bu operatörler ile kendiniz site açıklarını bulan dorklar oluşturabilirsiniz. Bunların yanında hazır olarak kullanıcılar tarafından yayınlanan dorkların listesi <a href=”https://www.exploit-db.com/google-hacking-database”>BU SİTEDE </a>mevcuttur.<br><br>



<h4>Bing İle Tarama</h4><br>
Pasif bilgi toplama sürecinde Google yanında Bing ile de hedef site hakkında bilgi edinmek mümkündür.Parametreleri Google ile hemen hemen aynı olsa da ufak farklar mevcuttur. Parametreler aşağıda listelenmiştir.
<img src="/resimler/bilgi toplama/webs/bing.JPG" alt="bing"><br><br>
<ul type=”disc”>
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

</ul>

<h3>Whois Analizi</h3><br>
<p> Whois sorgusu, hedef site hakkında bize birçok bilgi sunar. Site sahibinin iletişim bilgileri,adres bilgileri, işletme bilgileri,e-posta bilgileri vb. birçok şeyi whois sorgusu ile öğrenebiliriz. İnternet üzerinden whois analizi yapabilecek bir çok web site mevcuttur.Bunun yanında Linux ile terminal üzerinden kolaylıkla whois sorgusu yapılabilir. İlk örneğimizi Linux üzerinden gösterelim.</p><br><br>

<hr>Örnek<hr>
Öncelikle Terminalimizi açıyoruz ve<strong> whois “site adı” </strong> yazıp enter tuşuna basıyoruz. <br><br>

<img src="/resimler/bilgi toplama/whois/whois1.JPG" alt="whois"><br><br>

<img src="/resimler/bilgi toplama/whois/whois2.JPG" alt="whois2"><br><br>
Gördüğünüz gibi site sahibinin birçok bilgisi karşımıza çıktı.Bunu birde whois.net sitesi üzerinden yaparak gösterelim.<br><br>
<hr>Örnek<hr>
Öncelikle whois.net adlı sitemize giriyoruz.Daha sonra karşımıza çıkan arama motoruna hedef domain adresini yazıyoruz.Enter tuşuna basıp bekliyoruz. <br><br>

<img src="/resimler/bilgi toplama/whois/whois3.JPG" alt="whois3"><br><br>

<img src="/resimler/bilgi toplama/whois/whois4.JPG" alt="whois3"><br><br>

<h3>Reverse Whois</h3><br>
<p>Reverse Whois site sahibinin e-mail adresi üstünden ya da direk site adı girilerek, kayıtlı olan diğer domain adreslerini bulmaya yarar. İnternet üzerinde birçok Reverse Whois sorgusu yapan siteler mevcuttur.Biz bunlardan reversewhois.io adlı siteyi örnek göstereceğiz.</p><br><br>

İlk olarak sitemize giriyoruz. Daha sonra arama çubuğuna e-posta adresi ya da site adresini yazıyoruz ve enter tuşuna basıyoruz.<br><br>

<img src="/resimler/bilgi toplama/whois/rwhois1.JPG" alt="rwhois1"><br><br>

Karşımıza bu site sahibinin üzerine kayıtlı olan diğer site domainlerini listeliyor.<br><br>

<img src="/resimler/bilgi toplama/whois/rwhois1.JPG" alt="rwhois1"><br><br>

<h3>IP Aralığı Tespit Etme</h3><br>
İnternet siteleri üzerinden hedef sistemin IP aralıklarını bulabileceğimiz bir çok site mevcuttur. Bunlardan bir kaçını makalemizde örnek olarak göstereceğiz.<b><br>

<h4>Arin.Net</h4>

İlk göstereceğimiz sitenin adı Arin.Net. Siteye <a href=https://www.arin.net” target=”_blank”>BURAYA TIKLAYARAK</a> ulaşabilirsiniz.<br><br>

İlk olarak sitemize giriş yaptıktan sonra pencerenin sağ üst kısmında bulunan arama kutucuğuna hedef sitenin IP adresini yazıyoruz.Enter tuşuna basıp bekliyoruz. <br><br>

<img src="/resimler/bilgi toplama/aralık/arin1.JPG" alt="arin"><br><br>


Network kısmında bize sitenin hangi IP aralığında olduğunu gösteriyor.<br><br>
<img src="/resimler/bilgi toplama/aralık/arin2.JPG" alt="arin"><br><br>

<h4>Ripe.Net</h4><br>

İkinci sorgulama yapacağımız sitemiz ise Ripe.Net. Siteye <a href=”https://www.ripe.net/” target=”_blank”>BURAYA TIKLAYARAK</a>ulaşabilirsiniz.<br><br>

Sitemize girdiğimizde karşımıza gelen pencerede, sağ üst köşede bulunan arama kutucuğuna hedef IP adresimizi giriyoruz ve enter tuşuna basıp bekliyoruz.<br><br>

<img src="/resimler/bilgi toplama/aralık/ripe1.JPG" alt="ripe"><br><br>


Inetnum kısmında sitenin hangi IP aralığında olduğunu biz gösteriyor.<br><br>

<img src="/resimler/bilgi toplama/aralık/ripe2.JPG" alt="ripe"><br><br>

<h4>Apnic.Net</h4><br>

Üçüncü sorgulama yapacağımız site ise Apnic.Net.Siteye <a href=”https://www.apnic.net/” target=”_blank”>BURAYA TIKLAYARAK</a> ulaşabilirsiniz.<br><br>

Siteye girdiğimizde sağ üst kısımdaki arama kutucuğuna hedef IP adresini yazıp enter tuşuna basıp bekliyoruz.<br><br>


<img src="/resimler/bilgi toplama/aralık/apnic1.JPG" alt="apnic1"><br><br>
Inetnum kısmında bize IP aralığını gösteriyor.<br><br>
<img src="/resimler/bilgi toplama/aralık/apnic2.JPG" alt="apnic2"><br><br>
<center><h1>Archive.Org Nedir?</h1></center><br>
1996 yılında kurulmuş olan bu site kullanıcılara internet üzerinde kaydettiği dökümanları sunmaktadır.Bu dökümanlar içerisinde resim,video,müzik,kitap,yazılım gibi bir çok seçenek sunmaktadır.Bizim ilgili olduğumuz alan ise bu sitenin aynı zamanda web sitelerinin belirli aralıklarla görüntüsünü kaydetmesidir. Bu yol bize kapanmış bir sitenin, kapanmadan önceki görüntülerine erişme imkânı sağlamaktadır.<br><br>

İlk olarak sitemize giriyoruz.<a href=https://archive.org>Buraya Tıklayarak Ulaşabilirsiniz.</a>Sol üst köşeden sarı renkle gösterilmiş olan WEB kısmına tıklıyoruz. Karşımıza WaybackMachine adında bir tarama kutucuğu çıkıyor. <br><br>

<img src="/resimler/bilgi toplama/archive/archive1.JPG" alt="archive1"><br><br>
Bu arama kutucuğuna hedef sitemizin adresini giriyoruz ve enter tuşuna basıyoruz.<br><br>
<img src="/resimler/bilgi toplama/archive/archive2.JPG" alt="archive2"><br><br>
Karşımıza yılların sıralandığı çubuk şeklinde bir tarih sırası ve altında ise  ay ve günlerin olduğu bir tarih paneli çıkıyor. Yılların belirtildiği çubuğun olduğu kısımda ise hangi yıllar ne kadar görüntü almışsa onu ifade eden bir histogram grafiği mevcut. Altında ise ayların içinde mavi ile işaretlenmiş günler mevcut. Bu mavi işaretle gösterilmiş olan günler bize o gün görüntü kaydının alındığını ifade etmektedir.Biz 2005 yılını seçtik ve 23 Şubat tarihli görüntü kaydına tıkladık.<br><br>
<img src="/resimler/bilgi toplama/archive/archive3.JPG" alt="archive3"><br><br>
Gördüğünüz gibi seçtiğimiz tarihdeki sitenin görüntüsünü bizlere sundu.<br><br>
h5>YouGetSignal İle Bilgi Toplama</h5>
	
Pasif bilgi toplama sürecinde bize yardımcı olan sitelerden bir diğeri de YouGetSignal adlı web sitesidir.Siteye <a href=https://www.yougetsignal.com> BURAYA TIKLAYARAK</a> ulaşabilirsiniz.
<br>
İlk olarak sitemize giriş yapıyoruz. Karşımıza tools kısımlı bir pencere çıkıyor. Burada site içerisinde yapabileceğimiz taramalar mevcuttur. Her birinin açıklaması aşağıda verilmiştir.
<img src="/resimler/bilgi toplama/webs/yougetsignal.JPG" alt="yougetsignal"><br><br>

<ul type=”disc”>
<li><strong>Port Forwarding Tester</strong>:Hedef sitenin belirtilen portunun açık olup olmadığını bulur.</li> 
<li><strong>What Is My Ip Adress?</strong>:Bağlantı sağladığınız bilgisayarın IP adresini gösterir.</li>
<li><strong>Network Location Tool</strong>:Hedef adresin hangi konumda olduğunu harita üzerinde gösterir. </li>
<li><strong>Phone Number Geolocator</strong>:Sadece ABD hatlarını destekleyen numara sorgulama aracı.</li>
<li><strong>Reverse E-Mail Lookup Tool</strong>:Girilen e-mail adresinin kime ait olduğunu sosyal medya üzerinde arama yaparak bulmaya yarar.</li>
<li><strong>Reverse IP Domain Check</strong>:Ters IP sorgulaması yapmaya yarar.</li>
<li><strong>Whois Lookup Tool</strong>:Whois sorgulaması yapmaya yarar.</li>
</ul>

<h5>Netcraft İle Bilgi Toplama</h5><br>

Sıkça kullanılan sitelerden bir diğeri de Netcraft. Benim de oldukça hoşuma giden bu web sitesi sayesinde hedef sistemin DNS bilgileri,İşletim Sistemleri ve IP bilgileri gibi daha bir çok bilgiye erişmek mümkün. Biz Netcraft sitesinin Site Report kısmını kullanıyoruz.<a href=https://sitereport.netcraft.com/>BURAYA TIKLAYARAK</a> siteye ulaşabilirsiniz.
Sitemize girdikten sonra karşımıza çıkan arama bölümüne hedef site adını yazıyoruz. <br><br>
<img src="/resimler/bilgi toplama/webs/netcraft.JPG" alt="netcraft"><br><br>

<img src="/resimler/bilgi toplama/webs/netcraft2.JPG" alt="netcraft2"><br><br>
<img src="/resimler/bilgi toplama/webs/netcraft3.JPG" alt="netcraft3"><br><br>

<h5>Shodan İle Bilgi Toplama</h5><br>
Shodan diğer arama motorlarından farklı olarak web sitelerinden ziyade bizlere internete açık olan sunucular hakkında bilgi vermektedirOyun Sunucuları,Veritabanları,Kameralar ve giriş panelleri açık olan bir çok sunucuyu bizlere göstermektedir. Shodan kullanımı aşağıda gösterilmiştir.<br>
Siteye <a href=https://shodan.io>BURAYA TIKLAYARAK</a>ulaşabilirsiniz.
Öncelikle sitemize giriyoruz.

<img src="/resimler/bilgi toplama/webs/shodan.JPG" alt="shodan"><br><br>


Spesifik olarak arama gerçekleştirmeden önce site içerisinde bulunan hazır araçları göstermek istiyorum. Bunun için arama kutucuğunun altında bulunan Explore kısmına tıklıyoruz.


<img src="/resimler/bilgi toplama/webs/shodanexplore.JPG" alt="shodan"><br><br>
Daha sonra karşımıza gelen ekranda farklı araçların olduğunu görüyorsunuz. Databases,Video Games, Industrial Control Systems,Webcam, Netcam, Cams gibi.

<img src="/resimler/bilgi toplama/webs/shodanexplore1.JPG" alt="shodan"><br><br>


Biz örnek olarak bir sunucularına erişim olan Webcam taraması yapacağız. Webcam kısmına tıklıyoruz.<br><br>
<img src="/resimler/bilgi toplama/webs/shodanexplore2.JPG" alt="shodan"><br><br>

Karşımıza sunucusu açık olan Webcam listesini çıkardı. İlk sıradakine tıklıyoruz ve daha detaylı bilgi ediniyoruz.







