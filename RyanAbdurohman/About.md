---
layout: post
title: "Proclub NoGabut Challenge: Membuat Personal Blog"
date:   2021-02-13 22:03:24 +0900
categories: Teknologi
author: Ryan Abdurohman
author_pic: https://pbs.twimg.com/profile_images/1356209293679157248/z_XH7vWi_400x400.jpg
project_link: https://github.com/khavitidala/ootsuki
---

<p>Tantangan ini adalah tantangan dalam membuat personal blog. Functional Requirement yang direncanakan sangatlah sederhana yaitu hanya terdapat fungsionalitas CRUD. Dalam blog ini fungsionalitas yang ada yaitu membuat post dan komentar, mengupdate post, menghapus post dan komentar, serta menampilkan post dan komentar. Menurut saya, sebagai pemula yang baru belajar pemrograman web, tantangan ini memfasilitasi saya sebagai media ngulik framework django (python). Maka, akhirnya saya memutuskan untuk menggunakan django.&nbsp;</p>

<p>Relasi data pada personal blog tidaklah rumit, maka saya tidak membuat ERD-nya, langsung implementasi kodingan. UI nya pun insidental, langsung eksperimen menggunakan bootstrap 4, tanpa UI/UX design dan testing terlebih dahulu.</p>

<p>Proses pembuatannya cukup sederhana. Kita hanya perlu mengetikan perintah&nbsp;</p>

```
django-admin startproject namaproject
```

<p>maka boom, kita langsung mendapatkan boilerplate project dengan arsitektur mirip MVC. Lalu kita membuat app dengan mengetikan perintah di bawah pada direktori project kita:</p>

```
python manage.py startapp appkita
```

<p>Saya tidak akan menjelaskan detail, namun prosesnya memanglah sederhana. Kita mengatur konfigurasi di settings, lalu mengatur routing di urls.py. Tentunya kita harus membuat model dan view nya terlebih dahulu. Semua kode sudah saya cantumkan di repository github. Ada tiga model yang saya buat&nbsp;yaitu category, post, dan comment. Saya menggunakan database bawaan python yaitu sqlite3. Adapun saya memanfaatkan app yang bernama ckeditor untuk menambahkan rich text editor pada saat post.</p>
