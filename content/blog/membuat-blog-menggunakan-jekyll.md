---
title: "Membuat Blog Menggunakan Jekyll"
date: 2023-09-21T13:53:34+07:00
draft: true
---

Salah satu cara membuat blog adalah menggunakan _SSG_ atau _static site generator_ atau mesin pembuat situs statis. salah satu _SSG_ yang cukup populer dan mudah digunakan adalah Jekyll. Jekyll adalah generator situs web statis sederhana, mendukung-blog, yang diperuntukan untuk situs pribadi, proyek, atau organisasi. Jekyll ditulis dalam bahasa pemrograman Ruby oleh Tom Preston-Werner, Co-Founder GitHub, dan didistribusikan di bawah lisensi sumber terbuka. Jekyll dirilis pertama kali oleh Tom Preston-Werner pada tahun 2008.Dengan pengunduran Preston-Werner dari GitHub pada bulan April 2014, proyek ini kehilangan pimpinan pengembang. Jekyll memulai tren pengembangan web dengan kecenderungan pada situs web statis.

## Kelebihan dari Website Jekyll
Berikut adalah beberapa kelebihan dalam menggunakan Website Statis:

### Tidak Membutuhkan Database
Tidak seperti WordPress dan Content Managemen System (CMS) lainnya, Jekyll tidak memiliki dan tidak membutuhkan Database. Semua postingan dan halaman akan diubah ke dalam HTML sebelum dipublikasikan.

### Tidak Membutuhkan CMS
Kita hanya perlu menulis semua konten dalam format Markdown dan Jekyll akan menjalankannya melalui template agar dapat menghasilkan Website Statis. GitHub dapat berfungsi sebagai CMS  karena kita dapat mengedit konten yang ada di dalamnya.

### Cepat
Jekyll dapat dianggap cepat karena tidak memerlukan database, kita hanya perlu menyiapkan halaman statis. Jekyll Now hanya memiliki tiga HTTP Request - termasuk gambar profil dan social icon!

### Dapat Mengontrol Design
Kita dapat mengedit Template yang sudah dibuat oleh orang lain atau membuatnya sendiri dengan mudah.

### Aman
Hampir semua kemanan yang rentan pada platform seperti WordPress tidak berlaku di Jekyll karena tidak membutuhkan CMS, database, atau PHP. Jadi, kita tidak perlu menghabiskan banyak waktu untuk mengatasi masalah keamanan.

### Hosting yang Nyaman
Kenyamanan yang dapat kita rasakan jika sudah menggunakan GitHub yaitu: Tidak memerlukan biaya apapun.

## Cara Membuat Blog dengan Jekyll
Membuat blog menggunakan Jekyll sebenarnya cukup mudah. Jika kamu menggunakan Linux, saya sarankan untuk membaca dokumentasinya terlebih dahulu. Karena disini saya akan membagikan tutorial membuat blog dengan Jekyll menggunakan Windows.

Sebelum memulai persiapkan dahulu:
- Akun Github, jika belum punya silahkan daftar terlebih dahulu.
- Github Dekstop, bisa didownload saat sudah mempunyai akun github.
- VSCODE Studio, untuk membuat konten maupun penataan blog.

### Membuat Repository di Github
Setelah membuat akun github, buatlah sebuah repositori. Disini saya memberi nama contoh, kalian bisa sesuaikan namanya sesuai keinginan kalian.

<img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEh9pYy4WV3wD9aXnZp80mfettYWhF2OIwEDBveDsvaXCnvKTHuF03VToHpniQahjg96r8saTjeiT5ZTry04q8M5BGxfCoonpPQ8yNCHOmZe7PV6x5NEu2xOQ7IkeIe6WRijoeonu9fo168rwomeRtphLl1hEXZc7-AxJRuBulxCrhD7HX6n1B0H4Fig-TvS/s1887/github.png" alt="buat repositori di github"/>

Setelah itu klik _create repository_. maka akan muncul seperti ini.

<img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgqcwg_XTK-k2D3LX9ltCk-Zo2QSF-wAhSqmIOPvP7zrObcnU3p4YTjIDVT9omcOvJaGVH99KminlSt8OfsmIKsrOE-ddf6Nn-4Qj5FK7CeL_XumbEfwsJImjFxtfjlREyNJLQIvpl7cvnOZuiYjRSTGe8fGjBu_2qrR8TK5QmgCcdjFCfs3wFq_fpvXLp5/s1762/repositori-github.png" alt="gunakan github dekstop"/>

### Clone Repository dengan Github Desktop
Selanjutnya kita akan gunakan Github Dekstop untuk clone repository kita ke komputer, dengan Github Desktop kita tidak perlu repot-repot mengetikan perintah di terminal.

<img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEj4nmfnxXslabrI3FsGzxryzD6F60H2goTMaUJd7ylrwdmxXakyWlNdUvL9v2TA39ONMgveK1dY7dciVukdWxayO1Yfia0M3jIXa1x5qDhQymg37zEiBsjgNXl1CPrRFCuV9UsJzVSOjIcNZ1UGPr031P-XLwTrrTD2zP8YAjBjPlUjNWVUtwAdYlbGaTn3/s949/clone.png" alt="gunakan github dekstop"/>

Silahkan pilih tempat dikomputer kalian untuk menyimpan repository. Bebas tidak harus di C:/

Silahkan buka folder repository tadi di komputer kalian.

### Instal Tema
Langkah berikutnya adalah menginstal tema, silahkan cari tema Jekyll di Google. Misalnya disini saya pakai theme affiliate jekyll dari wowthemes. kemudian download dan ekstrak file temanya. lalu copy semua isi dalam folder tema tadi dan pastekan kedalam directory yang tadi sudah kita clone ke komputer kita.

### Push File ke Github
Jika sudah saatnya push file kita ke Github menggunakan Github Desktop


