# Khusus buat Khaldaa

Web app kejutan interaktif dari Wahyu untuk Khaldaa.

## Menjalankan secara lokal
1. Pastikan Node.js sudah terpasang.
2. Jalankan `npm install`.
3. Jalankan `npm start`.
4. Buka `http://localhost:3000`.

## Deploy ke Vercel
Hubungkan repository GitHub ke proyek Vercel dan deploy dari branch produksi. Jika domain produksi berubah, sesuaikan `og:url`, `og:image`, dan `twitter:image` pada `index.html`.

## Perilaku dan privasi
- Tidak memakai database dan tidak mengirim jawaban ke server.
- Pilihan jawaban hanya dipakai untuk menampilkan respons di browser.
- Jawaban dapat diubah dan pengguna dapat kembali ke pertanyaan sebelumnya.
- Pilihan "Belum / tidak dulu" dihargai tanpa paksaan.
- Animasi dekoratif mengikuti pengaturan reduced motion perangkat.
- Gambar preview sosial tersedia sebagai `og-preview.png` (1200 × 630).
