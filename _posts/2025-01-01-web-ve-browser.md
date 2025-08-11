---
layout: post
title: Web ve Browser
subtitle: Web ve browser nasıl çalışır ?
tags: [web, Broser]
author: Taha
---

Herkese selam bugün ilk taskım olan web ve browser nasıl çalışır ondan bahsedeceğim! Hazırsanız başlayalım 

## Web nedir ve nasıl çalışır

Bildiklerime göre **Web ve Browser**'ın nasıl çalıştığını anlamamız için önce Web ve İnternetin nasıl çalıştığını anlamamız gerekiyor.

## Web nedir ?

her zaman görmüşüzdür linklerde **www**.örnek.com işte burdaki www **World Wide Web** dir ve biz buna kısaca web diyoruz. Web yazı,
görsel gibi kısaca multimedya ve içerikleri internet aracılığıyla görünteleyibildiğimiz sayfalardır. İşin bu kısmında ise karşımıza
HTML (Hyper text markup language) ve HTTP (hyper text transfer protocol) çıkıyor. Peki nedir bunlar ?

## HTTP ve HTML
HTTP ve HTML birbirleri için önemli ancak farklı şeylerdir 

**HTTP** **H**yper **T**ext **T**ransfer **P**rotocol demek olduğundan bahsetmiştik şimdi bunun ne işe yaradığını ele alalım
İnternet üzerinde bilgi iletmeyi sağlayan bir protokoldür. Bu protokol, bir web tarayıcısı ile bir web sunucusu arasındaki iletişimi
 sağlar. Daha açık bir ifadeyle istemci(client) ve sunucu(server) arasındaki veri transferini yönetir. Bu sayede tarayıcının web sitelerini
  görüntülemesini, dosyaları indirmesini veya dosya göndermesini sağlar.

HTTP, tarayıcının web sunucularından HTML, CSS, JavaScript gibi dosyaları talep etmesini ve bu dosyaları alarak kullanıcının bilgisayarında
 görüntülemesini sağlar. Bu sayede kullanıcılar internet üzerinde gezinirken web sayfalarını görebilirler.

HTTP, dosya indirme ve yükleme işlemlerini de yönetir. Kullanıcılar, tarayıcı aracılığıyla HTTP protokolünü kullanarak dosya indirebilirler.
 Web sayfalarındaki form alanları aracılığıyla kullanıcılar HTTP protokolü sayesinde sunucuya bilgi gönderebilir. Form doldurma, çeşitli hizmetlere
  kayıt olma gibi işlemleri sağlar.

Web uygulamaları arasında veri paylaşımını sağlamak için kullanılan API’lar (Application Programming Interface) HTTP protokolünü temel alır.
 Bu sayede farklı uygulamalar arasında veri alışverişi protokol üzerinden gerçekleşir

 HTTP’nin çalışma prensibi client — server ilişkisine dayanmaktadır bunu istek ve cevap gibi düşünebiliriz. Bu çalışma prensibini açıklamak gerekirse:

Request :
Kullanıcı bir web sayfasını görüntülemek istediğinde istemci client bir HTTP isteği yapar. İstek, belirli bir kaynağı (örneğin bir web sayfasını) talep eden bir mesajdır. Bu mesaj, isteğin türünü GET, POST gibi ve talep edilen kaynağın adresini içerir.

Processing :
Sunucu, isteği aldıktan sonra talep edilen kaynağı bulur ve gerekli işlemleri gerçekleştirir. Bu işlemler nedir? Veri tabanı sorguları, dosya okuma/yazma işlemleri veya dinamik içerik oluşturma gibi çeşitli işlemlerdir.

Response :
Sunucu talep edilen işlemi tamamladıktan sonra bir HTTP yanıtı oluşturur. Yanıt, sunucunun yaptığı işlemlerin sonucunu içerir.

İnternet Üzerinde Transfer:
Sunucu, oluşturulan yanıtı HTTP protokolü ile istemciye geri gönderir ve kullanıcının görüntülemesini sağlar.

