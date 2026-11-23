# Rekayasa Interaksi (UX) - Top-up E-Wallet Mobile Banking

Proyek mata kuliah Rekayasa Interaksi (UX) oleh Firman Maulana Bhagaskara (202310370311355).

Fitur: top-up e-wallet dari rekening bank di aplikasi mobile banking. Fokus: menampilkan saldo yang bisa digunakan, memperingatkan pengguna sebelum PIN, dan memberi kepastian status dana saat top-up gagal. Persona: Farrel Abimanyu, mahasiswa 19-22 tahun.

> Semua data pada purwarupa adalah simulasi (tanpa integrasi bank). Angka saldo minimal, biaya admin, dan biaya otomatis hanya contoh; aturan sebenarnya ditetapkan bank.

## Isi repositori
| Berkas / folder | Keterangan |
| --- | --- |
| `202310370311355_Firman_Maulana_Bhagaskara_PRD_TopUp_EWallet.docx` | Product Requirement Document (versi 0.1) |
| `202310370311355_Firman_Maulana_Bhagaskara_Worksheet12_WireframePrototype.docx` | Worksheet 12: Wireframe and Prototype |
| `user-flow-topup.png` | Diagram alur pengguna |
| `wireframe-topup.png` | Wireframe awal 3 layar (Input Nominal, Peringatan sebelum PIN, Top-up Gagal) |
| `wireframe-8-layar/` | Wireframe mid-fidelity 8 layar (`screen-1.png` sampai `screen-8.png`) untuk Worksheet 12 |
| `prototype/index.html` | Purwarupa interaktif 8 layar (satu file HTML, tanpa dependensi) |
| `CHANGELOG.md` | Catatan perubahan antarversi |

## Menjalankan purwarupa
1. Unduh atau clone repositori ini.
2. Buka `prototype/index.html` di browser (klik dua kali), atau di VS Code gunakan ekstensi Live Server (klik kanan, "Open with Live Server").
3. Alur utama: Beranda, Pilih E-Wallet, Input Nominal, Peringatan Nominal, Konfirmasi, PIN, Top-up Gagal, Coba Lagi, Berhasil.

Cara mencoba:
- Ketik `1215000` di kolom nominal lalu tekan Lanjut untuk melihat peringatan sebelum PIN.
- Tekan "Gunakan maksimal" lalu lanjut sampai PIN. Dengan kotak centang simulasi aktif (default), top-up gagal satu kali bila nominal di atas Rp1.150.000, lalu "Coba lagi dengan nominal maksimal" menuju layar berhasil.
- Tombol di luar alur (Mutasi, Bantuan, Cek Mutasi, Hubungi CS) hanya menampilkan pesan singkat.

Bila GitHub Pages diaktifkan (Settings, Pages, branch `main`, folder `/root`), purwarupa dapat dibuka lewat `https://firman2244.github.io/RekayasaInteraksi/prototype/`.

## Cakupan purwarupa saat ini
Tercakup: saldo yang bisa digunakan dan teks bantu (Fitur 1), peringatan sebelum PIN (Fitur 2), layar top-up gagal (Fitur 3), tombol "Gunakan maksimal" dan nominal rekomendasi (Fitur 4).
Belum tercakup: jalur BCA Virtual Account dan komponen informasi bersama (Fitur 5), layar Mutasi, dan Pusat Bantuan. Uji kebergunaan belum dilakukan.

## Jadwal versi
| Versi | Tanggal rencana | Isi | Status |
| --- | --- | --- | --- |
| V0.1 | 24 Nov 2026 | PRD draf, Fitur 1 dan 2 | Selesai (23 Nov) |
| V0.2 | 26 Nov 2026 | Fitur 3 (layar top-up gagal) | Selesai (23 Nov), termasuk purwarupa HTML dan Fitur 4 |
| V0.3 | 28 Nov 2026 | Fitur 4 dan 5, uji kebergunaan singkat | Tersisa: Fitur 5 dan uji kebergunaan |
| V1.0 | 30 Nov 2026 | Perbaikan dan versi final | Belum dimulai |

Rincian perubahan ada di [CHANGELOG.md](CHANGELOG.md).
