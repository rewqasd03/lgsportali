# Netlify Deploy Rehberi - LGS Başarı Portalı

## 🚀 Netlify'a Deploy Etmek İçin İki Seçenek

### Seçenek 1: Drag & Drop (En Kolay)
1. [Netlify Drop Sitesine](https://app.netlify.com/drop) gidin
2. Bu klasörü (netlify-deploy) doğrudan sürükleyip bırakın
3. Otomatik olarak deploy edilip URL alacaksınız

### Seçenek 2: Manuel Upload
1. [Netlify Dashboard](https://app.netlify.com/)'a giriş yapın
2. "New site from Git" veya "Deploy manually" seçeneğini seçin
3. Bu klasörü ZIP olarak upload edin
4. Deploy işlemi tamamlanana kadar bekleyin

## 📁 Dosya Yapısı
```
netlify-deploy/
├── index.html              # Ana sayfa
├── student-dashboard.html  # Öğrenci paneli  
├── logo.svg               # Site logosu
└── README.md              # Bu dosya
```

## 🔧 Özellikler

### Ana Sayfa (index.html)
- Modern, responsive tasarım
- Öğrenci giriş formu (sınıf + okul numarası)
- Firebase Firestore entegrasyonu
- Canlı istatistikler
- Site özelliklerini tanıtan bölümler

### Öğrenci Paneli (student-dashboard.html)
- Öğrenci bilgileri
- İstatistik kartları
- Gelişim grafikleri (Chart.js)
- Ders bazlı performans analizi
- Son sınav sonuçları tablosu
- Çıkış yapma özelliği

## 🔥 Firebase Konfigürasyonu
Aşağıdaki Firebase ayarları koda gömülüdür:
- Project ID: `kopruler-basari-portali`
- API Key ve diğer konfigürasyonlar

## 📊 Örnek Veriler
Test için aşağıdaki öğrenci bilgileri ile giriş yapabilirsiniz:
- **8-A / 12345**
- **8-B / 12346** 
- **8-C / 12347**

*Not: Firebase Firestore'da bu verilerin kayıtlı olması gerekir.*

## 🌐 URL Yapısı
- Ana sayfa: `/`
- Öğrenci girişi: `/` (form)
- Dashboard: `/student-dashboard.html`

## 📱 Responsive Tasarım
- Mobil uyumlu
- Tablet ve desktop desteği
- Modern gradient arka planlar
- Tailwind CSS kullanımı

## ⚡ Performans
- CDN ile yüklenen kütüphaneler
- Optimized images
- Minimal JavaScript
- Fast loading times

## 🔒 Güvenlik
- Firebase Security Rules gerektirir
- Form validasyonu
- Error handling
- Session yönetimi

## 🚨 Deployment Sonrası
1. Firebase Firestore'a test öğrenci verileri ekleyin
2. Site URLsini test edin
3. Student login flow'unu kontrol edin
4. Dashboard verilerinin doğru görüntülendiğini doğrulayın

## 📞 Destek
Herhangi bir sorun yaşarsanız:
1. Browser console'daki hataları kontrol edin
2. Firebase konfigürasyonunu doğrulayın
3. Firestore rules'larını kontrol edin
4. Network tab'ında API çağrılarını inceleyin

---
*LGS Başarı Portalı - Netlify Deployment Guide*