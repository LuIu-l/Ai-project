# 🚀 Quick Start Guide - AI Chatbot

## Cara Menjalankan

```bash
# Masuk ke folder project
cd "C:\project web AI\AI project"

# Install dependencies (jika belum)
npm install

# Jalankan development server
npm run dev
```

Server akan berjalan di: **http://localhost:8080** (atau port lain jika sedang digunakan)

---

## 🎯 Akses Fitur Chatbot

### URL Routes

| URL | View | Deskripsi |
|-----|------|-----------|
| `/chat` | Chat | Percakapan utama dengan AI |
| `/chat/history` | History | Riwayat percakapan |
| `/chat/profile` | Profile | Profil pengguna |
| `/chat/settings` | Settings | Pengaturan chatbot |

### Cara Login
1. Buka **http://localhost:8080/auth/login**
2. Login dengan akun yang sudah ada atau signup dulu
3. Setelah login, akan redirect ke `/chat`

---

## 🎮 Cara Menggunakan

### 1. **Mengirim Pesan**
- Ketik pesan di input box
- Tekan **Enter** atau klik tombol **Send** (✉️)

### 2. **Menggunakan Voice Input** 🎤
- Klik tombol **Mic** di sebelah kiri input
- Browser akan meminta permission
- Recording akan otomatis berhenti setelah 3 detik
- Text "[Audio terekam]" akan ditambahkan ke input

### 3. **Menggunakan Camera** 📷
- Klik tombol **Camera** di sebelah kiri input
- Browser akan meminta permission
- Preview kamera akan muncul di atas input
- Klik X di preview untuk menutup

### 4. **Mengganti Mode AI** ⚡
- Klik dropdown di kanan atas (Fast/Balance/Deep)
- Pilih mode yang diinginkan:
  - **Fast**: Respon cepat untuk pertanyaan sederhana
  - **Balance**: Keseimbangan kualitas dan kecepatan
  - **Deep Learning**: Analisis mendalam untuk topik kompleks

### 5. **Membuat Chat Baru**
- Buka **History** dari sidebar
- Klik tombol **"Chat Baru"** atau **"+"**
- Chat baru akan dibuat dan siap digunakan

### 6. **Melihat History**
- Buka **History** dari sidebar
- Klik salah satu chat untuk membuka
- Klik icon **Trash** untuk menghapus

### 7. **Edit Profil**
- Buka **Profile** dari sidebar
- Edit nama dan email
- Klik **"Simpan Perubahan"**

### 8. **Pengaturan**
- Buka **Settings** dari sidebar
- Pilih mode default AI
- Atur konfigurasi project
- Atau clear all data

---

## 🎨 UI Elements

### Sidebar (Kiri)
```
┌─────────────────────┐
│  AI Chat Indonesia  │
├─────────────────────┤
│  💬 Chat            │
│  📜 Riwayat         │
│  👤 Profil          │
│  ⚙️ Pengaturan      │
├─────────────────────┤
│  [User Avatar]      │
│  User Name          │
│  user@email.com     │
│  🚪 Keluar          │
└─────────────────────┘
```

### Chat Area (Tengah)
```
┌─────────────────────────────────┐
│  Asisten AI Indonesia  [Mode ▼] │
├─────────────────────────────────┤
│                                 │
│  [Pesan User]          →        │
│           ←  [Pesan AI]         │
│                                 │
├─────────────────────────────────┤
│  [Camera Preview (optional)]    │
├─────────────────────────────────┤
│  🎤 📷 [Input Message...]    ✉️ │
└─────────────────────────────────┘
```

---

## 🎯 Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Enter` | Kirim pesan |
| `Shift + Enter` | New line di input |
| `Esc` | Tutup sidebar (mobile) |

---

## 📱 Responsive Behavior

### Desktop (>1024px)
- Sidebar selalu visible
- Full layout
- Optimal untuk multitasking

### Tablet (768-1024px)
- Sidebar collapsible
- Hamburger menu
- Touch-friendly

### Mobile (<768px)
- Sidebar sebagai overlay
- Auto-close setelah navigasi
- Optimized untuk satu tangan

---

## 🔧 Troubleshooting

### Issue: Mic/Camera tidak berfungsi
**Solusi**: 
1. Pastikan browser support WebRTC
2. Allow permission saat browser meminta
3. Check browser settings untuk microphone/camera access

### Issue: Pesan tidak terkirim
**Solusi**:
1. Pastikan input tidak kosong
2. Check console browser untuk error
3. Periksa koneksi internet

### Issue: Sidebar tidak muncul di mobile
**Solusi**:
1. Klik tombol hamburger (☰) di kiri atas
2. Refresh halaman jika stuck

---

## 🔐 Authentication

Chatbot terintegrasi dengan sistem autentikasi:

- **Login Required**: Harus login untuk akses chatbot
- **Auto Redirect**: Belum login → redirect ke `/auth/login`
- **Logout**: Klik "Keluar" di sidebar bawah

---

## 🌐 Browser Support

| Browser | Version | Status |
|---------|---------|--------|
| Chrome | 90+ | ✅ Fully supported |
| Firefox | 88+ | ✅ Fully supported |
| Safari | 14+ | ✅ Fully supported |
| Edge | 90+ | ✅ Fully supported |
| Opera | 76+ | ✅ Fully supported |

---

## 📞 Need Help?

- 📖 Baca **CHATBOT_README.md** untuk dokumentasi lengkap
- 📊 Lihat **CHATBOT_SUMMARY.md** untuk overview perubahan
- 🐛 Check browser console untuk error messages

---

## 🎉 Tips & Tricks

### Tip 1: Gunakan Mode yang Tepat
- Simple questions → **Fast Mode**
- General chat → **Balance Mode**
- Complex analysis → **Deep Learning Mode**

### Tip 2: Organize Your Chats
- Buat chat baru untuk topik berbeda
- Beri judul yang descriptive
- Hapus chat yang tidak diperlukan

### Tip 3: Voice Input Efficient
- Prepare pertanyaan sebelum klik mic
- Speak clearly untuk hasil terbaik
- Combine dengan text untuk editing

### Tip 4: Camera Preview
- Gunakan untuk visual context
- Screenshot dari kamera bisa dianalisis (future feature)
- Tutup kamera jika tidak digunakan untuk save bandwidth

---

**Happy Chatting! 🚀**

---

Last Updated: November 24, 2025
