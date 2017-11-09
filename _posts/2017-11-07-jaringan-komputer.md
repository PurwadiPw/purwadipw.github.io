---
layout: post
title: Jaringan Komputer
excerpt: "Di postingan kali ini saya akan menjelaskan tentang Jaringan Komputer."
modified: 2017-11-07
initial: J
place: Bandung, Indonesia
---

# DAFTAR ISI
1. Jaringan Komputer
	1. Pengertian Jaringan Komputer
	2. Macam-Macam Jaringan Komputer
	3. Komponen Jaringan Komputer
	4. Perangkat Jaringan Komputer
	5. Topologi Jaringan Komputer
	6. Manfaat Jaringan Komputer

## Jaringan Komputer
Komunikasi antar komputer pada saat ini sudah tidak mengenal batas-batas geografi, artinya dengan komputer yang kita miliki, kita dapat mengakses dan mencari data di seluruh dunia. Kita cukup menyalakan komputer kemudian mengkoneksikan ke internet dan semua informasi yang kita inginkan sudah tersaji di layar monitor. Bagaimana hal ini terjadi? Semua ini dapat terjadi karena adanya teknologi jaringan komputer.

### Pengertian Jaringan Komputer
Jaringan komputer adalah kumpulan dua atau lebih komputer yang saling berhubungan satu sama lain untuk melakukan komunikasi data dengan menggunakan protocol komunikasi melalui media komunikasi (kabel atau nirkabel), sehingga komputer-komputer tersebut dapat saling berbagi informasi, data, program-program, dan penggunaan perangkat keras secara bersama. Dalam hal ini komunikasi data yang bisa dilakukan melalui jaringan komputer dapat berupa data teks, gambar, video dan suara.

### Macam-Macam Jaringan Komputer
1. Berdasarkan Jangkauan Areanya
	* Local Area Network (LAN)  
		LAN adalah sebuah jaringan komputer dengan jangkauan area yang terbatas dan hubungan fisik antar komputer saling berdekatan. Misalnya jaringan di sebuah kantor atau sebuah ruangan.
	* Metropolitan Area Network (MAN)  
		MAN biasanya meliputi area yang lebih besar dari LAN, area yang digunakan adalah dalam sebuah kota. Dalam hal ini jaringan komputer menghubungkan beberapa buah jaringan-jaringan LAN ke dalam lingkungan area yang lebih besar, misalnya jaringan pada sistem online perbankan, yang menghubungkan antar kantor cabang bank tersebut.
	* Wide Area Network (WAN)  
		WAN adalah jaringan komputer dengan jangkauan area geografi yang dapat mencangkup antar negara bahkan benua. WAN merupakan gabungan dari MAN yang saling terhubung satu sama lain.
	* Internet  
		Internet yaitu jaringan komputer yang memiliki jangkauan hingga seluruh pelosok di dunia ini. Seringkali dimanfaatkan untuk berbagi informasi secara global meliputi pendidikan, hiburan, teknologi, dan lain sebagainya.

2. Berdasarkan Distribusi Sumber Informasi/ Data
	* Jaringan Terpusat  
		Yang dimaksud jaringan terpusat adalah jaringan yang terdiri dari komputer client dan komputer server dimana komputer client bertugas sebagai perantara dalam mengakses sumber informasi/ data yang berasal dari komputer server. Dalam jaringan terpusat, terdapat istilah dumb terminal (terminal bisu), dimana terminal ini tidak memiliki alat pemroses data.
	* Jaringan Terdistribusi  
		Jaringan ini merupakan hasil perpaduan dari beberapa jaringan terpusat sehingga memungkinkan beberapa komputer server dan client yang saling terhubung membentuk suatu sistem jaringan tertentu.

3. Berdasarkan Bentuk Jaringannya
	* Client Server  
		Client Server merupakan jaringan komputer yang seluruh aktivitasnya terpusat pada satu komponen tertentu yaitu server, dan server tersebut akan tetap menjadi server untuk melayani client-nya yang juga akan tetap menjadi client. Artinya dalam jaringan ini yang bertindak menjadi server tidak bisa menjadi client begitu pula sebaliknya (dedicated server).
	* Peer to peer  
		Peer to peer merupakan jaringan komputer yang semua anggota jaringannya bisa menjadi server maupun client. Artinya sever pada jaringan ini dapat berperan sebagai client begitu pula sebaliknya client dapat berperan sebgai server.

### Komponen Jaringan Komputer
1. Media Transmisi  
	Merupakan suatu media yang berfungsi untuk menghubungkan antar komputer secara fisik sebagai sarana komunikasi data.  
	* Media Transmisi Dengan Kabel  
		Dalam jaringan komputer dikenal dengan 3 macam kabel sebagai sarana komunikasi data, antara lain: 
		1. UTP ( Unshielded Twisted Pair )  
			Kabel UTP (Unshieladed Twisted Pair), secara fisik terdiri atas empat pasang kawat medium, setiap pasang dipisahkan oleh lapisan pelindung. Kabel UTP terdiri dari delapan pin warna. Dimana terdapat dua tipe kabel yang umum, yaitu kabel straight-through digunakan untuk menghubungkan sebuah hub dengan switch dan kabel cross-over digunakan untuk menghubungkan dua buah komputer secara peer to peer tanpa hub dan switch.
		2. STP ( Shielded Twisted Pair )  
			Secara fisik kabel shielded sama dengan unshielded tetapi perbedaannya sangat besar dimulai dari kontruksi kabel shielded mempunyai selubung tembaga atau alumunium foil yang khusus dirancang untuk mengurangi gangguan elektrik.

