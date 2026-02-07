# 🏔️ Gemapala Next.js

Sebuah aplikasi web modern untuk Gemapala (Gema Muda Ganesha Pecinta Alam) SMAN 1 Purworejo yang dibangun menggunakan Next.js 15 dengan TypeScript, TailwindCSS, dan teknologi web terkini.

## 📋 Deskripsi Project

Project ini merupakan website resmi untuk organisasi Gemapala yang dikembangkan dengan framework Next.js. Aplikasi ini dirancang untuk memberikan pengalaman pengguna yang optimal dengan performa tinggi dan tampilan yang responsif.

## 🚀 Teknologi yang Digunakan

- **Framework:** [Next.js 15](https://nextjs.org/) - React framework untuk production
- **Language:** [TypeScript](https://www.typescriptlang.org/) - JavaScript dengan type safety
- **Styling:** [TailwindCSS](https://tailwindcss.com/) - Utility-first CSS framework
- **Font:** [Geist](https://vercel.com/font) - Font family dari Vercel
- **Package Manager:** npm/yarn/pnpm/bun

## 📁 Struktur Project

```
gemapala-nextjs/
├── public/              # Asset statis (gambar, favicon, dll)
├── src/                 # Source code utama
│   ├── app/            # App router Next.js
│   ├── components/     # Komponen React reusable
│   ├── styles/         # File styling global
│   └── utils/          # Utility functions
├── .env                # Environment variables
├── middleware.ts       # Next.js middleware
├── next.config.mjs     # Konfigurasi Next.js
├── tailwind.config.ts  # Konfigurasi TailwindCSS
└── tsconfig.json       # Konfigurasi TypeScript
```

## 🛠️ Instalasi dan Setup

### Prasyarat

Pastikan Anda sudah menginstall:
- Node.js (versi 18.x atau lebih tinggi)
- npm, yarn, pnpm, atau bun

### Langkah Instalasi

1. Clone repository ini:
```bash
git clone https://github.com/Raharinda/gemapala-nextjs.git
cd gemapala-nextjs
```

2. Install dependencies:
```bash
npm install
# atau
yarn install
# atau
pnpm install
# atau
bun install
```

3. Setup environment variables:
- Salin file `.env` dan sesuaikan konfigurasi yang diperlukan

4. Jalankan development server:
```bash
npm run dev
# atau
yarn dev
# atau
pnpm dev
# atau
bun dev
```

5. Buka [http://localhost:3000](http://localhost:3000) di browser Anda untuk melihat hasilnya.

## 📝 Script yang Tersedia

```bash
npm run dev      # Menjalankan development server
npm run build    # Build aplikasi untuk production
npm run start    # Menjalankan production server
npm run lint     # Menjalankan ESLint untuk code quality
```

## 🎨 Fitur Utama

- ⚡ **Server-Side Rendering (SSR)** - Performa optimal dengan SSR
- 🎯 **TypeScript** - Type safety untuk development yang lebih robust
- 🎨 **TailwindCSS** - Styling yang efisien dan customizable
- 📱 **Responsive Design** - Tampilan optimal di semua perangkat
- 🔄 **Hot Reload** - Auto-reload saat development
- ✅ **ESLint** - Code linting untuk kualitas kode yang konsisten

## 📚 Panduan Pengembangan

### Edit Halaman

Anda dapat mulai mengedit halaman dengan memodifikasi file di dalam folder `src/app/`. Halaman akan otomatis ter-update saat Anda menyimpan file.

### Menambahkan Komponen Baru

Tempatkan komponen React reusable di folder `src/components/` untuk memudahkan maintenance dan reusability.

### Styling

Project ini menggunakan TailwindCSS untuk styling. Anda dapat:
- Menggunakan utility classes Tailwind langsung di JSX
- Menambahkan custom styles di `tailwind.config.ts`
- Membuat global styles di folder `src/styles/`

## 📖 Sumber Belajar

Untuk mempelajari lebih lanjut tentang Next.js, kunjungi:

- [Dokumentasi Next.js](https://nextjs.org/docs) - Panduan lengkap fitur dan API Next.js
- [Learn Next.js](https://nextjs.org/learn) - Tutorial interaktif Next.js
- [Next.js GitHub Repository](https://github.com/vercel/next.js) - Repository resmi Next.js

## 🚢 Deployment

### Deploy ke Vercel (Recommended)

Cara termudah untuk deploy aplikasi Next.js adalah menggunakan [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme).

1. Push code ke GitHub repository
2. Import repository di Vercel
3. Vercel akan otomatis detect Next.js dan melakukan deployment
4. Aplikasi Anda akan live dalam beberapa menit

Lihat [dokumentasi deployment Next.js](https://nextjs.org/docs/app/building-your-application/deploying) untuk opsi deployment lainnya.

### Deploy ke Platform Lain

Next.js dapat di-deploy ke berbagai platform:
- **Netlify** - Static & SSR deployment
- **Railway** - Containerized deployment
- **Google Cloud Run** - Docker container
- **AWS** - Amplify atau EC2
- **DigitalOcean** - App Platform

## 🤝 Kontribusi

Kontribusi selalu diterima! Jika Anda ingin berkontribusi:

1. Fork repository ini
2. Buat branch baru (`git checkout -b feature/AmazingFeature`)
3. Commit perubahan Anda (`git commit -m 'Add some AmazingFeature'`)
4. Push ke branch (`git push origin feature/AmazingFeature`)
5. Buat Pull Request

## 📄 Lisensi

Project ini dibuat untuk keperluan organisasi Gemapala.

## 👤 Author

**Raharinda**
- GitHub: [@Raharinda](https://github.com/Raharinda)

## 📞 Kontak & Support

Jika Anda memiliki pertanyaan atau menemukan bug, silakan buat issue di GitHub repository.

---

⭐ **Star repository ini jika Anda merasa terbantu!**

Dibuat dengan ❤️ untuk komunitas Gemapala
