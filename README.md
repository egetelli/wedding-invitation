# Kübra & Ege Düğün Web Sitesi

Bu proje, **Kübra & Ege** düğünü için hazırlanmış interaktif bir davetiye ve RSVP web sitesidir.  

## Özellikler

1. **Yükleme Ekranı**  
   - Açılışta animasyonlu loader ve isimler gösterilir.

2. **Arka Plan Müziği**  
   - Otomatik döngü ile çalacak bir müzik alanı (`music2.mp3`).

3. **Hero Bölümü**  
   - Çift isimleri, aileler, tarih ve davet mesajı.
   - "Katılımını Onayla" butonu ile RSVP bölümüne kaydırma.

4. **Geri Sayım Bölümü**  
   - Büyük güne kalan süreyi gün, saat, dakika ve saniye olarak gösterir.
   - Google Calendar bağlantısı ile etkinliği takvime ekleme.

5. **Hikayemiz / Carousel**  
   - Düğün hikayesi ve fotoğraf galerisi (carousel).

6. **Lokasyon Bölümü**  
   - Mekan bilgisi ve Google Maps bağlantısı.

7. **Düğün Akışı**  
   - Etkinlik saatleri ve detayları (karşılama, nikah, yemek, eğlence, pasta).

8. **Anı Paylaşım Bölümü**  
   - Google Drive üzerinden fotoğraf ve video yükleme.

9. **RSVP (Katılım Onayı) & Dilek Defteri**  
   - İsim, katılım durumu, kişi sayısı, misafir isimleri ve not bırakma alanı.
   - Dinamik misafir inputları kişi sayısına göre açılır.
   - Gönderim sonrası teşekkür mesajı ve formu resetleme seçeneği.
   - Google Forms ile veri gönderimi.

10. **Sabit Butonlar**  
    - WhatsApp ile davetiye paylaşma.
    - Dark Mode toggle.
    - Arka plan müziğini aç/kapat toggle.

## Kullanım

- `index.html` dosyasını tarayıcıda açarak görüntüleyebilirsiniz.  
- Müzik dosyasını (`music2.mp3`) ve görselleri `images/` klasöründe bulundurmanız gerekir.  
- RSVP formu gönderimleri Google Forms üzerinden alınır.  

## Gereksinimler

- Modern bir web tarayıcısı (Chrome, Edge, Firefox vb.).  
- İnternet bağlantısı (Google Forms ve Google Drive bağlantıları için).  

## Notlar

- Form gönderimi `fetch` ve `no-cors` ile Google Forms’a yapılmaktadır.  
- Misafir inputları sadece kişi sayısı seçildikten sonra açılır.  
- Resetleme butonu formu temizler ve misafir inputlarını kapatır. 
