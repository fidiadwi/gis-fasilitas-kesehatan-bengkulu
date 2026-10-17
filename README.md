# Pemetaan dan Analisis Sebaran Fasilitas Kesehatan di Kota Bengkulu Menggunakan GIS

## 1. Deskripsi Proyek

Proyek ini bertujuan untuk memetakan dan menganalisis sebaran fasilitas kesehatan di Kota Bengkulu menggunakan *Geographic Information System* (GIS) dan Python. Proyek ini dibuat sebagai studi kasus penerapan teknologi GIS untuk memahami persebaran fasilitas kesehatan berdasarkan lokasi geografis.

Data fasilitas kesehatan diperoleh dari OpenStreetMap (OSM), yaitu sumber data geografis terbuka. Data tersebut diolah dan dianalisis menggunakan Python melalui Google Colab.

## 2. Tujuan Proyek

- Mengidentifikasi persebaran fasilitas kesehatan di Kota Bengkulu.
- Menampilkan lokasi fasilitas kesehatan pada peta digital.
- Mengetahui jumlah fasilitas kesehatan berdasarkan kategori.
- Menghitung jarak garis lurus ke fasilitas kesehatan terdekat.
- Menghasilkan visualisasi dan ringkasan data untuk mendukung analisis spasial.

## 3. Teknologi yang Digunakan

- Python
- Google Colab
- OpenStreetMap (OSM)
- OSMnx
- GeoPandas
- Pandas
- Matplotlib
- Folium
- Scikit-learn

## 4. Data yang Digunakan

Data diperoleh dari OpenStreetMap melalui proses pengambilan data menggunakan OSMnx. Kategori fasilitas kesehatan yang dianalisis meliputi:

- Rumah sakit (*hospital*)
- Klinik (*clinic*)
- Dokter (*doctors*)
- Dokter gigi (*dentist*)
- Apotek (*pharmacy*)

Ketersediaan dan kelengkapan data bergantung pada informasi yang telah dipetakan oleh kontributor OpenStreetMap.

## 5. Tahapan Analisis

1. Mengambil data batas wilayah Kota Bengkulu.
2. Mengambil data lokasi fasilitas kesehatan dari OpenStreetMap.
3. Membersihkan dan mengolah data menggunakan Python.
4. Menghitung jumlah fasilitas kesehatan berdasarkan kategori.
5. Menghitung jarak garis lurus ke fasilitas kesehatan terdekat.
6. Membuat grafik hasil analisis.
7. Membuat peta digital interaktif.
8. Menyimpan hasil analisis dalam format CSV, PNG, GeoJSON, dan HTML.

## 6. Struktur Proyek

```text
gis-fasilitas-kesehatan/
├── hasil/
│   ├── batas_wilayah.geojson
│   ├── fasilitas_kesehatan.csv
│   ├── grafik_jarak_terdekat.png
│   ├── grafik_jumlah_fasilitas.png
│   ├── peta_fasilitas_kesehatan.html
│   └── ringkasan_fasilitas.csv
├── README.md
└── gis-fasilitas-kesehatan.ipynb
```

Nama berkas notebook dapat disesuaikan dengan nama file `.ipynb` yang kamu unggah ke GitHub.

## 7. Hasil Proyek

Hasil yang dihasilkan dari proyek ini meliputi:

- **Peta fasilitas kesehatan:** Menampilkan persebaran lokasi fasilitas kesehatan secara interaktif.
- **Grafik jumlah fasilitas:** Menampilkan jumlah fasilitas kesehatan berdasarkan kategori.
- **Grafik jarak terdekat:** Menampilkan hasil analisis jarak garis lurus ke fasilitas kesehatan terdekat.
- **Dataset hasil pengolahan:** Menyimpan data fasilitas kesehatan dan ringkasan hasil analisis.

Untuk membuka peta interaktif, unduh file `peta_fasilitas_kesehatan.html` dari folder `hasil`, lalu buka menggunakan peramban (*browser*).

## 8. Batasan Analisis

Analisis ini bergantung pada kelengkapan data OpenStreetMap. Jarak yang dihitung merupakan jarak garis lurus berdasarkan koordinat geografis, bukan jarak perjalanan melalui jalan raya. Oleh karena itu, hasil analisis belum dapat digunakan sebagai ukuran langsung aksesibilitas atau waktu tempuh menuju fasilitas kesehatan.

## 9. Cara Menjalankan Proyek

1. Buka file notebook `.ipynb` menggunakan Google Colab.
2. Jalankan setiap sel kode secara berurutan dari awal hingga akhir.
3. Pastikan koneksi internet tersedia untuk mengambil data dari OpenStreetMap.
4. Tunggu hingga proses pengolahan data dan visualisasi selesai.
5. Periksa hasil analisis pada folder `hasil`.

## 10. Sumber Data

- OpenStreetMap: https://www.openstreetmap.org/
- Dokumentasi OSMnx: https://osmnx.readthedocs.io/

## 11. Penutup

Proyek ini menunjukkan penerapan Python dan GIS untuk mengolah data geografis, memetakan lokasi fasilitas kesehatan, serta melakukan analisis spasial sederhana. Studi kasus ini juga menggambarkan pemanfaatan keterampilan pemrograman dan analisis data dalam menyelesaikan permasalahan berbasis lokasi.

