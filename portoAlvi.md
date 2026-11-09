# 🚀 Panduan & Cetak Biru Web Portofolio Alvynf

Dokumen ini berisi cetak biru lengkap untuk pembangunan web portofolio pribadi. Dirancang secara jujur, relevan dengan latar belakang **Teknik Jaringan (TKJ)** serta studi **Informatika (UTDI)** saat ini.

---

## 📌 1. Konsep & Identitas Utamav

* **Nama / Identitas:** Alvynf
* **Fokus Utama:** Software Development & Network/Systems Specialist
* **Target Desain:** Simple, Dinamis, Modern (Dark Mode)
* **Repositori Utama:** [github.com/alvynf](https://github.com/alvynf)

---

## 🎨 2. Palet Warna (Dark Slate & Deep Teal)

Palet warna gelap yang nyaman di mata (*eye-friendly*), mengurangi silau, dan memberikan kesan teknologis seperti *code editor* modern.

| Elemen UI | Nama Warna | Kode Hex | Fungsi & Efek Visual |
| :--- | :--- | :--- | :--- |
| **Background Utama** | Deep Charcoal / Slate | `#0F172A` | Dasar latar belakang utama seluruh halaman |
| **Surface / Card BG** | Dark Navy Slate | `#1E293B` | Latar belakang kartu proyek, skill, & sertifikat |
| **Teks Utama** | Off-White / Soft Blue | `#E2E8F0` | Kontras teks tinggi yang tidak menyilaukan |
| **Teks Sekunder** | Muted Slate | `#94A3B8` | Subtitle, tanggal, & keterangan pendukung |
| **Aksen Utama** | Cyan / Emerald | `#38BDF8` | Warna tombol CTA, link, & efek aktif |
| **Aksen Sekunder** | Soft Purple / Violet | `#818CF8` | Warna tag skill & variasi efek hover |
| **Garis Pembatas** | Dark Border | `#334155` | Garis batas tipis untuk pemisah antar elemen |

---

## 🗺️ 3. Struktur Halaman Web (Section Breakdown)

```text
[ Hero Banner ]
  ├── Tagline & Perkenalan Singkat
  └── Tombol CTA (Lihat Proyek, GitHub, LinkedIn)
       │
[ Tentang Saya (About Me) ]
  ├── Perjalanan dari SMK TKJ ke S1 Informatika
  └── Fokus Pengalaman (Fiber Optic, Networking, Pemrograman Java)
       │
[ Keahlian & Peralatan (Skills & Tools) ]
  ├── Jaringan & Sistem  : Subnetting/VLSM, FO Splicing, Topologi
  ├── Pemrograman        : Java (Dasar & Logika Algoritma)
  └── Tools              : Git/GitHub (Basic), VS Code, Terminal
       │
[ Proyek & Studi Kasus (Projects) ]
  ├── CLI IP Subnet Calculator (Java)
  ├── Perencanaan Topologi Jaringan (Dokumentasi PKL)
  └── Web Portofolio Responsive (HTML/CSS/JS)
       │
[ Sertifikasi & Pencapaian (Certificates) ]
  ├── Juara 3 LKS IT Network System Administration (2025 - Kab. Klaten)
  ├── Sertifikat Intern Technician (PT. Searas Citra Terabit)
  └── Galeri Kartu Preview Sertifikat
       │
[ Pengalaman & Soft Skills ]
  ├── Ketua Sekbid Kewirausahaan OSIS (2 Periode)
  └── Sekretaris Dewan Ambalan Pramuka
       │
[ Kontak & Footer ]
  └── Link Email, LinkedIn, GitHub, & Hak Cipta
```

---

## 💻 4. Rincian Isi Setiap Section

### 1. Hero Section
* **Title:** Halo, Saya Alvy 👋
* **Tagline:** Informatika Student | Network Specialist & Java Developer
* **Deskripsi:** Berfokus pada arsitektur jaringan yang efisien dan pengembangan perangkat lunak berbasis logika yang kuat.

### 2. About Me Section
* **Latar Belakang Teknis:** Memiliki pondasi kuat dari SMK jurusan TKJ, berpengalaman praktis dalam penarikan & penyambungan *fiber optic*, serta perencanaan topologi jaringan kantor saat magang di PT. Searas Citra Terabit.
* **Akademik:** Saat ini menempuh pendidikan S1 Informatika di UTDI untuk memperdalam ilmu *software engineering* dan logika algoritma.

### 3. Projects Showcase
1. **CLI IP Subnet Calculator (Java)**
   * *Deskripsi:* Aplikasi berbasis baris perintah (*command-line*) untuk menghitung pembagian *subnet* IP (CIDR/VLSM) secara otomatis.
   * *Tech Stack:* Java (JDK)
2. **Dokumentasi Topologi Jaringan PT. Searas Citra Terabit**
   * *Deskripsi:* Perencanaan topologi dan dokumentasi konfigurasi jaringan fisik & statistik koneksi *fiber optic*.
   * *Tech Stack:* Cisco Packet Tracer / Visio, Fiber Optic Tools
3. **Web Portofolio Pribadi**
   * *Deskripsi:* Web portofolio interaktif dan responsif berbasis warna gelap modern.
   * *Tech Stack:* HTML5, CSS3, JavaScript

### 4. Galeri Sertifikat (Certificate Cards)
* **Komponen:**
  * Gambar *thumbnail* sertifikat
  * Judul Sertifikat
  * Penerbit & Tahun
  * Tombol *Preview/Modal*

---

## 📱 5. Panduan Tampilan Antar Device (Responsive UI/UX)

| Elemen | Desktop (> 1024px) | Mobile (< 768px) |
| :--- | :--- | :--- |
| **Navigasi** | Links horizontal di navbar atas | Hamburger menu dropdown |
| **Kartu Proyek** | Grid 3 kolom menyamping | 1 Kolom menyusun ke bawah |
| **Sertifikat** | Grid 2-3 kolom dengan efek hover zoom | Scroll vertikal / slider horizontal |
| **Ukuran Tombol** | Standar (padding `12px 24px`) | *Touch-friendly* (tinggi min 48px) |

---

## 📝 6. Catatan Pengembangan & Roadmap

- [ ] Membuat struktur dasar `index.html`
- [ ] Menyusun variabel warna pada file `style.css`
- [ ] Mengatur layout responsive menggunakan CSS Grid/Flexbox
- [ ] Menambahkan efek *hover* dinamis pada kartu proyek & sertifikat
- [ ] Upload gambar sertifikat ke folder `/assets/images`
- [ ] Deploy website ke GitHub Pages atau Vercel
