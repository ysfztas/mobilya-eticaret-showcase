# Mobilya E-Ticaret

**Mobilya mağazası için e-ticaret sitesi ve yönetim paneli.**

> Kaynak kod private. Bu depo projenin tanıtım sayfasıdır. İstek üzerine demo yapılabilir.

## Özellikler

**Mağaza**
- Kategori ve ürün listeleme; varyantlı ürünler
- Fiyatı girilmemiş ürünlerde WhatsApp'tan fiyat sorma
- Misafir ve üye sepeti; oturum süresi dolunca misafir sepetine sorunsuz geçiş
- Havale/EFT ile ödeme, sipariş takibi, siparişlerim sayfası
- Ürün yorumları, üyelik ve e-posta doğrulama
- KVKK, mesafeli satış sözleşmesi, iade ve teslimat sayfaları; çerez onayı; SEO

**Yönetim paneli**
- İki adımlı doğrulamalı (2FA) admin girişi
- Ürün, kategori, sipariş, kullanıcı, yorum ve duyuru yönetimi

**Güvenlik ve altyapı**
- JWT, bcrypt, Helmet, rate limiting, girdi doğrulama, NoSQL injection koruması
- Stok güncellemelerinde MongoDB transaction ile yarış durumu koruması
- Winston ile loglama, e-posta bildirimleri

## Teknolojiler

Node.js · Express · MongoDB / Mongoose · JWT · bcrypt · Helmet · express-rate-limit · express-validator · Nodemailer · Winston · HTML/CSS/JavaScript
