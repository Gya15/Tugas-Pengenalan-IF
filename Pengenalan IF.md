## 1.1 Latar Belakang

Karena sekarang zamannya e commerce maka banyak orang memakai toko online untuk menjual dan membeli sesuatu, maka saya ingin mendigitalkan toko saya agar orang tidak perlu ke toko untuk membeli sesuatu, cukup dengan dirumah saja dan menekan tanda beli, maka pesanan akan dikirim ke rumah pembeli.

## 1.2. Deksripsi Teknologi Informasi

Website ini sangat sederhana, dimana pembeli dapat membeli makanan berupa roti, pastry, kue, dan lain-lain. Bisa juga memesan dalam jumlah banyak untuk keperluan acara ataupun kegiatan. Tidak perlu repot, cukup menekan tanda beli atau pesan, maka pesanan akan dikirim ke rumah pembeli atau ke tempat acara.

## 1.3. Branding

Merk : Cita Sari
Tagline : pembelian mudah untuk makanan
Campaign : bagaimana agar orang mudah membeli makanan tanpa harus keluar rumah
Target user :
Seseorang yang ingin makanan ringan dengan cepat
Seseorang yang butuh makanan untuk sebuah acara / kegiatan
seseorang yang memiliki waktu sedikit
User experience :
Mudah 
Sederhana
cepat
murah


## 2. User Story

Sebagai | Saya Ingin bisa | bla | Prioritas
---|---|---|---
Pengguna | membeli makanan | bla | ⭐⭐⭐⭐⭐

## 3. Struktur Data

```mermaid
erDiagram
  PEMBELI {
    string username
    string email
    string password
    string nama_lengkap
  }
 PEMBELI ||--O{ PESANAN:MEMBUAT
 PESANAN ||--O{ ADMIN:MENERUSKAN_PESANAN
 PESANAN {
    string nama_pemesan
    string nama_barang
    int id_jumlah_barang_yang_dipesan
    int id_alamat_pengguna
    int id_pembayaran
    datetime waktu_pemesanan
    datetime waktu_dikirim

 }
```

## 4. Arsitektur Sistem

Masih pake mermaid.js juga bisa lihat flowchart di [https://mermaid.js.org/syntax/flowchart.html](https://mermaid.js.org/syntax/flowchart.html)

## 5. Teknologi, Library, dan Framework

bla bla bla

## 6. Desain User Experience dan User Interface

https://www.figma.com/file/NhKE5dOSKAlfVYIb1P2k2Z/Figma-basics?type=design&node-id=1669%3A162202&mode=design&t=7olGBrC8d37R33Gi-1
https://www.figma.com/file/NhKE5dOSKAlfVYIb1P2k2Z/Figma-basics?type=design&node-id=1669-162202&mode=design

## 7. Demonstrasi Video

Link youtube nya

## 8. Bagaimana mesin komputasi dan sistem operasi berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 9. Bagaimana algoritma, struktur data, dan bahasa pemrograman berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 10. Bagaimana metode pengembangan perangkat lunak / Software Development Life Cycle berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 11. Bagaimana database / sistem basis data berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

