# EventHub - Sistem Pendaftaran Workshop Informatika

Proyek UTS Pemrograman Web berupa halaman front-end untuk menampilkan informasi workshop dan menerima pendaftaran peserta. Dibuat dengan HTML5, CSS3, Bootstrap, dan JavaScript dasar.

## Alur Dasar Web: Browser → Web Server → Response

Saat pengguna mengetik alamat web atau mengklik sebuah link, Browser mengirim sebuah request ke Web Server. Web Server mencari file yang diminta, lalu mengirim Response berupa file HTML, CSS, dan JavaScript. Browser kemudian membaca file-file itu dan menampilkannya sebagai halaman web. Pada proyek ini semua file bersifat statis, jadi server hanya mengirim file apa adanya, dan interaksi form (validasi dan ringkasan pendaftaran) dijalankan oleh JavaScript di sisi Browser.

## Struktur Folder

```
NIM_Nama_UTSWeb/
├── index.html        # halaman utama (header, workshop, form, footer)
├── css/
│   └── style.css     # styling eksternal
├── js/
│   └── script.js     # validasi form dan ringkasan pendaftaran
├── assets/           # gambar dan file pendukung
├── README.md         # penjelasan proyek
└── git-log.pdf       # bukti hasil git log --oneline
```

## Cara Menjalankan

Buka file `index.html` langsung di browser. Tidak perlu instalasi tambahan karena Bootstrap dimuat lewat CDN.