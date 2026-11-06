# PERMATA LAB
Unit Laboratorium UPTD Puskesmas Sanga-sanga, Dinas Kesehatan Kutai Kartanegara
Dikelola oleh Andi Budiman, ATLM Puskesmas Sanga-sanga

Situs statis, dipublikasikan lewat GitHub Pages.
Letakkan semua file di folder yang sama (index.html, PKM1.jpg, LOGO_PKM_SANGASANGA.jpg, _nojekyll).

## Yang diatur admin (di index.html)
- ADMIN_EMAIL     : email admin untuk tombol "Hubungi Admin" (labpkmsangasanga@gmail.com)
- CONFIG          : nama pengelola, jabatan, dan email yang tampil di Tentang & footer
- DATA_DIPERBARUI : tanggal data laporan diperbarui admin (opsional), cari "PENGATURAN TAMBAHAN"
- PANDUAN         : isi panduan / SOP

## Dashboard Kecukupan Stok per Reagensia (menu Stok Reagensia)
- Kecukupan (bulan) = stok akhir / rata-rata pemakaian 3 bulan terakhir sampai periode terpilih.
- Kritis bila kurang dari 1 bulan, waspada 1-2 bulan, cukup 2 bulan atau lebih.
- Saran order = pemakaian 3 bulan - stok akhir (target stok 3 bulan).
- Angka ambang diatur di index.html, cari "var CUK=" (kritis, waspada, target, jendela).

## Tampilan
- Tampilan awal (setelah masuk) hanya menampilkan dashboard: Ringkasan Laporan Tahunan Lab dan Stok Reagensia.
- Klik "Mode petugas" untuk memunculkan menu link, pencarian & kategori, favorit, Dashboard Tasks, Catatan Harian, backup, dan panduan.
- Kelas CSS `staff-only` menandai elemen yang hanya tampil di Mode petugas.