### Perangkat Jaringan Komputer
1. Server  
	Suatu server merupakan jantung dari kebanyakan jaringan. Server biasanya merupakan komputer berkecepatan tinggi dengan kapasitas memori (RAM) yang besar, dan dihubungkan dengan antar muka jaringan yang cepat (Fast Network Interface). Sistem operasi jaringan bekerja pada komputer tersebut, bersama perangkat lunak applikasi dan file data yang diperlukan. Komputer Server adalah suatu unit komputer yang berfungsi untuk menyimpan informasi dan untuk mengelola suatu jaringan komputer.Komputer server akan melayani seluruh client atau workstation yang terhubung ke jaringannya. Berdasarkan fungsi tersebut bisa dikatakan bahwa komputer server adalah komputer induk.
2. Work Station  
	Semua komputer yang terhubung kepada server disebut dengan work station. Work Station merupakan komputer standar yang dikonfigurasikan menggunakan kartu antar muka jaringan, perangkat jaringan dan kabel-kabel yang diperlukan.
3. NIC (Network Interface Card)/Ethernet Card  
	NIC adalah sebuah kartu yang berfungsi sebagai jembatan dari komputer ke sebuah jaringan komputer. NIC berada di layer datalink.
4. WiFi Adapter  
	WiFi Adapter adalah sebuah perangkat jaringan yang berfungsi menangkap sinyal Wifi yang dipancarkan Wireless Router maupun Access Point.
5. Switch  
	Switch adalah sebuah alat yang menyaring dan melewatkan (mengijinkan lewat) paket yang ada disebuah LAN. Switch bekerja pada layer data link (layer 2) dan terkadang di network (layer 3) berdasarkan referensi OSI Layer. Switch dapat mempelajari alamat hardware host tujuan, sehingga informasi bisa langsung dikirim ke host tujuan. Switch yang lebih cerdas dapat mengecek dan memblok frame yang error.
6. HUB  
	Hub atau konsentrator adalah sebuah perangkat yang menyatukan kabel-kabel jaringan dari tiap-tiap workstation, server, atau perangkat lain. Keuntungan mengunakan hub adalah fleksibelitas yang dimiliki, sehingga setiap client dapat di tambahkan setiap waktu tanpa menganggu jaringan yang sedang beroperasi. Akan tetapi Hub tidak mampu membaca data dan tidak mengetahui sumber dari tujuan paket-paket yang dilepaskan melalui Hub tersebut.
7. Bridge  
	Bridge adalah sebuah perangkat yang menghubungkan beberapa jaringan untuk mendapatkan jaringan yang efiesien. Kebanyakan bridge dapat mengetahui masing-masing alamat dari tiap segmen komputer pada jaringan disekitarnya. Diibaratkan bahwa bridge seperti lalu lintas yang mengatur dipersimpangan jalan pada saat jam-jam sibuk. Bridge mengatur agar informasi diantara kedua sisi jaringan tetap berjalan dengan baik dan teratur.
8. Repeater  
	Repeater merupakan sebuah device yang meregenerasi/menghasilkan kembali sinyal yang ditransmisikan pada kabel. Repeater mengijinkan sinyal untuk mengalir diluar batas keterbatasan panjang kabel. Device ini berada dilayer Physical. Sebuah repeater tidak melakukan translasi atau filterisasi paket.
9. Router  
	Router adalah sebuah alat jaringan komputer yang sering digunakan untuk menggabungkan beberapa network. Baik network yang sama maupun berbeda dari segi teknologinya. Router juga digunakan untuk membagi network besar menjadi beberapa buah subnetwork. Router.ini memiliki fungsi tambahan sebagai firewall

### Topologi Jaringan Komputer
Topologi jaringan komputer adalah gambaran atau konsep yang akan digunkan untuk membangun sebuah jaringan komputer. 

Topologi jaringan dapat dibedakan menjadi:

1. Topologi Bus  
	Merupakan topologi yang menggunakan sebuah kabel utama sebagai tulang punggung jaringan.
2. Topologi Star  
	Merupakan topologi yang menggunkan concentrator (hub atu switch) sebagai pengatur paket data.
3. Topologi Tree  
	Merupakan kombinasi dari topologi bus dengan topologi star. Dalam topologi ini tidak semua node mempunyai kedudukan yang sama.
4. Topologi Ring  
	Topologi jaringan yang berupa lingkaran tertutup yang berisi node-node. Data mengair dalam dua arah sehingga dapat menghindari terjadinya collision sehingga memungkinkan terjadinya pergerkan data yang cepat.
5. Topologi Mesh  
	Pada topologi ini semua komputer saling terkoneksi satu sama lain tanpa adanya konsep tertentu.

### Manfaat Jaringan Komputer
Berbicara mengenai manfaat dari jaringan komputer. Terdapat banyak sekali manfaat jaringan komputer, antara lain :

1. Dengan jaringan komputer, kita bisa mengakses file yang kita miliki sekaligus file orang lain yang telah diseberluaskan melalui suatu jaringan, semisal jaringan internet.
2. Melalui jaringan komputer, kita bisa melakukan proses pengiriman data secara cepat dan efisien.
3. Jaringan komputer membantu seseorang berhubungan dengan orang lain dari berbagai negara dengan mudah.
4. Selain itu, pengguna juga dapat mengirim teks, gambar, audio, maupun video secara real time dengan bantuan jaringan komputer.
5. Kita dapat mengakses berita atau informasi dengan sangat mudah melalui internet dikarenakan internet merupakan salah satu contoh jaringan komputer.
6. Misalkan dalam suatu kantor memerlukan printer, kita tidak perlu membeli printer sejumlah dengan komputer yang terdapat pada kantor tersebut. Kita cukup membeli satu printer saja untuk digunakan oleh semua karyawan kantor tersebut dengan bantuan jaringan komputer.