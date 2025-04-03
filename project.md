# Ege Meet – Proje Tanımı

Bu proje, Ege Üniversitesi özelinde etkinlik oluşturma ve paylaşım platformu olmayı amaçlamaktadır. Amaç; Ege üniversitesi bünyesinde gerçekleştirilen etkinliklerin organizasyonunu ve paylaşımını kolaylaştırmak, etkinlik sahiplerini ve katılımcıları tek bir platformda buluşturarak etkileşimi artırmaktır.

---

## 🎯 Proje Hedefleri

- Ege Üniversitesi öğrencilerinin etkinlikleri takip edebileceği bir platform oluşturmak
- Üniversite bünyesinde etkinlik düzenlemek isteyen yetkili biri için etkileşimin olduğu bir platform ortaya koymak
- Tasarıma sadık kalarak kullanıcı deneyimi yüksek bir ürün çıkarmak
- Açık kaynaklı **gerçek hayat** projesi geliştirmek

---

## 🧩 Proje Özeti

- Kullanıcı onboarding & giriş/kayıt
- Etnkinlik listeleme ve filtreleme
- Etkinlik detay sayfası
- Topluluk Oluşturma
- Etkinlik oluşturma (Sadece topluluk sahibi)
- Ödeme akışı (Bir sonraki geliştirmede eklenebilir)
- Profil yönetimi

## ⏱️ Süre ve İş Gücü Tahmini

Bu proje uçtan uca tamamlanmak istendiğinde, tasarımdan yayına kadar birçok süreci içerir:

### Dahil Olan Adımlar

- Tasarım analiz ve bileşen planlama
- Mimari belirleme
- Mobil uygulama & Admin panel kurulumu, mimari yapı, sayfa geliştirmeleri
- Backend kurulumu (Supabase), API endpoint geliştirmeleri
- Ortam değişkenleri, localizasyon, auth sistemi
- Test altyapısı (unit/widget/postman/firebase emulator)
- CI/CD pipeline kurulumu
- Dokümantasyon ve deploy

---

### 🔄 Geliştirme Akışı

1. ⚙ Sistem tasarımı & Mimari belirleme
2. 🎯 Tasarım inceleme & bileşen çıkarımı  
3. 📱 Mobil / Admin sayfa & navigasyon yapısı  
4. 💻 Backend (auth, db)  
5. 🧪 Test ve validasyon  
6. 📦 Paketleme & pipeline kurulumu  
7. 📖 Dokümantasyon & teslim

---

## 🔧 Genel Yapılacaklar (Framework bağımsız)

- [ ] Genel sistem tasarımının oluşturulması
- [ ] Mimarinin belirlenmesi
- [ ] Verilerin moddellenmesi
- [ ] Tasarım ekranlarının analizi
- [ ] Navigasyon akışı ve ekran sıralaması
- [ ] Sayfa arayüzlerinin kodlanması
- [ ] Filtreleme ve sıralama mantığının kurulması
- [ ] Profil yönetimi
- [ ] Backend API uç noktaları ve testler
- [ ] Dokümantasyonların hazırlanması

---

## ⏱️ Önerilen Takvim

Bu proje tahmini 3 ay ( 90 gün ) içinde tamamlanabilir şekilde planlanmıştır.  

| Aşama                      | Süre     |
|---------------------------|----------|
| Genel sistem tasarımının oluşturulması & mimarinin belirlenmesi           | 2 gün    |
| Verilerin moddellenmesi                                                   | 14 gün   |
| Tasarım analizi                                                           | 7 gün    |
| Sayfa yapılarının çıkarılması                                             | 7 gün    |
| UI geliştirme                                                             | 20 gün   |
| Backend model & API                                                       | 15 gün   |
| Entegrasyon & test                                                        | 15 gün   |
| Son düzenleme                                                             | 7 gün    |

---

## 🔗 Figma Tasarımı

UI Kit ( 📱 Mobil ): **Event Booking App- EventHub (Community)**  
Figma Link: [Figma UI Kit](https://www.figma.com/design/OlwXrrLgiJR5UqcwDOgdAN/Event-Booking-App--EventHub-(Community)?node-id=704-4802&p=f&t=sIJVLgjV1qpPNjMB-0)

UI Kit ( 💻 Admin Panel ): **Horizon UI Free**  
Github Link: [Horizon Tailwind & React & Typescript Template](https://github.com/horizon-ui/horizon-tailwind-react-ts)
