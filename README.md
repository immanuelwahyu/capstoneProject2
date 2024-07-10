# CAPSTONE PROJCET 2

Pada capstone Project 2 ini, saya melakukan analisis penggunaan Transjakarta. Analisis yang dilakukan adalah sebagai berikut
1) Mencari pengguna utama dari Transjakarta
2) Waktu pengguna Transjakarta dengan penggunaan terttinggi
3) Rute dengan pengguna Transjakarta tertinggi


# Dataset yang digunakan
| Nama Kolom        | Deskripsi                                                                                         |
|-------------------|--------------------------------------------------------------------------------------------------|
| transID           | ID transaksi yang unik untuk setiap transaksi.                                                    |
| payCardID         | Identifikasi utama dari pelanggan. Kartu yang digunakan pelanggan sebagai tiket untuk masuk dan keluar. |
| payCardBank       | Nama bank penerbit kartu pembayaran milik pelanggan.                                             |
| payCardName       | Nama pelanggan yang ada di kartu.                                                                 |
| payCardSex        | Jenis kelamin pelanggan yang ada di kartu.                                                        |
| payCardBirthDate  | Tahun kelahiran pelanggan.                                                                        |
| corridorID        | ID Koridor / ID Rute sebagai kunci untuk pengelompokan rute.                                     |
| corridorName      | Nama Koridor / Nama Rute berisi Mulai dan Selesai untuk setiap rute.                              |
| direction         | Arah rute. 0 untuk Pergi, 1 untuk Pulang.                                                         |
| tapInStops        | ID halte tempat pelanggan melakukan Tap Masuk.                                                     |
| tapInStopsName    | Nama halte tempat pelanggan melakukan Tap Masuk.                                                   |
| tapInStopsLat     | Garis lintang dari halte tempat pelanggan melakukan Tap Masuk.                                    |
| tapInStopsLon     | Garis bujur dari halte tempat pelanggan melakukan Tap Masuk.                                       |
| stopStartSeq      | Posisi halte awal dalam rute perjalanan pelanggan pada saat melakukan Tap Masuk.                   |
| tapInTime         | Waktu pelanggan melakukan Tap Masuk yang mencakup tanggal dan jam.                                 |
| tapOutStops       | ID halte tempat pelanggan melakukan Tap Keluar.                                                    |
| tapOutStopsName   | Nama halte tempat pelanggan melakukan Tap Keluar.                                                  |
| tapOutStopsLat    | Garis lintang dari halte tempat pelanggan melakukan Tap Keluar.                                     |
| tapOutStopsLon    | Garis bujur dari halte tempat pelanggan melakukan Tap Keluar.                                       |
| stopEndSeq        | Posisi halte akhir dalam rute perjalanan pelanggan pada saat melakukan Tap Keluar.                 |
| tapOutTime        | Waktu pelanggan melakukan Tap Keluar.                                                              |

