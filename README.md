# Kap Loglama ve Log İzleme Sistemi

Kap API tabanlı basit loglama sistemidir. Kendinize özel olarak uygulamalar oluşturup bu uygulamalarda oluşan hataları takip edebilirsiniz.

## Planlanan Özellikler

Planlanan özellikler aşağıdaki gibidir. Gidişata göre değişim gösterebilirler.

 - Kullanıcıların Giriş Yapabileceği Web Arayüzü
 - Kullanıcıların Uygulama Ekleyebilmesi
 - Uygulamalar İçin Özel Anahtarlar Oluşturma
 - Tarih Aralığına Göre Hata Filtreleme
 - Hatalara Dair Varsa Linkler
 - Mümkünse Hata Türlerine Göre Filtreleme
 - Loglanan Hataların Aktiflik durumu
 - Genel Log Türleri
 - Yeni Log Kategorileri Ekleme
 - Loglanmış Verinin Kategorisini Değiştirme.


## Uygulama Kaynağı

Projenin klasör yapısı aşağıdaki bağlantılar örnek alınarak oluşturulmuştur

[https://www.digitalocean.com/community/tutorials/how-to-structure-large-flask-applications](https://www.digitalocean.com/community/tutorials/how-to-structure-large-flask-applications)

[https://damyanon.net/post/flask-series-environment/](https://damyanon.net/post/flask-series-environment/)

[https://www.restapitutorial.com/lessons/httpmethods.html](https://www.restapitutorial.com/lessons/httpmethods.html)

## Durum

**03.03.2019**:

    - Models değiştirildi
    - Database oluşturuldu
    - Database seeder oluşturuldu
    - Configler oluşturuldu.
    - Modellerden mixinler kaldırıldı
    - Controller için databaseden veri çekme ve ekleme işlemleri gerçekleştirildi
    - user endpoint'i users olarak değiştirildi.

**27.02.2019**:
    
    - User Model Oluşturuldu

**26.02.2019**:

    - Klasör Yapısının Oluşturulmasına Başlandı
    - Cors Tüm Domainler İçin Aktif Kılındı