# DisiplinFit — Android proje dosyaları

Bu proje, ilerlemeyi telefonda kalıcı olarak saklayan basit bir Android uygulamasıdır.
Günlük görevler, tamamlanan günler, puanlar, seri, haftalık hedef ve seçilen ödül uygulamanın
yerel veritabanı yerine WebView içindeki `localStorage` alanında saklanır.

## APK oluşturma (GitHub Actions ile)
Bu çalışma ortamında Android SDK/Gradle kurulu olmadığı için burada doğrudan APK derleyemedim.
Proje, GitHub Actions ile APK üretmeye hazırdır:

1. ZIP dosyasını aç.
2. İçindeki dosyaları yeni bir GitHub deposuna yükle.
3. GitHub deposunda **Actions** sekmesine gir.
4. `Build Android APK` iş akışını çalıştır (gerekirse **Run workflow**).
5. İşlem bitince çalıştırma sayfasındaki **Artifacts** bölümünden `DisiplinFit-debug-apk` dosyasını indir.
6. ZIP'i aç, `app-debug.apk` dosyasını Android telefona gönderip kur.
   Telefonda yalnızca güvendiğin kaynaklardan APK kur; Android izin verirse bu dosya için
   “bilinmeyen uygulamaları yükle” iznini açman gerekebilir.

## Önemli
- Veriler bu telefonda ve bu uygulamanın yerel depolamasında kalır; uygulama verilerini temizlemek
  veya uygulamayı kaldırmak ilerlemeyi silebilir.
- Bu ilk sürümde hesap/senkronizasyon yoktur.
- Ön kol ağrısı devam ediyorsa ağrıya neden olan egzersizleri işaretlemek için kendini zorlama.
