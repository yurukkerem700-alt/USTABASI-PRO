# USTABAŞI Ekosistemi

Türkiye'nin en büyük ustalık ve hizmet ekosistemi. Bu proje Vite, React, TailwindCSS ve Supabase kullanılarak geliştirilmiştir.

## Özellikler
- **Rol Bazlı Sistem:** Müşteri, Usta ve Firma panelleri.
- **Gerçek Zamanlı İletişim:** Supabase Realtime ile anlık mesajlaşma.
- **Güvenli Ödeme:** Escrow mantığı ile çalışan cüzdan sistemi.
- **Yapay Zeka:** Fiyat tahmini ve akıllı eşleştirme sunan AI asistanı.
- **Ustagram:** Ustaların projelerini dikey video formatında sergilediği sosyal medya.
- **Topluluk:** Sesli odalar ve metin kanalları barındıran Discord benzeri yapı.
- **Çoklu Dil:** Türkçe ve İngilizce i18n desteği.
- **Karanlık Mod:** Göz yormayan Dark/Light mode altyapısı.

## Kurulum
1. Bağımlılıkları yükleyin:
   ```bash
   npm install
   ```
2. `.env.example` dosyasını kopyalayarak `.env` oluşturun ve Supabase bilgilerinizi girin.
3. Geliştirme sunucusunu başlatın:
   ```bash
   npm run dev
   ```

## Deployment
Vercel üzerine doğrudan deploy edilebilir. Build komutu:
```bash
npm run build
```