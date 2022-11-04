---
layout: post
title: Cara Membuat Bot WhatsApp
date: 2022-11-03
categories: ["dev"]
---

# Cara Membuat Bot WhatsApp (Step by Step)

<img style="image-size:cover; border-radius: 2%" src="https://i.ibb.co/C68VJDZ/Hero-Banner.jpg" alt="Hero Banner">

Diera jaman sekarang kita sudah tidak asing lagi dengan yang namanya _Artificial intelligence_ (AI) atau Kecerdasan Buatan. Ada banyak sekali kelebihan yang dapat dilakukan oleh AI, diantaranya adalah membuat pekerjaan kita semakin efisien, hemat waktu, dan lain sebagainya. WhatsApp Bot merupakan salah satu contoh kecerdasan buatan, yang dimana kita dapat merespon pesan secara cepat _(Real-Time)_ tanpa kita harus mengetik.

Kali ini saya akan share bagaimana cara membuat bot whatsapp menggunakan website berbasis _cloud_ yaitu **Heroku**.

### Apa itu Heroku ?

![Heroku Images!](https://upload.wikimedia.org/wikipedia/commons/thumb/e/ec/Heroku_logo.svg/2560px-Heroku_logo.svg.png "Heroku")

Dikutip dari [Wikipedia](https://en.wikipedia.org/wiki/Heroku), **Heroku** adalah platform cloud sebagai layanan yang mendukung beberapa bahasa pemrograman. Salah satu platform cloud pertama, Heroku telah dikembangkan sejak Juni 2007, ketika hanya mendukung bahasa pemrograman Ruby, tetapi sekarang mendukung `Java, Node.js, Scala, Clojure, Python, PHP, dan Go.`

Oleh karena itu kita akan menggunakan Heroku sebagai tempat hosting bot kita nanti. Oke mari kita mulai....

## Download _Source Code_

Langkah awal yang harus kita lakukan adalah mendownload terlebih dulu asset atau _Source Code_ bot WhatsApp, kalian bisa cari di Github atau juga bisa download melalui link yang sudah saya sediakan [**Download WhatsApp Bot**](https://github.com/4ndrexyz/KatoBot-v2)

## Github

Setelah file tadi terdownload, langkah selanjutnya adalah login ke akun [Github](https://github.com) kalian lalu upload file tadi ke _Repository_ kalian.

![Github Repository Preview!](https://i.postimg.cc/tCGKyj3H/repository.jpg "Github Repository Preview")

Jika file tadi sudah terupload ke _Repsitory_ Github kalian, kita akan masuk ke langkah selanjutnya, yaitu Konfigurasi dan _Deployment_ menggunakan Heroku.

## Heroku & Heroku CLI

Okee, selanjutnya kita akan masuk ke bagian konfigurasi dan _Deployment_ ke website Heroku.

Pertama-tama kunjungi website resmi Heroku terlebih dahulu yaitu [https://www.heroku.com/](https://www.heroku.com/) lalu masuk menggunakan email aktif kalian.

![Heroku!](https://i.postimg.cc/Zntr9jHC/login.jpg "Heroku Web Preview")

Setelah kita berhasil masuk, kita akan diarahkan ke laman Dashboard Heroku, dan klik tombol **Create New App**, untuk membuat Aplikasi baru.

![Create New App!](https://i.postimg.cc/kG2Khz51/create-app.jpg "Create New App")

Setelah itu kita akan disuruh untuk memasukkan **_Name_, _Region_, dan _Pipeline_**, disini kita hanya mengisikan Nama Aplikasinya saja, sebagai contoh saya menggunakan nama **"andrexyz-bot"**

> Untuk nama aplikasi hanya boleh berisikan _lower-case_ saja (huruf kecil)

![Nama Aplikasi!](https://i.postimg.cc/c6qh70cM/name-app.jpg "Nama Aplikasi Heroku")
