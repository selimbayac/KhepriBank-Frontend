# KhepriBank Frontend

KhepriBank müşteri destek uygulamasının **React** tabanlı modern frontend arayüzü.

Bu proje, backend tarafındaki AI destekli şikayet yönetim sistemine (KhepriBank Backend) bağlı olarak çalışan kullanıcı arayüzünü içermektedir.

## ✨ Özellikler

- Modern ve temiz kullanıcı arayüzü (Tailwind CSS)
- React + Vite ile hızlı geliştirme ortamı
- Responsif (mobil uyumlu) tasarım
- Backend API entegrasyonu (RESTful API calls)
- Şikayet oluşturma, listeleme ve detay görüntüleme
- Yapay zeka analiz sonuçlarını (UrgencyScore, SuggestedAction, CustomerResponse) gösterme arayüzü

## 🛠️ Kullanılan Teknolojiler

- **React 18**
- **Vite** (Build Tool)
- **Tailwind CSS**
- **JavaScript / JSX**
- Axios (veya Fetch) ile API Entegrasyonu
- ESLint + PostCSS

## 🚀 Nasıl Çalıştırılır?

1. Projeyi klonlayın:
   ```bash
   git clone https://github.com/selimbayac/KhepriBank-Frontend.git
   cd KhepriBank-Frontend/KhepriBankFront
   ```
   2.Bağımlılıkları yükleyin:npm install
   3.Geliştirme sunucusunu başlatın:npm run dev
   4. Tarayıcıda http://localhost:5173 adresine gidin.

Backend API ile bağlantı kurmak için .env dosyasında API base URL'sini ayarlayın.

Proje Yapısı
KhepriBankFront/
├── public/
├── src/
│   ├── assets/
│   ├── components/     # Reusable bileşenler
│   ├── pages/          # Ana sayfalar (Login, Dashboard, Complaint vb.)
│   ├── services/       # API servisleri
│   ├── utils/
│   └── App.jsx
├── index.html
├── tailwind.config.js
├── vite.config.js
└── package.json

Bağlantılı Projeler
Backend API: KhepriBank Backend (.NET 8 + AI) https://github.com/selimbayac/banka-destek-api


Hedef
Bu frontend projesi, banka müşteri şikayetlerinin yapay zeka ile analiz edildiği modern bir müşteri destek paneli oluşturmayı amaçlamaktadır.

