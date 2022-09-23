Rise Phone Directory
Telefon rehberi uygulaması için geliştirilmiş Backend projesi.

Başlarken
Repo'yu yerel bilgisayarınıza indirerek Visual Studio ile çalıştırabilirsiniz.

Önkoşullar
Bilgisayarınızda Docker kurulu olmalıdır.

Kurulum
Öncelikler Sertifika kurulumları için aşağıdaki komutları cmd'de çalıştırıyoruz.

```
dotnet dev-certs https -ep %USERPROFILE%\.aspnet\https\aspnetapp.pfx -p devcan123
```
```
dotnet dev-certs https --trust
```

Sonrasında src klasörü içerisinde  
```
docker-compose up -d 
```

Komutu ile docker üzerinde ayağa kaldırabiliriz.
