# 💌 Kübra & Ege Düğün Web Sitesi

Bu proje, **Kübra & Ege** düğünü için hazırlanmış interaktif davetiye ve RSVP web sitesidir.  
Renkli, animasyonlu ve kullanıcı dostu tasarımı ile misafirlerinizi etkileyecek bir deneyim sunar.  

---

## 🎨 Özellikler

### 🖼️ Yükleme Ekranı
- Açılışta animasyonlu loader ve çift isimleri.
- Kusursuz bir başlangıç için tüm içerik yüklenene kadar ekranı kaplar.

### 🎵 Arka Plan Müziği
- Döngüsel çalan müzik (`music2.mp3`) ile siteye canlılık katar.
- Müzik aç/kapat butonu ile kontrol edilebilir.

### 👰🤵 Hero Bölümü
- Çift isimleri ve aileler gösterilir.
- Davet mesajı ve "Katılımını Onayla" butonu ile RSVP bölümüne kaydırma.

### ⏳ Geri Sayım
- Büyük güne kalan süreyi gösterir (Gün / Saat / Dakika / Saniye).
- Google Calendar bağlantısı ile etkinliği takvime ekleme.

### 📸 Hikayemiz / Carousel
- Düğün hikayesi ve fotoğraf galerisi.
- Fotoğraflar tıklanabilir ve büyütülebilir.

### 📍 Lokasyon
- Düğün mekânı bilgisi ve harita bağlantısı (Google Maps).

### 🗓️ Düğün Akışı
- Etkinlik saatleri ve detayları:  
  🥂 Karşılama | 💍 Nikah | 🍽️ Yemek | 🎵 Eğlence & Müzik | 🍰 Pasta Kesimi

### 📷 Anı Paylaşımı
- Google Drive üzerinden fotoğraf ve video yükleme imkânı.
- Misafirleriniz anılarını paylaşabilir.

### ✉️ RSVP (Katılım Onayı) & Dilek Defteri
- Ad, soyad, katılım durumu, kişi sayısı, misafir isimleri ve not bırakma alanı.
- Dinamik misafir inputları, kişi sayısına göre açılır.
- Gönderim sonrası teşekkür mesajı gösterilir.
- Form verileri Google Forms ile alınır.
- Yanıtı güncellemek için resetleme butonu mevcut.

### 🔘 Sabit Butonlar
- 📱 WhatsApp ile davetiye paylaşımı.
- 🌙 Dark Mode toggle.
- 🔇 Arka plan müziği aç/kapat toggle.

---

## 🛠️ Kullanım

1. `index.html` dosyasını tarayıcıda açın.  
2. `music2.mp3` ve tüm görsellerin `images/` klasöründe olduğundan emin olun.  
3. RSVP formu gönderimleri Google Forms üzerinden alınır.  
4. Misafir inputları sadece kişi sayısı seçildikten sonra açılır.  
5. Resetleme butonu formu temizler ve misafir inputlarını kapatır.

---

## ⚡ Gereksinimler

- Modern web tarayıcısı (Chrome, Edge, Firefox vb.)  
- İnternet bağlantısı (Google Forms ve Google Drive için)

---

## 💡 Notlar

- Form gönderimi `fetch` ve `no-cors` ile yapılır.  
- Site tamamen responsive ve mobil uyumludur.  
- Animasyonlar CSS ile sağlanır, kullanıcı deneyimi odaklıdır.

---

💖 Hazırlayan: Kübra & Ege | 5 Temmuz 2026  
