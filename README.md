# 🍴 Lezzet Atlası  | Online Sipariş & Restoran Yönetim Platformu

Lezzet Atlası, kullanıcıların hızlı ve kolay bir şekilde yemek siparişi verebildiği, ürün özelleştirmeleri yapabildiği ve siparişlerini canlı olarak takip edebildiği modern bir **ASP.NET Core Web API** ve **Vanilla JavaScript** projesidir.

Gelişmiş sepet algoritmaları, kurye bahşiş sistemi, Gel-Al indirimleri ve anlık (Flash) kampanyalar ile hem son kullanıcılara hem de restoran yöneticilerine kusursuz bir deneyim sunmayı hedefler.

---

## ✨ Öne Çıkan Özellikler

### 👤 Kullanıcı & Kimlik Doğrulama (Auth)
- **JWT (JSON Web Token) Güvenliği:** Güvenli uç noktalar, oturum ve token yönetimi.
- **Dinamik Formlar:** Tek ekranda pürüzsüz "Giriş Yap" ve "Kayıt Ol" geçişleri.
- **Profil Yönetimi:** Kullanıcıya özel adres ve telefon bilgisi saklama.

### 🍕 Ürün & Sepet Yönetimi
- **Ürün Özelleştirme:** Pişme derecesi seçimi ve ekstra malzeme (Cheddar, Jalapeno, Truffle Mantar Sos) ekleme.
- **Akıllı Çapraz Satış (Cross-Sell):** Sepete eklenen ürüne göre *"Bunun yanına iyi gider"* tavsiyeleri (Çıtır Patates, Soğan Halkası vb.).
- **Esnek Teslimat Modelleri:** - 🛵 **Adrese Teslim:** İsteğe bağlı kurye bahşişi eklentisi.
  - 🥡 **Gel-Al Fırsatı:** Sepette anında **%10 ekstra indirim** uygulaması.
- **Kampanya ve Kuponlar:** Zamanlayıcılı anlık "Hoş Geldin Fırsatları" ve kupon entegrasyonu (`LEZZET50`).
- **Minimum Sepet Tutarı:** Restoran bazlı dinamik minimum sipariş limiti kontrolü.

### 🚀 Sipariş Takibi & Yönetimi
- **Canlı Durum Takibi:** *Hazırlanıyor*, *Yolda* ve *Teslim Edildi* durumlarının CSS Flexbox/Grid destekli animasyonlu takibi.
- **Sipariş İptali ve Detay İnceleme:** Geçmiş siparişlerin detaylı fatura dökümü.
- **Admin/Restoran Paneli:** `admin` rolüne sahip kullanıcılar için tüm siparişleri tek ekrandan yönetme ve aşamaları ilerletme yetkisi.

---

## 🛠️ Kullanılan Teknolojiler

### Backend
- **Framework:** ASP.NET Core Web API (.NET 6 / 8)
- **ORM:** Entity Framework Core
- **Veritabanı:** SQLite / SQL Server
- **Güvenlik:** JWT (JSON Web Tokens), `[Authorize]` & `[AllowAnonymous]` mimarisi

### Frontend
- **HTML5 & CSS3:** Modern Flexbox/Grid mimarisi, CSS Değişkenleri (Custom Properties), duyarlı (responsive) tasarım.
- **JavaScript (ES6+):** Vanilla JS, Asenkron Programlama (`async/await`), Fetch API entegrasyonu, LocalStorage veri yönetimi.
- **İkonlar & Tipografi:** FontAwesome 6.0, Google Fonts (Poppins).

---

## 🚀 Kurulum & Çalıştırma

Projenin yerel ortamınızda (localhost) çalıştırılması için aşağıdaki adımları izleyebilirsiniz:

### 1. Backend (API) Kurulumu
1. Projeyi Visual Studio ile açın.
2. `appsettings.json` dosyasından veritabanı bağlantı dizesini (Connection String) kontrol edin.
3. Paket Yöneticisi Konsolu (Package Manager Console) üzerinden veritabanını oluşturun:
   ```bash
   Update-Database
