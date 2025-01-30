# HepsiApi - Onion Architecture & CQRS

Bu proje, **Onion Architecture** ve **CQRS** mimarileri kullanılarak geliştirilmiş, ölçeklenebilir ve sürdürülebilir bir **ASP.NET Core Web API** uygulamasıdır.

## 📌 Kullanılan Teknolojiler
- **ASP.NET Core** - Web API geliştirme
- **CQRS (Command and Query Responsibility Segregation)** - Veri yönetimi
- **Onion Architecture** - Modüler ve sürdürülebilir yapı
- **Entity Framework Core** - ORM ve veritabanı yönetimi
- **SQL Server** - Veritabanı yönetimi
- **MediatR** - Katmanlar arası iletişim
- **Swagger** - API dokümantasyonu

## 🏗 Mimari Yapı
- **Core** 📂 - İş mantığını ve domain modellerini içerir.
- **Infrastructure** 📂 - Veritabanı erişimi ve repository yapısını içerir.
- **Presentation** 📂 - API servisleri ve uygulamanın dışa açılan yüzü.

## 🚀 Kurulum ve Çalıştırma

1. **Depoyu Klonlayın:**
   ```bash
   git clone <repository-url>
   cd HepsiApi-OnionCQRS
   ```

2. **Bağımlılıkları Yükleyin:**
   ```bash
   dotnet restore
   ```

3. **Veritabanı Migrasyonlarını Çalıştırın:**
   ```bash
   dotnet ef database update
   ```

4. **Uygulamayı Başlatın:**
   ```bash
   dotnet run
   ```

5. **Swagger Üzerinden API'yi Test Edin:**
   - Tarayıcınızda `http://localhost:5000/swagger/index.html` adresini açın.

## 📜 Lisans
Bu proje açık kaynaklıdır ve katkı sağlamaya açıktır.

---
Herhangi bir geri bildiriminiz veya katkıda bulunmak isterseniz bizimle iletişime geçebilirsiniz! 🚀

