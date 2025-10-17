# Hasil Screenshot

Berikut adalah hasil tampilan aplikasi Flutter setelah Implementasi title row
![Hasil Screenshot](langkah1.png, langkah2.png, langkah2_1.png, langkah3.png, langkah4.png, langkah5.png, langkah6.png, hasil.png)

# Praktikum 7 - Manajemen Plugin di Flutter

## Langkah 2
Menambahkan plugin `auto_size_text` menggunakan `flutter pub add auto_size_text`. 
Langkah ini menambahkan dependensi eksternal agar Flutter dapat menggunakan fitur teks otomatis yang menyesuaikan ukuran.

## Langkah 5
Menambahkan variabel `text` agar widget `AutoSizeText` dapat menerima input teks dari luar. 
Tanpa variabel ini akan muncul error karena `text` belum didefinisikan.

## Langkah 6
Menambahkan dua widget: 
- `RedTextWidget` (menggunakan plugin auto_size_text, teks merah, menyesuaikan ukuran).
- `Text` (teks bawaan Flutter, ukuran tetap).  
Perbedaannya ada pada pengaturan ukuran otomatis.

## Parameter AutoSizeText
|-----------------------------------------------|-------------------------------------|                             
|                                               |                                     |
|                   Parameter                   |                     Fungsi          |
|-----------------------------------------------|-------------------------------------|                             
| text                                          | Teks yang akan ditampilkan          |
| style                                         | Gaya teks                           |
| maxLines                                      | Batas jumlah baris                  |
| overflow                                      | Efek jika teks berlebih             |
| minFontSize, maxFontSize, stepGranularity     | Pengaturan ukuran font              |
| group                                         | Menyamakan ukuran teks antar widget |
|-----------------------------------------------|-------------------------------------|                             
