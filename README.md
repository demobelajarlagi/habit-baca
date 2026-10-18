# Habit Baca

Web app untuk membangun kebiasaan membaca buku fisik lewat sesi timer pendek yang naik bertahap.

**Aplikasi live:** https://habit-baca.demo-belajarlagi.workers.dev/

## Untuk siapa

Pembaca yang punya buku fisik tapi sulit menyelesaikannya karena tergoda membuka HP. Pengguna saat ini adalah pembuatnya sendiri. Setelah pengembangan, target audiensnya adalah pembaca atau orang yang tertarik dengan buku.

## Cara mulai (3 langkah)

1. **Tambah buku.** Isi judul dan total halaman, cukup sekali per buku.
2. **Pilih buku dan goal menit**, lalu tekan **Mulai timer**.
3. **Setelah selesai**, isi end page lalu tekan **Submit**. Sesi tercatat di Riwayat.

## Fitur

- Timer mundur dan maju. Layar tetap menyala selama timer berjalan.
- Mini quest 4 level berdasarkan hari aktif:
  - Level 1: hari aktif 1-3, goal 5 menit
  - Level 2: hari aktif 4-14, goal 10 menit
  - Level 3: hari aktif 15-30, goal 15 menit
  - Level 4: hari aktif 31 dan seterusnya, goal 30 menit (bonus setelah target tercapai)
- Streak dan progress per buku.
- Hitung mundur ke ulang tahun 18 Des 2026, dengan target 30 hari aktif.
- Riwayat sesi.
- Pemulihan sesi yang terputus (misalnya halaman tertutup atau HP mati saat timer berjalan).

## Aturan

- **Hari aktif:** satu hari kalender dengan minimal satu sesi yang disubmit, berapa pun durasinya.
- **Streak:** bolos 1 hari dimaafkan. Bolos 2 hari berturut-turut mereset streak ke 0.

## Batasan

- Data tersimpan hanya di browser HP (localStorage), tanpa akun dan tanpa cadangan. Data hilang kalau data Chrome dihapus atau HP diganti.
- Notifikasi pengingat belum ada.

## Tentang proyek ini

Dibuat dengan Claude Code dan di-deploy ke Cloudflare, sebagai Final Project Mini Bootcamp Claude for Non-Tech Professional Cohort 3.