Bu client — server iletişim şekli, HTTP’nin temel çalışma prensibini oluşturur. client bir kaynak talep eder ve server bu talebi karşılar. Bu basit işlem sayesinde internet üzerinden bilgi alışverişi sağlanır.

## HTTPS nedir ?

Yine web adreslerinde gördüğümüz https HTTP ile aynı ancak sondaki **S** **Security**'i belirtir yani HTTP şifrelenmemiş  veri iken HTTPS şifrelenmiş veridir bu yüzden https ile verilerimiz daha güvendedir  

## HTML nedir ? 

HTML; **H**yper **T**ext **M**arkup **L**anguage'dir isminden de anlaşılacağı üzere bir işaretleme dilidir bu işaretlemeye biz **tags** diyoruz örneğin benim burdaki
tags yazısını kalınlaştırmam bir tag sayesinde oldu. HTML taglardan oluşur bu taglar sayesindede biz sitemizin iskeletini oluşturmuş oluruz iskeletten örnek vermişken 
web sitelerini bir insan vücudu olarak düşünelim. Bu vücudun iskelet sistemini HTML oluşturur neyin nerede olacağını ve dik durmasını sağlayan kemiklerdir yani HTML
ve tabii ki kaslarımızda var vücudumuzda işte bu kaslar **javascript**'tir hareketimizi sağlar ve istediğimiz yere yönelip hareketimizi sağlar sitemiz için en basit örnek bir butona basıp bizi sitemizdeki farklı bir yere götürmesidir. Son olarakda bu kaslarımızın üzerinde derimiz var bunuda sitemizde CSS olarak adlandırıyoruz CSS, tamamen dış görünüş üzerinedir sitemizin butonları ve arayüzü CSS sayesinde şekil alır.


## Web nasıl çalışır 

Artık Web nedir ve nelerden oluşur biliyoruz şimdi ise nasıl çalıştığına bakalım.

Web, client ve server arasında veri alışverişi yaparak çalıştığını söylemiştir. Her bir web sayfası ve içerik, bu iki taraf arasında sürekli bir etkileşim sonucu oluşturulur.

**Client** :
Client, web sayfasına erişmeye çalışan cihazdır. Çoğunlukla bu bir web tarayıcısıdır Google Chrome, Mozilla Firefox, Safari gibi. Tarayıcı, kullanıcının istediği sayfayı alır ve görüntüler.

**Server** :
Server, web sitesi dosyalarının ve içeriğinin depolandığı bilgisayardır. Bu sunucu, istemciden gelen istekleri alır, işler ve karşılığında içerik gönderir.

{: .box-note}
**Unutmayalım:** İnternete erişmi olan bütün cihazlar haberleşmek için bir IP adresi vardır



Ve şöylede bir şey var ki her site domaini (alan adı) aslında bir IP adresidir hatta insanlar bu sitelere erişimin kolaylaşması adında domain sistemini geliştirmişlerdir çünkü ben bir siteye girmek için sayıları aklımda tutmaktansa sitenin domainini (genellikle bu yüzden sitenin isminin amacı olması iyidir) aklımda tutmam daha kolay olucaktır. Ancak bilgisayarda işler farklı bilgisayar bu siteyi IP adresi olarak arar ve domaini IP adresine dönüştüren şeyde **DNS**'tir

**DNS nedir ?** DNS yani **D**omain **N**ame **S**ystem'dir az önce bilgisayarların haberleşmek için IP adresi kullandığını söylemiştik işte DNS ise tamda burada devreye giriyor. Bizim girdiğimiz bütün domainlerin IP adresini buluyor ve bunuda HTTP protokolünden anlatıcak olursak bizim girdiğimiz domain DNS server'ine bir istek olarak gider server bu ip adresindeki siteyi bize bulur ve cevap olarak geri gönderir ve tarayıcda web sayfası görüntülenir.

{: .box-note}
**DNS caching:** yani DNS önbellekleme girdiğimiz bir sitenin adresini tarayıcı ön belleğinde tutar ve tekrar istek gönderip cevap beklemek zorunda kalmaz buda bize zaman kazandırır.
