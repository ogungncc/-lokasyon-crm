# Lokasyon CRM — iPhone PWA Kurulum Rehberi

## Adım 1: GitHub Hesabı Aç
1. https://github.com adresine git
2. "Sign up" ile ücretsiz hesap oluştur

## Adım 2: Yeni Repository Oluştur
1. Sağ üstte "+" → "New repository"
2. Repository name: `lokasyon-crm`
3. **Public** seç (GitHub Pages için gerekli)
4. "Create repository" tıkla

## Adım 3: Dosyaları Yükle
1. "uploading an existing file" linkine tıkla
2. Bu klasördeki 5 dosyayı sürükle bırak:
   - index.html
   - manifest.json
   - sw.js
   - icon-192.png
   - icon-512.png
3. "Commit changes" tıkla

## Adım 4: GitHub Pages Aktif Et
1. Repository'de "Settings" → "Pages"
2. Source: "Deploy from a branch"
3. Branch: "main" → "/ (root)" → Save
4. 1-2 dakika bekle
5. Adresin: **https://KULLANICI_ADIN.github.io/lokasyon-crm**

## Adım 5: iPhone'a Uygulama Olarak Ekle
1. Safari'de yukarıdaki adresi aç
2. Alt ortadaki paylaş butonuna bas (kare + ok)
3. "Ana Ekrana Ekle" seç
4. "Ekle" tıkla
5. ✅ Artık ana ekranda uygulama gibi açılır!

## Veri Güvenliği
- Tüm veriler iPhone'unuzda saklanır (iCloud Safari sync ile yedeklenir)
- Hiçbir veri dışarı gönderilmez
- İnternet olmadan da çalışır (offline mode)
