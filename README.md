<div align="center">

# ⚡ next-modern-utils

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js"/>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
</p>

<p align="center">
  <img src="https://img.shields.io/github/license/abdulrahmanqdev/next-modern-utils?style=flat-square&color=blue" alt="Lisans"/>
  <img src="https://img.shields.io/github/stars/abdulrahmanqdev/next-modern-utils?style=flat-square&color=yellow" alt="Yıldızlar"/>
  <img src="https://img.shields.io/github/forks/abdulrahmanqdev/next-modern-utils?style=flat-square&color=green" alt="Fork"/>
  <img src="https://img.shields.io/github/last-commit/abdulrahmanqdev/next-modern-utils?style=flat-square&color=orange" alt="Son Commit"/>
</p>

<p align="center">
  <strong>Modern Next.js uygulamaları için hazır UI modülleri.</strong><br/>
  Komut paleti + iskelet yükleyiciler — sıfır bağımlılık, üretime hazır.
</p>

</div>

---

## 📖 Genel Bakış

**next-modern-utils**, modern web uygulamaları için geliştirilmiş yeniden kullanılabilir ve erişilebilir UI bileşenleri koleksiyonudur. Klavye odaklı bir komut merkezi veya şık yükleme durumları arıyorsan, bu repo ihtiyacını karşılar — tek bir harici bağımlılık olmadan.

---

## ✨ Özellikler

### ⌨️ Komut Paleti
- `Ctrl + K` / `Cmd + K` kısayoluyla anında erişim
- Tam klavye navigasyonu (ok tuşları, `Enter`, `Escape`)
- Tüm komutlar üzerinde akıllı arama ve filtreleme
- Harici kütüphane olmadan saf React Hook'ları ile geliştirildi

### 🌙 Karanlık Mod
- Komut Paleti üzerinden tek tıkla tema değiştirme
- **Tailwind CSS v4** ve **React Context API** ile destekleniyor
- Oturumlar arasında tema tercihi korunuyor

### 💀 İskelet Yükleyici
- Yükleme durumları için özelleştirilebilir shimmer animasyonu
- Veri getirilirken pürüzsüz ve modern kullanıcı deneyimi
- Tailwind ile çalışır — kolayca genişletilebilir ve yeniden stillendirilebilir

### ⚡ Performans Odaklı
- **Sıfır harici bağımlılık**
- Hafif ve tree-shakeable yapı
- Next.js App Router için optimize edildi

---

## 🛠️ Teknoloji Yığını

| Teknoloji | Sürüm | Amaç |
|---|---|---|
| [Next.js](https://nextjs.org/) | 15+ | Framework |
| [React](https://react.dev/) | 18+ | UI Kütüphanesi |
| [Tailwind CSS](https://tailwindcss.com/) | v4 | Stillendirme |
| JavaScript | ES2022+ | Dil |

---

## 🚀 Başlarken

### Gereksinimler

Aşağıdakilerin kurulu olduğundan emin ol:
- **Node.js** `>= 18.x`
- **npm** veya **yarn** veya **pnpm**

### Kurulum

```bash
# Repoyu klonla
git clone https://github.com/abdulrahmanqdev/next-modern-utils.git

# Proje dizinine geç
cd next-modern-utils

# Bağımlılıkları yükle
npm install
```

### Geliştirme Modu

```bash
npm run dev
```

Tarayıcında [http://localhost:3000](http://localhost:3000) adresini aç.

### Üretim Derlemesi

```bash
npm run build
npm start
```

---

## 📁 Proje Yapısı

```
next-modern-utils/
├── public/               # Statik dosyalar
├── src/
│   └── app/              # Next.js App Router sayfaları ve bileşenleri
├── tailwind.config.js    # Tailwind yapılandırması
├── next.config.mjs       # Next.js yapılandırması
├── jsconfig.json         # JS yol takma adları
└── README.md
```

---

## 🎮 Kullanım

### Komut Paleti

Uygulamanın herhangi bir yerinde `Ctrl + K` (Mac'te `Cmd + K`) tuşlarına bas. Ok tuşlarıyla gezin, `Enter` ile komutu çalıştır, `Escape` ile kapat.

### İskelet Yükleyici

İskelet yükleyici, veri çeken bileşenlerde otomatik olarak devreye girer ve içerik yüklenirken pürüzsüz bir shimmer efekti sunar.

---

## 🤝 Katkıda Bulunma

Katkılar memnuniyetle karşılanır! Şu adımları takip edebilirsin:

1. Repoyu fork'la
2. Yeni bir özellik dalı oluştur (`git checkout -b ozellik/harika-ozellik`)
3. Değişikliklerini kaydet (`git commit -m 'Harika özellik eklendi'`)
4. Dalı push'la (`git push origin ozellik/harika-ozellik`)
5. Pull Request aç

---

## 📄 Lisans

Bu proje açık kaynaklıdır ve [MIT Lisansı](LICENSE) kapsamında sunulmaktadır.

---

## 👤 Geliştirici

**@abdulrahmanqdev**
