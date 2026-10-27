# MidProject Jarkom_K15_005_025_055

## Anggota Kelompok

| Nama                   | NRP        |
| :--------------------- | :--------- |
| Umar | 5027251005 |
| Tafidah Hasna | 5027251025 |
| Keisya Dira Anugerah   | 5027251055 |

## Laporan Dokumentasi


### 1. Topologi dan Skema

![topologi](images/topologi.png)

**Skema yang digunakan: VLSM**, dengan blok induk `10.120.0.0/16`.


#### Pertimbangan Pemilihan VLSM

![tabel](images/tabel.png)

> Rincian perhitungan disertakan dalam file spreadsheet [(.xslx)](sps/UTS%20JarKom%20K15.xlsx)

Berdasarkan hasil perhitungan pada spreadsheet, kedua skema memiliki kebutuhan aktual sebesar 61.752 alamat. VLSM dapat menampung kebutuhan tersebut dalam blok induk `/16` yang berkapasitas 65.536 alamat, dengan efisiensi penggunaan sebesar 94,23% dan sisa 3.784 alamat. Sementara itu, skema CIDR yang diuji memerlukan total alokasi 118.784 alamat untuk blok per router, sehingga membutuhkan blok induk `/15` berkapasitas 131.072 alamat.

Dari hasil perbandingan tersebut, VLSM dipilih karena mampu memenuhi kebutuhan alamat IP dalam blok induk yang lebih kecil dengan tingkat pemanfaatan alamat yang lebih tinggi. Pada jaringan yang lebih besar atau memiliki kebutuhan routing berbeda, CIDR dapat menjadi alternatif yang relevan.



### 2. Desain Topologi             (router, link, LAN, tunnel)


### 3. Konfigurasi                 (per soal 3-8: tujuan, config, arti tiap perintah)


### 4. Pengujian Mandiri           (per soal: perintah, hasil, screenshot)