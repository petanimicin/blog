---
title: "Mulai Ngeblog Pakai Static Site Generator"
meta_title: "mulai ngeblog pakai static site generator"
description: "this is meta description"
date: 2023-08-07T11:09:27+07:00
image: "/images/ngeblog-pakai-static-site-generator.png"
categories: ["Blog","Website"]
author: "Webillian Adhi"
tags: ["Static Site Generator", "Hugo"]
draft: false
---

{{< toc >}}

Sudah beberapa tahun yang lalu sejak saya mulai ngeblog. berbagai macam platform blogging bahkan sudah pernah coba. Mulai dari blogger, wordpress, sampai ghost sudah pernah saya cicipi. Tidak ada yang buruk sih sebenarnya dari ketiga platform yang sudah pernah saya coba itu. Malah sebenarnya bagus dan lebih powerfull jika bisa di optimasi dengan tepat. Namun setelah melalui beberapa pertimbangan dan ingin mencoba hal baru, akhirnya saya menjatuhkan pilihan ke _SSG_ _(Static Site Generator)_ dan memilih Hugo sebagai platformnya.

## Apa itu _Static Site Generator_?
Gampangnya _Static Site Generator_ atau _SSG_ itu adalah pembuat halaman website statis. Website statis itu yang seperti apa? website statis itu adalah halaman web yang terdiri dari struktur HTML dengan konten isi yang tidak berubah-ubah alias tetap. 

### Keunggulan menggunakan Static Site Generator
Nah alasan saya memilih menggunakan _SSG_ itu karena tentu saja memiliki keunggulan. apa saja keunggulannya? pertama lebih cepat, dari sisi kecepatan sudah tidak diragukan lagi. website statis tidak memerlukan _request_ ke database jadi pemuatan halaman akan sangat cepat. yang kedua lebih aman, karena tidak menggunakan database jadi lebih aman asalkan komputer kita tidak dibajak orang lain. yang ketiga murah biayanya. membuat halaman website statis itu murah bahkan bisa gratis. blog Tamago ini saja hanya modal domain, sementara hosting saya menggunakan github yang dideploy memakai cloudflare.

### Kekurangan Static Site Generator
dibalik keunggulannya pastilah juga memiliki kekurangan atau kelemahan. bagi kamu yang tidak terbiasa menggunakan _terminal_ seperti _command prompt_ mungkin akan sedikit kesulitan. membuat website statis memang harus akrab dengan perintah-perintah di _terminal_. selain itu untuk_setup_ dan _build up_ nya juga memerlukan waktu. untuk pemula memang akan sedikit kesusahan. tapi tenang saja, asalkan membaca dokumentasinya dengan benar, semua bisa kok.

### Macam-macam Static Site Generator
varian SSG itu cukup banyak kok. ada Gatsby, Jekyll, gridsome, nuxtjs, hugo, dan masih banyak lagi. Dan Blog Tamago ini menggunakan Hugo. Kenapa saya memilih menggunakan Hugo mungkin akan kita bahas diartikel berikutnya.