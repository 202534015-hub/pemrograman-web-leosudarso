# CSS Problem dan Perbaikan

## Masalah

Halaman web awalnya tampil seperti HTML tanpa styling meskipun aturan CSS sudah dibuat.

## Penyebab

File HTML menggunakan path:

`css/gaya.css`

Padahal file stylesheet berada langsung di folder `tugas_2` dengan nama:

`style.css`

Akibatnya browser tidak dapat menemukan stylesheet dan menampilkan halaman menggunakan style bawaan browser.

## Perbaikan

Path stylesheet pada `index.html` diubah menjadi:

`<link rel="stylesheet" href="style.css">`

Setelah path diperbaiki dan halaman di-refresh, CSS berhasil dimuat dan seluruh aturan styling dapat diterapkan.

## Pengujian

Saya menguji kembali halaman melalui Live Server dan memastikan perubahan warna, typography, card, form, gambar, navigasi, dan focus indicator sudah tampil.