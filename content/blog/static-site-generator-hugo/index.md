---
title: "Mulai Ngeblog Pakai Static Site Generator Hugo"
description: "mengenal static site generator hugo beserta keunggulan, kekurangan, dan jenis static site generator"
date: 2023-08-07T11:09:27+07:00
categories: ["Blog","Website"]
tags: ["Static Site Generator", "Hugo"]
summary: "Hugo atau dikenal juga dengan SSG Hugo adalah static site generator dengan bahasa pemrograman Go Lang atau Go."
draft: false
---

Sudah beberapa tahun yang lalu sejak saya mulai ngeblog. berbagai macam platform blogging bahkan sudah pernah coba. Mulai dari blogger, wordpress, sampai ghost sudah pernah saya cicipi. Tidak ada yang buruk sih sebenarnya dari ketiga platform yang sudah pernah saya coba itu. Malah sebenarnya bagus dan lebih powerfull jika bisa di optimasi dengan tepat. Namun setelah melalui beberapa pertimbangan dan ingin mencoba hal baru, akhirnya saya menjatuhkan pilihan ke _SSG_ _(Static Site Generator)_ dan memilih Hugo sebagai platformnya.

## Apa itu _Static Site Generator_?
Gampangnya _Static Site Generator_ atau _SSG_ itu adalah pembuat halaman website statis. Website statis itu yang seperti apa? website statis itu adalah halaman web yang terdiri dari struktur HTML dengan konten isi yang tidak berubah-ubah alias tetap. 

## Perbedaan SSG dengan CMS
Pada hari-hari awal Internet, situs web disimpan sebagai situs HTML statis, dengan semua halaman web ditata dan dikodekan terlebih dahulu. Ini tidak efisien karena mengharuskan pengembang untuk membuat kode setiap halaman web secara manual.

Sistem manajemen konten (CMS) muncul sebagai cara bagi pengembang untuk menghindari semua pengaturan manual itu. Alih-alih mengkode halaman sebelumnya, konten disimpan dalam database CMS, dan ketika pengguna meminta halaman, server melakukan hal berikut:

1. Query database untuk konten
2. Mengidentifikasi template yang sesuai dengan konten
3. Menghasilkan halaman
4. Melayani halaman ke pengguna

Konten dalam CMS harus sesuai dengan salah satu bidang yang ditawarkan oleh database CMS, tetapi selama itu, akan muncul di tempat yang tepat di situs web setiap saat.

SIte Static Generator adalah gabungan antara dua pendekatan ini. Seperti CMS, ini memungkinkan pengembang untuk menggunakan template dan secara otomatis membuat halaman web tetapi melakukan yang terakhir sebelumnya, bukan sebagai tanggapan atas permintaan pengguna. Ini membuat kinerja situs web lebih cepat, karena halaman web langsung siap dikirim ke pengguna akhir. Ini juga menawarkan penyesuaian yang lebih besar kepada pengembang, karena mereka tidak dibatasi oleh bidang basis data yang ditawarkan oleh CMS.

## Cara Kerja Static Site Generator
Generator situs statis bekerja berdasarkan kesederhanaan yang menghasilkan proses cepat. Pada waktu pembuatan, generator atau kerangka situs statis membaca konten dari file sebelum konten tersebut mencapai CDN. Kemudian, konten dirender ke HTML berdasarkan templat dan dikirim ke CDN, yang hasilnya akan sesuai dengan file sumber. File-file ini akan tetap ada di sana dan siap digunakan ketika permintaan konten dibuat.

Generator situs statis juga digunakan bersama dengan framework, yaitu kode bawaan dengan kumpulan file dan folder yang akan membantu mengatur situs web sehingga pengembang akan mendapatkan situs web atau aplikasi yang berfungsi penuh.

## Keunggulan menggunakan Static Site Generator
Nah alasan saya memilih menggunakan _SSG_ itu karena tentu saja memiliki keunggulan. apa saja keunggulannya? pertama lebih cepat, dari sisi kecepatan sudah tidak diragukan lagi. website statis tidak memerlukan _request_ ke database jadi pemuatan halaman akan sangat cepat. yang kedua lebih aman, karena tidak menggunakan database jadi lebih aman asalkan komputer kita tidak dibajak orang lain. yang ketiga murah biayanya. membuat halaman website statis itu murah bahkan bisa gratis. blog Tamago ini saja hanya modal domain, sementara hosting saya menggunakan github yang dideploy memakai cloudflare.

## Kekurangan Static Site Generator
dibalik keunggulannya pastilah juga memiliki kekurangan atau kelemahan. bagi kamu yang tidak terbiasa menggunakan _terminal_ seperti _command prompt_ mungkin akan sedikit kesulitan. membuat website statis memang harus akrab dengan perintah-perintah di _terminal_. selain itu untuk_setup_ dan _build up_ nya juga memerlukan waktu. untuk pemula memang akan sedikit kesusahan. tapi tenang saja, asalkan membaca dokumentasinya dengan benar, semua bisa kok.

## Macam-macam Static Site Generator
varian SSG itu cukup banyak kok. ada Gatsby, Jekyll, gridsome, nuxtjs, hugo, dan masih banyak lagi. Dan Blog Tamago ini menggunakan Hugo. Kenapa saya memilih menggunakan Hugo? tapi sebelumnya ayo kenalan dulu dengan _SSG_ Hugo ini.

### Apa itu Hugo?
Hugo atau dikenal juga dengan SSG Hugo adalah static site generator dengan bahasa pemrograman Go Lang atau Go. Dengan SSG Hugo, kita dapat menciptakan static site atau website statis. Hugo adalah sebuah open-source framework yang saat ini begitu populer di kalangan developer dan programmer. Developer Hugo pun mengklaim, Hugo lebih cepat dibanding SSG lain seperti Jekyll, Middleman, dan Octopress.

Hugo pertama kali dibuat oleh Steve Francia di tahun 2013, yang kemudian mendapat peningkatan besar pada fitur dan performa setelah dikembangkan oleh developer yang dipimpin oleh Bjørn Erik Pedersen sejak tahun 2015. Saat ini Hugo berada dibawah lisensi Apache License 2.0. Framework ini memiliki keunggulan diantaranya, cepat, mudah digunakan, dan dapat dikonfigurasi. Hugo SSG mengambil direktori dengan konten dan template dan membuatnya menjadi situs web HTML lengkap. Nah keunggulan tersebutlah yang membuat saya lebih memilih hugo daripada static site generator yang lain.