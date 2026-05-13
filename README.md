# 🍴 Lezzet Atlası | Online Sipariş & Restoran Yönetim Platformu

Lezzet Atlası, kullanıcıların hızlı ve kolay bir şekilde yemek siparişi verebildiği, ürün özelleştirmeleri yapabildiği ve siparişlerini canlı olarak takip edebildiği modern bir **ASP.NET Core Web API** ve **Vanilla JavaScript** projesidir.

Gelişmiş sepet algoritmaları, kurye bahşiş sistemi, Gel-Al indirimleri ve anlık (Flash) kampanyalar ile hem son kullanıcılara hem de restoran yöneticilerine kusursuz bir deneyim sunmayı hedefler.

---

## 📸 Uygulama Arayüzü & Operasyonel Kanıtlar (UI/UX)

Sistemin tüm modülleri asenkron API mimarisi ile uçtan uca test edilmiş ve aşağıdaki ekran görüntüleriyle kayıt altına alınmıştır:

### 👤 1. Kullanıcı & Oturum Yönetimi
- **Giriş ve Kayıt Paneli:** ![Giriş](giris_ekrani.png) | ![Kayıt](kayit_olma%20ekrani.png)
- **Kullanıcı Profil Ekranı:** ![Profil](profil_ekrani.png)

### 🍕 2. Ürün Keşfi & Dinamik Menüler
- **Ana Sayfa & Restoran Arama:** ![Ana Sayfa](ara_sayfa_ekrani.png) | ![Arama](restoran_arama.png)
- **Kategori Menüleri:** ![Pizza](pizza_menüsü.png) | ![Burger](hamburger_menüsü.png) | ![Döner](dönerci_menüsü.png) | ![Sosisli](sosisli_menüsü.png)
- **Ürün Özelleştirme (Pişme Derecesi & Malzeme Seçimi):** ![Ürün Detay](urun_detay.png)

### 🛒 3. Gelişmiş Sepet & İndirim Motoru
- **Zamanlayıcılı Flash İndirim Kampanyaları:** ![Flash İndirim](flash_indirim_ekrani.png)
- **Kupon ve Kampanya Ekranı:** ![Kupon](kupon_ekrani.png)
- **Sepet Özeti (Normal):** ![Sepet Normal](sepet_özeti.png)
- **Kupon ve Gel-Al Entegrasyonlu Sepetler:** ![Kuponlu Sepet](kuponlu_gel_al_sepet_özeti.png) | ![Gel-Al Sepet](gel_al_sepet_özeti.png)
- **Sepet Çakışma Kontrolü (Farklı Restoran Doğrulaması):** ![Sepet Temizleme Uyarısı](restoran_yonetimi.png)

### 🚀 4. Canlı Sipariş Takibi & Fatura
- **Sipariş Durumu:** ![Takip](siparis_takibi.png) | **Sipariş İptali:** ![İptal](siparis_iptal.png)
- **Detaylı Dijital Fatura:** ![Sipariş Özeti](siparis_özeti.png)

### ⚙️ 5. Admin / Restoran Yönetim Paneli
- **Sipariş Aşamaları Yönetimi:** ![Admin Sipariş](admin_siparis_yonetimi.png)
- **Restoran ve Menü Kontrolü:** ![Restoran Yönetimi](restoran_yonetimi.png)

---

## ✨ Öne Çıkan Özellikler

### 🔒 Kimlik Doğrulama (Auth)
- **JWT Güvenliği:** Güvenli uç noktalar, oturum ve token yönetimi.
- **Dinamik Formlar:** Tek ekranda pürüzsüz geçişler ve LocalStorage tabanlı oturum kontrolü.

### 🧠 Akıllı Sepet Algoritmaları
- **Çapraz Satış (Cross-Sell):** Sepete eklenen ürüne göre *"Bunun yanına iyi gider"* tavsiyeleri.
- **Esnek Teslimat:** Adrese teslimde bahşiş entegrasyonu, Gel-Al siparişlerinde anında **%10 ekstra indirim**.

---

## 🛠️ Kullanılan Teknolojiler

### Backend
- **Framework:** ASP.NET Core Web API (.NET 6 / 8)
- **ORM & DB:** Entity Framework Core, SQLite / SQL Server
- **Güvenlik:** JWT (JSON Web Tokens), Role-based Authorization (`admin` & `user`)

### Frontend
- **Tasarım:** Modern Flexbox/Grid mimarisi, CSS Değişkenleri, Tam Duyarlı (Responsive) Tasarım.
- **Mantık Katmanı:** Vanilla JavaScript (ES6+), Asenkron Fetch API, DOM Manipülasyonu.

---

## 🚀 Kurulum & Çalıştırma

### 1. Backend (API) Kurulumu
1. Projeyi Visual Studio ile açın.
2. Paket Yöneticisi Konsolu üzerinden veritabanını oluşturun:
   ```bash
   Update-Database
