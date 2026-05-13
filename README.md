# 🍴 Lezzet Atlası | Online Sipariş & Restoran Yönetim Platformu

Lezzet Atlası; kullanıcıların hızlı yemek siparişi verebildiği, adminlerin ise tüm operasyonu anlık yönetebildiği **ASP.NET Core Web API** ve **Vanilla JavaScript** tabanlı tam kapsamlı bir platformdur.

---

## 📸 Uygulama Arayüzü & Operasyonel Kanıtlar

Aşağıdaki görseller, sistemin tüm modüllerinin asenkron API mimarisi ile nasıl çalıştığını adım adım göstermektedir.

### 👤 1. Kullanıcı Giriş ve Kayıt Paneli
Sistem, JWT tabanlı güvenli oturum yönetimi kullanmaktadır.

![Giriş Ekranı](giris_ekrani.png)

<br/>

![Kayıt Ekranı](kayit_olma%20ekrani.png)

<br/>

### 🏠 2. Ana Sayfa ve Restoran Keşfi
Kullanıcıların restoranları listeleyebildiği ve arama yapabildiği ana ekran.

![Ana Sayfa](ana_sayfa_ekrani.png)

<br/>

![Restoran Arama](restoran_arama.png)

<br/>

### 🍕 3. Menü ve Ürün Detayları
Kategori bazlı menüler ve ürün özelleştirme (malzeme seçimi) ekranları.

![Pizza Menüsü](pizza_menüsü.png)

<br/>

![Ürün Detay ve Özelleştirme](urun_detay.png)

<br/>

### 🛒 4. Gelişmiş Sepet ve İndirim Yönetimi
Gel-Al indirimleri, kuponlar ve flash kampanyaların uygulandığı sepet modülü.

![Flash İndirim Kampanyası](flash_indirim_ekrani.png)

<br/>

![Kupon ve Kampanya Girişi](kupon_ekrani.png)

<br/>

![Sepet Özeti ve İndirimler](kuponlu_gel_al_sepet_özeti.png)

<br/>

### 🛵 5. Canlı Sipariş Takibi ve Fatura
Siparişin mutfaktan teslimata kadar olan süreci ve final fatura dökümü.

![Canlı Sipariş Takibi](siparis_takibi.png)

<br/>

![Sipariş İptal Durumu](siparis_iptal.png)

<br/>

![Dijital Fatura Detayı](siparis_özeti.png)

<br/>

### ⚙️ 6. Yönetim (Admin) Panelleri
Siparişlerin onaylandığı ve restoran/menü ayarlarının yapıldığı yetkili panelleri.

![Admin Sipariş Yönetimi](admin_siparis_yonetimi.png)

<br/>

![Restoran ve Menü Yönetimi](restoran_yonetimi.png)

---

## 🛠️ Teknik Yetkinlikler

- **Backend:** ASP.NET Core Web API (.NET 8), Entity Framework Core, JWT Auth.
- **Frontend:** Vanilla JavaScript (ES6+), Modern CSS (Flexbox/Grid), Fetch API.
- **Veritabanı:** SQLite / SQL Server.

---

> **Geliştirici:** Poyraz Kesgin  
> **Durum:** Tüm modüller entegre edildi ve başarıyla test edildi.
