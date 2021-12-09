# Jarkom-Modul-5-B10-2021

## Anggota B10
Nama | NRP | Pembagian
------------ | ------------- | -------------
Pramudya Tiandana Wisnu Gautama | 05111940000018 | 
Jason Andrew Gunawan | 05111940000085 | 
Frans Wijaya | 05111940000098 | 

## Daftar Isi
- [Jarkom-Modul-5-B10-2021](#jarkom-modul-5-b10-2021)
  * [Anggota B10](#anggota-b10)
  * [Daftar Isi](#daftar-isi)
  * [Topologi](#topologi)
  * [Konfigurasi](#konfigurasi)
    + [Soal B](#soal-b)
    + [Soal C](#soal-c)
    + [Soal D](#soal-d)
  * [GNS3](#gns3)
    + [Soal 1](#soal-1)
    + [Soal 2](#soal-2)
    + [Soal 3](#soal-3)
    + [Soal 4](#soal-4)
    + [Soal 5](#soal-5)
    + [Soal 6](#soal-6)
  * [Kendala](#kendala)

## Topologi
(A) Tugas pertama kalian yaitu membuat topologi jaringan sesuai dengan rancangan yang diberikan Luffy dibawah ini:

![Topologi](/assets/topologi.png)

Keterangan :
- Doriki adalah DNS Server
- Jipangu adalah DHCP Server
- Maingate dan Jorge adalah Web Server
- Jumlah Host pada Blueno adalah 100 host
- Jumlah Host pada Cipher adalah 700 host
- Jumlah Host pada Elena adalah 300 host
- Jumlah Host pada Fukurou adalah 200 host
---
## Konfigurasi
### Soal B
Karena kalian telah belajar subnetting dan routing, Luffy ingin meminta kalian untuk membuat topologi tersebut menggunakan teknik CIDR atau VLSM. setelah melakukan subnetting, 
#### **Jawaban**

### Soal C
Kalian juga diharuskan melakukan Routing agar setiap perangkat pada jaringan tersebut dapat terhubung.
#### **Jawaban**

### Soal D
Tugas berikutnya adalah memberikan ip pada subnet Blueno, Cipher, Fukurou, dan Elena secara dinamis menggunakan bantuan DHCP server. Kemudian kalian ingat bahwa kalian harus setting DHCP Relay pada router yang menghubungkannya.
#### **Jawaban**
---

## GNS3
### Soal 1
Agar topologi yang kalian buat dapat mengakses keluar, kalian diminta untuk mengkonfigurasi Foosha menggunakan iptables, tetapi Luffy tidak ingin menggunakan MASQUERADE.
#### **Jawaban**

### Soal 2
Kalian diminta untuk mendrop semua akses HTTP dari luar Topologi kalian pada server yang merupakan DHCP Server dan DNS Server demi menjaga keamanan.
#### **Jawaban**

### Soal 3
Karena kelompok kalian maksimal terdiri dari 3 orang. Luffy meminta kalian untuk membatasi DHCP dan DNS Server hanya boleh menerima maksimal 3 koneksi ICMP secara bersamaan menggunakan iptables, selebihnya didrop.
#### **Jawaban**
Jawab

> Kemudian kalian diminta untuk membatasi akses ke Doriki yang berasal dari subnet Blueno, Cipher, Elena dan Fukuro dengan beraturan sebagai berikut:
### Soal 4
Akses dari subnet Blueno dan Cipher hanya diperbolehkan pada pukul 07.00 - 15.00 pada hari Senin sampai Kamis.
#### **Jawaban**

### Soal 5
Akses dari subnet Elena dan Fukuro hanya diperbolehkan pada pukul 15.01 hingga pukul 06.59 setiap harinya.
#### **Jawaban**
Jawab

> Selain itu di reject
### Soal 6
Karena kita memiliki 2 Web Server, Luffy ingin Guanhao disetting sehingga setiap request dari client yang mengakses DNS Server akan didistribusikan secara bergantian pada Jorge dan Maingate
#### **Jawaban**
Jawab

> Luffy berterima kasih pada kalian karena telah membantunya. Luffy juga mengingatkan agar semua aturan iptables harus disimpan pada sistem atau paling tidak kalian menyediakan script sebagai backup.
---
## Kendala