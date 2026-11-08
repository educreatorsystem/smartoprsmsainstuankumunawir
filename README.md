# SMART OPR GENERATOR — SM Sains Tuanku Munawir

Fail ZIP ini boleh diekstrak dan **semua kandungan folder** dimuat naik terus ke akar repositori GitHub Pages.

- Sheet ID: `1Sw9QqXshY8M3JihmF15MvyXJb672haBUNH6DtfRQw1w`
- Apps Script: `https://script.google.com/macros/s/AKfycbzQrKFcsVn3VZ5IVoQDLgmYvlfhxiXWLvHvyhIuebTh2Maiy2sKOydqRmVuRw8Y-3Li/exec`
- Folder Drive: `1YxKLNj_HSTRT5qkkBG4YXfqzem-P8ppZ`
- Logo/PWA: `https://iili.io/nDxdzdX.md.png`

## Pemasangan

1. Muat naik `index.html`, `Code.gs`, `manifest.webmanifest`, `sw.js`, `.nojekyll`, `smart-opr-header.png`, dan `README.md` ke akar repositori.
2. Dalam Google Apps Script, gunakan kandungan `Code.gs` jika perlu mengemas kini backend, kemudian deploy versi baharu.
3. Semak kebenaran Google Sheet dan folder Google Drive untuk akaun yang menjalankan Apps Script.
4. Semak paparan sekolah dan cuba simpan satu rekod ujian sebelum menggunakan sistem sebenar.

**Perhatian:** Logo dan ikon PWA ialah URL JPG luar kerana fail imej asal tidak tersedia secara lokal. Sesetengah peranti mungkin memerlukan ikon PNG lokal 192/512px untuk pemasangan PWA. Muat naik fail logo asal untuk menghasilkan ikon PWA setempat yang lebih stabil.

Sambungan sebenar Google Sheet / Drive tidak dapat disahkan melalui ujian terus dalam persekitaran ini.


## Pilihan templat OPR
Templat asal + Corporate Blue, Emerald Gold, Modern Minimalist, Sporty Dynamic. Klik Lihat Laporan > pratonton > pilih templat. Cetakan A4 mengikut templat dipilih. Semua fungsi simpan, edit, paparan laporan, gambar dan Google Sheet asal dikekalkan. Pilihan templat disimpan pada peranti, tidak mengubah struktur Google Sheet.

## Perhatian ikon PWA
Lencana dimasukkan melalui URL luaran https://iili.io/nDxdzdX.md.png. Untuk pemasangan PWA yang konsisten pada semua peranti dan luar talian, simpan versi PNG tempatan 192x192 dan 512x512 dalam repositori serta kemas kini manifest.

## Pembaikan cetak A4 (8 November 2026)
Kandungan templat baharu ditetapkan kepada 210 × 297 mm termasuk padding dan sempadan (box-sizing: border-box), mengelakkan bahagian kanan terpotong. Lebar gambar dihadkan pada petak sendiri. Fungsi asal dan backend tidak diubah.
