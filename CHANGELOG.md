# Change Log

Semua perubahan penting pada proyek Top-up E-Wallet Mobile Banking dicatat di file ini.
Format: [versi] - tanggal, lalu daftar Added / Changed / Fixed.

## [Unreleased]
- Rencana V0.3 (28 Nov 2026): Fitur 5 (jalur BCA Virtual Account dan komponen informasi bersama), layar Mutasi dan Pusat Bantuan, serta uji kebergunaan singkat.
- Rencana V1.0 (30 Nov 2026): perbaikan dari uji dan versi final.

## [0.2.0] - 2026-11-23
### Added
- Purwarupa interaktif berbasis HTML di `prototype/index.html` (satu file, tanpa dependensi, data simulasi) dengan 8 layar: Beranda, Pilih E-Wallet, Input Nominal, Peringatan Nominal, Konfirmasi, PIN, Top-up Gagal, Top-up Berhasil.
- Fitur 1: saldo yang bisa digunakan dan teks bantu (saldo minimal, biaya admin) di halaman Input Nominal.
- Fitur 2: validasi nominal dan peringatan sebelum PIN dengan pilihan "Gunakan nominal maksimal" atau "Ubah nominal".
- Fitur 3: layar top-up gagal dengan status dana, penyebab, nominal maksimal, tombol "Coba lagi dengan nominal maksimal", Cek Mutasi, dan Hubungi CS.
- Fitur 4: tombol "Gunakan maksimal" dan nominal rekomendasi.
- Simulasi top-up gagal setelah PIN (kotak centang, aktif secara default) untuk menjalankan alur pemulihan.
- Wireframe mid-fidelity 8 layar di folder `wireframe-8-layar/`.
- Worksheet 12: Wireframe and Prototype (mengikuti template workbook).
### Changed
- README: daftar isi repositori, cara menjalankan purwarupa, dan cakupan purwarupa diperbarui.
### Catatan
- Fitur 3 dan 4 selesai lebih awal dari jadwal (rencana V0.2 hanya Fitur 3, rencana V0.3 memuat Fitur 4).
- Belum tercakup: Fitur 5, layar Mutasi, Pusat Bantuan, dan uji kebergunaan.

## [0.1.0] - 2026-11-23
### Added
- PRD versi 0.1 (draf): Objective, Release, Features, User Flow and Design, Analytics, dst.
- Worksheet 8: pemetaan Insight, Need, Requirement (R1-R8) dan User Stories.
- Diagram alur pengguna dan wireframe 3 layar (Input Nominal, Peringatan sebelum PIN, Top-up Gagal).
