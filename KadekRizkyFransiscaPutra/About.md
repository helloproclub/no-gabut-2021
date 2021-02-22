---
layout: post
title: "Membangun Website Ketika Gabut"
date:   2021-02-22 18:26:14 +0800
categories: softwrae engineering 
author: Kadek Rizky Fransisca Putra
author_pic: ./assets/rizky.jpg
project_link: https://github.com/rizkyfransisca/personal-blog
---

## Abstrak
Website ini digunakan untuk pengelolaan personal blog saya, disini saya menggunakan node js dan express js sebagai server side dan html, css, dan bootstrap sebagai tampilan sisi client side. Pada blog site ini saya menggunakan mongo db sebagai database yang akan menyimpan artikel yang saya buat dan data pembaca yang mengirimkan saya feedback pada kolom komentar. Pada blog site ini terdapat fitur feedback oleh admin kepada user melalui email, yang saya buat menggunakan nodemailer.


## Deskripsi
Jadi blog site ini dibuat karena adanya tantangan "No Gabut Challenge" dari proclub, tentu saja saya sebagai seorang yang baru mulai belajar website merasa tertantang. Untuk tahap awal saya mulai dengan pemilihan konsep dari blog site yang akan saya buat, setelah itu saya mencari beberapa tutorial yang dapat membantu saya dalam hal pembuatan website ini. Setelah semua hal tersebut terpenuhi , saya mulai mengerjakan blog site dengan membuat API nya terlebih dahulu menggunakan node js dan express js, ketika API telah selesai saya melakukan testing menggunakan postman dan tentu saja terdapat beberapa error yang harus saya perbaiki :D. Singkat cerita error-error tersebut sudah berhasil saya edo tensei :D, setelah error-error tersebut hilang saya mulai membangun front-end dari blog site ini. Karena saya adalah seseorang yang sangat tidak menguasai frontend developer , maka saya menggunakan framework bootstrap dalam membangun frontend blog site ini. Dan karena saya kurang menguasai frontend developer, maka pada blog site ini saya lebih terfokuskan pada pengembangan di sisi backend nya :D. Sekian cerita singkat dari proses pembangunan dan pengembangan blog site ini, semoga konten yang ada pada blog site ini dapat bermanfaat bagi rekan-rekan semua ^^

## Cara Kerja
Viewer:

1. Viewer dapat langsung mengunjungi blogsite dan melihat semua artikel yang tersedia
2. Viewer dapat membaca semua artikel yang tersedia
3. Viewer dapat memberikan komentar/masukan/saran/menghubungi saya dengan mengakses kolom komentar

Admin:

1. Admin harus login terlebih dahulu menggunakan username atau password yang telah disediakan
2. Admin bisa membuat artikel baru
3. Admin bisa mengedit / mengubah artikel yang sudah ada
4. Admin bisa menghapus artikel 
5. Admin bisa mengelola data user yang dicantumkan di kolom komentar
6. Admin bisa menghapus data user jika dirasa sudah tidak diperlukan
7. Admin bisa memberikan feedback kepada user melalui email (nodemailer)


- Teknologi yang digunakan
- Bahasa pemrograman         : JavaScripts
- Database                   : MongoDB
- REST Server                : ExpressJS dan NodeJS
- Situs Website              : HTML, CSS , Bootstrap