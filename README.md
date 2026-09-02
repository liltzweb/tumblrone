# 🌐 internetknows // a private archive

> **Website Digital Gift & Private Search Engine for Couples**  
> *Harga Template / Jasa:* **Rp 10.000**

`internetknows` adalah template website perayaan hubungan (mensive, anniversary, birthday) dengan konsep **mesin pencari privat (private search engine)** yang estetik, modern, dan bebas dari klise AI (*anti-slop*). 

Website ini membimbing pasanganmu melalui pengalaman interaktif 6 tahap: mulai dari mencari tahu *"what is today?"*, menemukan arsip foto berdua dengan pop-out lightbox, pengakuan manis, membaca surat cinta personal, hingga halaman penutup editorial yang hangat.

---

## ✨ Alur Interaktif 6 Tahap (User Journey)

1. **Page 01 — Private Search (`#search`)**  
   Header ultra-minimalis dengan search bar interaktif. Pasangan mengetik query pencarian dengan efek suara ketikan prosedural.
2. **Page 02 — Search Results (`#results`)**  
   Kartu hasil temuan privat bertanggal: *"apparently, something important happened today."* Menuntun user untuk menekan tombol **view result**.
3. **Page 03 — Image Archive & Pop-Out Lightbox (`#images`)**  
   Galeri editorial diptych yang menampilkan **1 Foto Pasangan (Keith)** dan **1 Foto Pengirim (Keisha)**. Setiap foto dapat di-klik untuk **pop-out (zoom membesar)** dalam lightbox modal berlatar *dark blur*.
4. **Page 04 — The Answer / Monograph (`#answer`)**  
   Monograf puitis dengan tipografi estetik yang mengungkap rahasia hari ini (*"and because today is our 3rd mensive."*) dengan aksen pink highlight.
5. **Page 05 — Private Love Letter (`#letter`)**  
   Surat cinta digital bertajuk `PRIVATE_MESSAGE.txt` dengan sapaan, multi-paragraf yang tulus, dan tanda tangan personal.
6. **Page 06 — Colophon & Ending (`#final`)**  
   Tampilan penutup editorial dengan pesan milestone (*"and i'm still choosing you."*), opsi membaca ulang surat, dan kembali ke pencarian awal.

---

## 🎨 Tipografi & Palet Warna Aktif

* **Display / Headlines**: `Bricolage Grotesque` (Ink-traps tebal & modern)
* **Body / Reading**: `Outfit` (Geometris bersih)
* **Romantic Accents**: `Instrument Serif` (Editorial italic)
* **Metadata & Tags**: `Space Mono` (Monospace tech)

### 🩶 Palet Warna Utama: Charcoal + Soft Gray + Pink (Dark Romantic)
* **Background (Canvas)**: `#191919`
* **Surface / Cards**: `#222222`
* **Primary Text**: `#F1F1F1`
* **Secondary Text**: `#969696`
* **Border & Dividers**: `#303030`
* **Romantic Accent**: `#E38A9B` (hover: `#EB9DB0`)

---

## 📸 Panduan Memasang 2 Foto

Letakkan 2 file foto kamu di folder `assets/` dengan nama dan spesifikasi berikut:

| Foto | Lokasi & Nama File | Format Rekomendasi | Keterangan |
| :--- | :--- | :--- | :--- |
| **Foto 1 (Pasangan)** | `assets/photo-01.jpg` | 4:5 Portrait (800×1000 px atau 1080×1350 px) | Foto Keith / Pasangan kamu (`01 KEITH`) |
| **Foto 2 (Kamu)** | `assets/photo-02.jpg` | 4:5 Portrait (800×1000 px atau 1080×1350 px) | Foto Keisha / Diri kamu (`02 KEISHA`) |

> **Tips:** Gunakan format file `.jpg` atau `.jpeg` dengan ukuran di bawah 1 MB agar proses loading website instan dan mulus.

---

## 📝 Cara Kustomisasi Konten

Semua data teks, tanggal, nama pasangan, dan isi surat cinta disimpan dalam satu file konfigurasi:
👉 **[`js/config.js`](js/config.js)**

Kamu cukup mengubah data di dalam objek `siteData`:

```javascript
const siteData = {
  // Identitas Pasangan
  senderName: "Keisha Harper",
  senderFirstName: "Keisha",
  recipientName: "Keith Harrison",
  recipientFirstName: "Keith",
  occasion: "3rd Mensive",
  dateFormatted: "September 1, 2026",
  dateShort: "09.01.2026",

  // Surat Cinta (Bebas tambah/kurang paragraf)
  letter: {
    greeting: "dear keith,",
    paragraphs: [
      "paragraf 1 kamu...",
      "paragraf 2 kamu...",
      "paragraf 3 kamu..."
    ],
    closing: "happy 3 months, keith.\ni'm really glad it's still us.",
    signature: "— keisha"
  }
};
```

---

## 📋 Formulir Pemesanan (`form.html`)

Website ini dilengkapi dengan formulir pemesanan khusus: **[`form.html`](form.html)**.

Fitur formulir:
1. **Input Lengkap 8 Bagian**: Identitas pasangan, pencarian, caption 2 foto, kalimat pengakuan, surat cinta multi-paragraf, dan pilihan palet warna.
2. **Kirim Pesanan via WhatsApp**: Otomatis membuat format pesanan terstruktur dan membuka chat WhatsApp penjual/admin.
3. **Salin Format (Copy to Clipboard)**: Salin seluruh teks pesanan dalam 1 klik.
4. **Download `config.js`**: Otomatis menghasilkan file `config.js` yang langsung siap dipakai tanpa perlu mengetik kode manual!

---

## 🚀 Cara Menjalankan & Deploy Website

### 1. Menjalankan di Komputer / Laptop Sendiri (Lokal)
Cukup klik ganda file `index.html` untuk membuka langsung di Google Chrome / browser apa pun, atau jalankan local server:
```bash
# Menggunakan Python
python -m http.server 3000

# Atau menggunakan Node.js
npx serve .
```

### 2. Deploy Online Gratis
Karena website ini 100% static (HTML, CSS, JS murni tanpa database backend), kamu bisa mengunggahnya secara gratis ke:
* **Vercel** (`vercel deploy`)
* **Netlify Drop** (Cukup drag-and-drop seluruh folder proyek ke browser)
* **GitHub Pages** (Push repository dan aktifkan Pages di tab Settings)
* **Cloudflare Pages**

---

## 📂 Struktur File Proyek

```
INTERNETKNOWS/
├── index.html           # File utama website digital gift
├── form.html            # Formulir pemesanan & generator config (Rp 10.000)
├── README.md            # Dokumentasi lengkap proyek
├── assets/
│   ├── favicon.svg      # Favicon web
│   ├── photo-01.jpg     # Foto Keith (Pasangan)
│   └── photo-02.jpg     # Foto Keisha (Pengirim)
├── css/
│   └── style.css        # Stylesheet Charcoal + Pink & Responsive Layout
└── js/
    ├── config.js        # Konfigurasi data teks, nama, surat & tanggal
    ├── sound.js         # Sound engine prosedural (Web Audio API)
    └── app.js           # State machine, navigation routing & lightbox logic
```

---

## 🏷️ Lisensi & Hak Cipta
Dibuat dengan penuh cinta untuk merayakan momen berharga bersama pasangan. Template ini dijual dengan harga terjangkau **Rp 10.000**.
