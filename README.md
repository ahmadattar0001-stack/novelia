# NOVELIA

NOVELIA adalah prototipe platform baca dan tulis novel yang responsif untuk HP dan desktop.

## Cara menjalankan
Buka `index.html` di browser. Untuk menerbitkan ke internet, unggah file ini ke repository GitHub dan aktifkan GitHub Pages.

## Fitur prototipe
- Beranda, katalog, pencarian, filter genre
- Detail novel, sinopsis, daftar bab
- Reader dengan pengaturan ukuran teks
- Writer Studio untuk membuat/mengedit/menghapus novel
- Upload sampul dari galeri perangkat
- Penyimpanan lokal browser (`localStorage`)

## Batasan penting
Versi ini belum memiliki akun, database online, sinkronisasi antarperangkat, atau upload publik. Data novel tersimpan hanya pada browser/perangkat yang digunakan. GitHub Pages hanya meng-host file statis; agar banyak penulis dan pembaca dapat berbagi karya secara nyata, langkah berikutnya adalah menghubungkan backend seperti Supabase (Auth + Database + Storage) atau Firebase.

## Deploy GitHub Pages
1. Buat repository publik bernama `novelia`.
2. Upload `index.html` dan `README.md` ke root repository.
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main`, folder `/ (root)`, lalu **Save**.
6. Tunggu proses deployment. URL biasanya `https://USERNAME.github.io/novelia/`.

Jangan mengunggah password, token, atau kunci rahasia ke repository publik.
