# Teknik Komputer Unsoed 2026

Website profil statis untuk komunitas **Teknik Komputer Universitas Jenderal Soedirman Angkatan 2026**. Website dibuat sebagai mini project dengan HTML, CSS, dan JavaScript murni.

## Fitur

- Empat section utama: Home/Hero, About/Profile, Main Content, dan Contact/Footer.
- Desain modern dengan nuansa teknologi, gradien, elemen dekoratif, dan animasi.
- Responsif untuk desktop, tablet, dan ponsel.
- Navigasi antar-section dan menu mobile.
- Animasi reveal ketika konten masuk ke area layar.
- Tidak menggunakan backend, database, autentikasi, atau fitur CRUD.

## Struktur file

```text
teknik-komputer-unsoed-2026/
├── index.html
├── style.css
├── script.js
└── README.md
```

## Menjalankan secara lokal

1. Unduh atau clone repository.
2. Buka folder proyek.
3. Buka `index.html` di browser.

Opsional: gunakan ekstensi **Live Server** di Visual Studio Code untuk menjalankan website melalui server lokal.

## Cara upload ke GitHub

### Opsi A: lewat website GitHub

1. Masuk ke [GitHub](https://github.com/) dan buat repository baru, misalnya `teknik-komputer-unsoed-2026`.
2. Pilih visibilitas repository sesuai kebutuhan.
3. Klik **Add file → Upload files**.
4. Unggah `index.html`, `style.css`, `script.js`, dan `README.md` (pastikan keempat file berada di root repository).
5. Tulis pesan commit, misalnya `Add static organization website`, lalu klik **Commit changes**.

### Opsi B: lewat Git di terminal

Jalankan perintah berikut dari folder proyek. Ganti `USERNAME` dengan username GitHub kamu.

```bash
git init
git add index.html style.css script.js README.md
git commit -m "Add static organization website"
git branch -M main
git remote add origin https://github.com/USERNAME/teknik-komputer-unsoed-2026.git
git push -u origin main
```

Jika repository lokal sudah terhubung ke remote, tidak perlu mengulang `git remote add origin`.

## Mengaktifkan GitHub Pages

1. Buka repository di GitHub.
2. Masuk ke **Settings → Pages**.
3. Pada bagian build/deployment, pilih **Deploy from a branch**.
4. Pilih branch `main` dan folder `/ (root)`, lalu simpan.
5. Tunggu proses publikasi selesai. URL website akan ditampilkan pada halaman Pages.

## Hal yang perlu disesuaikan sebelum publikasi

- Periksa kembali nama resmi organisasi dan detail profil angkatan.
- Ganti tautan Instagram dengan akun resmi jika sudah tersedia.
- Ganti alamat `hello@example.com` pada `index.html` dengan email kontak yang benar.
- Tinjau ulang uraian visi, misi, dan program agar sesuai kesepakatan angkatan. Program pada website ini merupakan contoh konsep, bukan klaim kegiatan resmi.

## Teknologi

- HTML5
- CSS3
- JavaScript (vanilla)

Google Fonts digunakan untuk tipografi; jika koneksi internet tidak tersedia, website tetap dapat digunakan dengan font cadangan.
