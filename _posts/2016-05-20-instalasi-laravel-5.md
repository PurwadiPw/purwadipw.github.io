---
layout: post
title: Instalasi Laravel 5
excerpt: "Tutorial cara install laravel 5 baik di ubuntu ataupun windows dengan beberapa cara."
modified: 2015-05-20
initial: I
place: Bandung, Indonesia
---


##### Pertama sebelum menginstal laravel pastikan server anda memiliki minimal <i>requirement</i> seperti berikut:
* PHP >= 5.5.9
* OpenSSL PHP Extension
* PDO PHP Extension
* Mbstring PHP Extension
* Tokenizer PHP Extension

Oke, jika anda telah memenuhi syarat instalasi seperti di atas anda siap untuk menginstal laravel. Ada beberapa cara yang bisa di lakukan untuk menginstal laravel. Masing-masing ada kelebihan dan kekurangan. Untuk selebihnya silahkan pilih yang menurut anda paling gampang. 

Langsung saja ke intinya.

## Cara 1: Via Installer Laravel

Sebelum ke langkah yang pertama, sitem anda harus sudah terinstal composer terlebih dulu. jika belum terinstal anda bisa mengikuti tutorial [berikut](http://purwadipw.github.io/2016/03/24/cara-instal-composer.html).

Pertama, download installer laravel:

    composer global require "laravel/installer"
    
Selanjutnya, jalankan perintah berikut:

    laravel new blog
        

### Kelebihan
* Relatif lebih cepat. 
* Keywordnya lebih simpel dan mudah diingat.
* Dijamin mendapatkan update kode terbaru.

### Kekurangan
* Perlu koneksi internet untuk mendowloand library lainnya.
* Perlu satu langkah tambahan untuk mendownload installer laravel.

### Perkiraan Waktu
* 2 menit*

## Cara 2: Via `composer create-project`

Setelah Anda berhasil menginstall composer, cukup jalankan perintah berikut ini di terminal/console/command prompt Anda:

    composer create-project laravel/laravel blog --prefer-dist

### Kelebihan
* Singkat, cukup satu langkah.

### Kekurangan
* Perlu koneksi internet untuk mendowloand library lainnya.
* Relatif membutuhkan waktu yang lama.

### Perkiraan Waktu
* 10 menit*

## Cara 3: Download Source Laravel Secara Lengkap

[Klik disini](/download) untuk mendownload source Laravel siap pakai (sudah lengkap dengan library lain yang dibutuhkan). Ekstrak file tersebut di document root server Anda (htdocs, www, atau yang sejenisnya). Laravel siap dijalankan.


### Kelebihan
* Ini cara yang paling dikenal oleh rata-rata programmer: download source code, taruh di htdocs, aplikasi bisa langsung diakses.
* Relatif paling cepat.
* Tidak perlu koneksi internet untuk mendownload library lain yang dibutuhkan.

### Kekurangan
* Bisa jadi kode yang Anda download bukan kode terbaru. Oleh karena itu **cara ini sebenarnya tidak dianjurkan**, kecuali Anda cuma ingin mencicipi Laravel secara cepat dan tidak mau dipusingkan dengan `composer`. 

### Perkiraan Waktu
* 1 menit*

> Untuk cara ketiga, sebenarnya update library tetap bisa dilakukan kapanpun Anda mau. Begitu terhubung dengan internet, cukup jalankan perintah `composer update` maka otomatis library akan diperbarui. Yang membedakan hanyalah cara Anda mendapatkan library-library tersebut untuk pertama kali.  

<p class="text-muted">
*Perkiraan waktu didapatkan dengan ujicoba pada jaringan internet dengan kecepatan download 200 KB/s.
</p>