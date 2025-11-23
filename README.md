# To-Do-App
# OOP Tabanlı To-Do Uygulaması

Bu proje, Flask ve Flask-SQLAlchemy kullanılarak geliştirilmiş, OOP mimarisine dayalı bir **Görev Yönetim Uygulamasıdır**.  
Görevler başlık, açıklama, durum ve deadline bilgileriyle kaydedilir, düzenlenir ve filtrelenebilir.

## Özellikler

### 1. OOP Tabanlı Görev Sınıfı
Projede `Gorev` adında bir sınıf bulunur ve şu özellikleri içerir:

- Başlık  
- Açıklama  
- Durum (Beklemede / Tamamlandı)  
- Son Tarih (Deadline)

### 2. CRUD İşlemleri
Kullanıcılar web arayüzünden:

- Görev ekleyebilir  
- Görevleri listeleyebilir  
- Durumu güncelleyebilir  
- Görev silebilir  

### 3. Flask-SQLAlchemy ile Kalıcı Veri Kaydı
Görevler `SQLite` veritabanına kaydedilir. ORM yapısı sayesinde ekleme–silme–güncelleme işlemleri kolaylaştırılmıştır.

### 4. Deadline Uyarı Sistemi
Görev kartlarının  tarafında renkli  şerit bulunur:

| Renk | Anlamı |

| 🔴 Kırmızı | Deadline geçmiş |
| 🟠 Turuncu | Deadline 0–3 gün içinde |
| 🟢 Yeşil | Deadline ileri bir tarihte |
| ⚪ Gri | Görev tamamlandı |

### 5. Göreve Göre Filtreleme
Kullanıcı görevleri:

- Beklemede
- Tamamlandı
- Yaklaşan Deadline
- Geçmiş Deadline

şeklinde filtreleyebilir.

### 6. Modern Frontend Tasarımı
- Kart tasarımı  
- Renk kodlaması  
- Deadline legend (renk açıklama kutusu)   
- Şık butonlar
## Proje çalıştırma
zip dosyasından çıkarın
Proje başlat düğmesine basınca tarayıcıda  http://127.0.0.1:5000 bu sayfa aratılır ve uygulama açılır.Eğer proje çalışmazsa alttaki kurulması gerekenler kurulur.
## Projede kurulması gereken 
pyhton kurulur ardından altaki kod terminalde çalıştırılır
    python -m venv venv
    venv\Scripts\activate
gerekli paket  yüklenir
     pip install flask flask_sqlalchemy
alttaki kod çalıştırmak için projeyi çalıştırılır     
  python app.py
tarayıcıda bu açın
  http://127.0.0.1:5000



## Proje Yapısı

