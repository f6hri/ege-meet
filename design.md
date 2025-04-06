# 🎨 Tasarım Rehberi – Ege Meet

Bu doküman, UI Kit'in nasıl kullanılacağı, tasarımı nasıl doğru okuyup yazılıma aktaracağınız ve Figma üzerindeki önemli kuralları içerir.

## 🔗 Figma Tasarımı

- **Figma URL:**
  [Event Booking App- EventHub (Community)](https://www.figma.com/design/OlwXrrLgiJR5UqcwDOgdAN/Event-Booking-App--EventHub-(Community)?t=6C5NfTu7tUsuPfjV-0)

---

## 🖌️ Design System'deki Yapılar

### 🎨 Renk Paleti

- **Primary:** #5669FF (Blue **Main**)
  - #7887FF (Blue 1)
  - #9AA5FF (Blue 2)
  - #BBC3FF (Blue 3)
  - #DDE1FF (Blue 4)
  - #EEF0FF (Blue 5)
- **Secondary:** #00F8FF (Cyan **Main**)
  - #33F9FF (Cyan 1)
  - #66FBFF (Cyan 2)
  - #99FCFF (Cyan 3)
  - #CCFEFF (Cyan 4)
  - #E6FEFF (Cyan 5)
- **Accent:**
  - #F0635A (Red)
  - #39B54A (Green)
  - #F0635A (Orange)
  - #46CDBF (Dark Cyan)
  - #8C3EF1 (Purple)
  - #FDC400 (Yellow)
- **Typography:**  #120D26 (Black **Main**)
  - #29253C (Black 1)
  - #888693 (Gray 1)
  - #B8B6BE (Gray 2)
  - #D0CFD4 (Gray 3)
  - #E7E7E9 (Gray 4)
- **Backgorund:**
  - #2D2D3A (Black 1)
  - #393948 (Black 2)
  - #E5E5E5 (Gray)

---

### 🔡 Tipografi Sistemi

**Tipografi:** Airbnb Cereal App

- Header 1: **Bold** | **50px** | **72** | **0**
- Header 2: **Book** | **35px** | **Auto** | **0**
- Header 3: **Book** | **30px** | **Auto** | **0**
- Header 4: **Medium** | **24px** | **Auto** | **0**
- Header 5: **Medium** | **22px** | **Auto** | **0**
- Title 1: **Medium** | **18px** | **Auto** | **0**
- Title 2: **Medium** | **16px** | **Auto** | **0**
- BUTTON: **Medium** | **16px** | **25** | **1**
- Body 1: **Book** | **16px** | **25** | **0**
- Body 2: **Book** | **15px** | **Auto** | **0**
- Body 3: **Book** | **14px** | **24** | **0**
- Sub Title 1: **Book** | **13px** | **Auto** | **0**
- Sub Title 2: **Book** | **12px** | **Auto** | **0**

---

### 🧿 Icon

- **Kategorilere ayrılmış:** Money, Media, UI, Crypto, Navigation vs.
- **Tavsiye edilen format:** `SVG` (vector olarak ölçeklenebilir)

---

### 🔲 Button & Input

- 4 tip buton: düz, ikonlu, sadece ikon, disabled
- Yazı boyutları, padding ve corner-radius değerleriyle birlikte tanımlanmış

####

---

## 🧠 Tasarımı Kodlarken Dikkat Etmen Gerekenler

✅ **Pixel-perfect takıntısına gerek yok** – önemli olan uyumlu görünüm
✅ Auto layout → padding/margin değerlerini öğrenmek için
✅ Font büyüklüğü ve ağırlığı → responsive stil sistemi kurarken belirleyici
✅ Komponentlerin tek tek değil, gruplar halinde yazılması (design-to-code disiplini)
✅ Renk, ikon, yazı stilleri `constants.dart` veya `theme.ts` gibi tek merkezden tanımlanmalı
✅ Görseller `2x`, `3x` gibi retina destekli boyutlarla eklenmeli

---

## 🔨 Geliştirici Notları

- Her bileşen için “reusable” düşün: `HotelCard`, `RatingStars`, `FilterTag` gibi
- Layout kurarken spacing değerlerine dikkat et (Figma'daki spacing’ler önemli!)
- SVG ikonları component gibi çağır → PNG kullanma
- UI ekranları test edilirken tasarımla görsel karşılaştırma yapılmalı
