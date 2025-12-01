OgrenciKayitSistemi.sln
21430070029/Dorukhan Perdeci

⚡ Kullanılan Araçlar ve Mimariler
Teknoloji / Mimari	Görevi
🧱 ASP.NET Core MVC	Sunum katmanı
🧩 Entity Framework Core	Veritabanı işlemleri
🧬 Layered Architecture	Modüler ve yönetilebilir yapı
🧲 SOLID	Esnek ve sürdürülebilir kod
🧰 Dependency Injection	Bağımlılıkların IoC ile yönetimi
🚀 Projenin Sağladığı Fonksiyonlar

🎓 Öğrenci ekleme, düzenleme ve listeleme özellikleri

🧑‍🏫 Öğretmen bilgilerinin yönetimi

📚 Cinsiyet, Sınıf, Branş gibi enum yapıları ile seçenek yönetimi

🔗 Servis, repository ve manager katmanlarıyla ayrık görev yapısı

🎨 Razor View tabanlı kullanışlı kullanıcı arayüzü

🧱 Mimarinin Güçlü Yönleri

✔️ Veriyi işleyen, yöneten ve sunan katmanlar birbirinden tamamen ayrıdır
✔️ EF Core ile kod taraflı veri yönetimi
✔️ IoC ile gevşek bağlı sınıflar
✔️ Temiz ve genişlemeye açık yapı

├── 🧠 Business
│   ├── Abstract
│   ├── Concrete
│   └── DependencyResolvers
│
├── 🔧 Core
│   ├── DataAccess
│   ├── Entities
│   └── Core.csproj
│
├── 🗄️ DataAccess
│   ├── Abstract
│   ├── Concrete (EF)
│   └── Migrations
│
├── 📁 Entities
│   ├── DTOs
│   ├── Enums
│   └── Models
│
└── 🌍 Presentation (Web UI)
    ├── Controllers
    ├── Views
    ├── wwwroot
    └── Settings
