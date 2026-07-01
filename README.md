# Tarif Sistemi

Yemek tariflerini yönetmek için geliştirilmiş Java Swing masaüstü uygulaması. Kullanıcı eldeki malzemelere göre hangi tariflerin yapılabileceğini görebilir.

Kocaeli Üniversitesi — Yazılım Laboratuvarı I, 1. Proje.

## Özellikler

- Tarif ekleme, düzenleme, silme ve arama
- Malzeme ekleme, düzenleme, silme ve arama
- Tarif önerisi: mevcut malzemelere göre yapılabilecek tariflerin yüzdesel gösterimi
- Sütuna göre sıralama (id, hazırlama süresi, maliyet)
- MySQL veritabanı entegrasyonu

## Teknolojiler

- **Java Swing** — masaüstü arayüzü
- **MySQL** — veritabanı
- **JDBC** — veritabanı bağlantısı
- **Apache NetBeans** — geliştirme ortamı

## Kurulum

1. MySQL kurulu olduğundan emin ol
2. `jdbcdemo` adında bir veritabanı oluştur (uygulama `localhost:3306/jdbcdemo` adresine bağlanır)
3. Tüm `.java` kaynak dosyalarındaki `YOUR_PASSWORD` değerini kendi MySQL şifrenle değiştir
4. Projeyi NetBeans ile aç ve çalıştır
