# RuangK3 PPLG

Website course K3 yang berfokus pada kebutuhan siswa PPLG: ergonomi komputer, keselamatan listrik dan kabel, kesehatan mata, keadaan darurat, lingkungan lab, dan kebiasaan kerja sehat.

## Menjalankan
1. Ekstrak ZIP.
2. Buka `index.html` di browser modern.
3. Untuk workflow development, jalankan server lokal dari folder ini, misalnya `python -m http.server 8000`, lalu buka `http://localhost:8000`.

## Fitur demo
- Landing/dashboard dan katalog materi dengan pencarian.
- Enam modul K3, masing-masing punya halaman sendiri (alamat `#/materi/<nama>`) dengan daftar isi, poin kunci, dan navigasi modul sebelumnya/berikutnya.
- Tandai materi selesai dan simpan progres di localStorage.
- Checklist keselamatan sebelum praktik.
- Kuis 15 soal yang tiap soalnya terhubung ke satu bagian materi: mode semua modul atau latihan per modul, umpan balik langsung, skor per modul, pembahasan, dan tautan ke bagian materi terkait.
- Layout responsif untuk HP (320px+), tablet, laptop, hingga layar lebar: menu samping menjadi drawer di ≤900px (tutup via overlay/Esc), TOC modul menempel di atas saat scroll, target sentuh ≥44px, dan mendukung notch/safe-area.

## Catatan
Ini adalah prototype frontend tanpa backend/login sungguhan. Progres disimpan di browser perangkat yang sedang digunakan. Konten bersifat edukatif dan bukan sertifikasi K3 resmi. Ikuti SOP sekolah dan arahan guru/petugas berwenang.
