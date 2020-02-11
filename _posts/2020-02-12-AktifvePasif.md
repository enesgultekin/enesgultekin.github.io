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

<img src="/resimler/bilgi toplama/ip/osi.jpg" alt="osi">
