# Pertemuan 06 Nested Loop Python

**Algoritma dan Pemrograman | Pertemuan 06**

Nama: Siti Fitriani
NIM: 2225250213
Kelas: 3B
Program Studi: Pendidikan Matematika
Fakultas: FKIP Untirta

## Tujuan

Mempelajari dan menerapkan nested loop, pola, akumulasi, dan pencacahan menggunakan Python.

## Struktur Folder

```text
pertemuan-06-nested-loop-2225250213/
├── README.md
├── .gitignore
├── latihan/
│   ├── 01_pasangan_indeks.py
│   ├── 02_pola_segitiga.py
│   ├── 03_jumlah_per_baris.py
│   └── 04_hitung_pasangan.py
└── tugas/
    └── tabel_perkalian_dan_statistik.py
```

## Cara Menjalankan

Jalankan program melalui terminal VS Code:

```bash
python tugas/tabel_perkalian_dan_statistik.py
```

## Algoritma Tugas 3

1. Memasukkan bilangan positif `n`.
2. Memvalidasi `n` menggunakan `while` sampai nilainya positif.
3. Menggunakan loop luar untuk setiap baris.
4. Menggunakan loop dalam untuk setiap kolom.
5. Menghitung hasil perkalian `i * j`.
6. Menggunakan akumulator untuk menghitung total seluruh hasil dan jumlah setiap baris.
7. Menggunakan counter untuk menghitung banyak hasil genap.
8. Menampilkan tabel perkalian dan statistik.

## Hasil Pengujian

| Input n | Total Seluruh Hasil | Banyak Hasil Genap | Status   |
| ------- | ------------------: | -----------------: | -------- |
| 1       |                   1 |                  0 | Berhasil |
| 2       |                   9 |                  3 | Berhasil |
| 3       |                  36 |                  5 | Berhasil |

## Analisis Efisiensi

Untuk input `n`, loop dalam dijalankan sebanyak `n × n` atau `n²` kali.

Contohnya, jika `n = 3`, maka loop dalam berjalan:

```text
3 × 3 = 9 kali
```

Sehingga kompleksitas waktu program adalah **O(n²)**.

## Refleksi

Kesalahan yang perlu diperhatikan pada nested loop adalah penempatan variabel akumulator. `total_baris` harus diatur ulang pada setiap awal loop luar agar jumlah setiap baris tidak tercampur dengan baris sebelumnya.

Dari latihan ini, saya memahami bahwa nested loop dapat digunakan untuk membuat pola, tabel, menghitung pasangan, serta melakukan akumulasi dan pencacahan.
