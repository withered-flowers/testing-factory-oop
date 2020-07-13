# List the Fans

Sekarang kita akan membuat sebuah aplikasi untuk membaca data fans Pop
garis keras nih !

Dengan diberikan sebuah data bernama `pop.csv`, maka kita akan:

## Release 1: Buat class
Cobalah untuk membaca file `pop.csv` dan berdasarkan file tersebut, buatlah
5 buah class yang akan me-representasikan data yang akan digunakan:
- Fans
- FansBlackpink
- FansIU
- FansTwice
- FansAKB48
- FansJKT48

## Release 2: Buat factory method
Dikarenakan data classnya ada banyak sekali, maka tidak `sah` rasanya apabila
tidak ada factory methodnya, maka, cobalah untuk membuat sebuah class Factory
dengan nama `FansFactory` yang didalamnya memiliki sebuah method dengan nama
`createFans` yang akan digunakan untuk meng-*instantiate* semua class Fans yang
ada.

## Release 3: Buat tabel-nya !
Setelah berhasil membuat semuanya, maka saatnya kita untuk menampilkannya. 
Tampilkannya seluruh data dengan mengelompokannya satu per satu dalam bentuk
tabel.

Hint: gunakan `console.table` untuk membuat tabelnya !

contoh output
```javascript
=============
Tabel Fans IU
=============
┌─────────┬──────┬───────────┬─────────────────────┬─────────────┐    
│ (index) │  0   │     1     │          2          │      3      │    
├─────────┼──────┼───────────┼─────────────────────┼─────────────┤    
│    0    │ 'iu' │  'Wangi'  │  'wangi@gmail.com'  │  '1000000'  │    
│    1    │ 'iu' │ 'Handoko' │ 'handoko@yahoo.com' │ '150000000' │    
└─────────┴──────┴───────────┴─────────────────────┴─────────────┘    

====================
Tabel Fans Blackpink
====================
┌─────────┬─────────────┬──────────┬────────────────────┬────────────┐
│ (index) │      0      │    1     │         2          │     3      │
├─────────┼─────────────┼──────────┼────────────────────┼────────────┤
│    0    │ 'blackpink' │ 'Melati' │ 'melati@gmail.com' │ '10000000' │
│    1    │ 'blackpink' │ 'Erlina' │ 'erlina@coba.com'  │ '10000000' │
└─────────┴─────────────┴──────────┴────────────────────┴────────────┘

...
```

Untuk contoh output di atas, bisa berbeda `header` nya yah !