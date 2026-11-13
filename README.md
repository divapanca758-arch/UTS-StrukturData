# UTS-StrukturData
# Diva Oktiana Panca Ramadani
# 312510313

# PROGRAM DATA MAHASISWA MENGGUNAKAN LINKED LIST

## 1. Deskripsi Project

Project ini merupakan program sederhana menggunakan bahasa pemrograman C++ untuk mengelola data mahasiswa dengan menerapkan konsep Linked List.

Program ini dibuat untuk memenuhi tugas mata kuliah Struktur Data. Aplikasi dapat digunakan untuk memasukkan data mahasiswa, menghitung nilai akhir, menentukan mutu, menambahkan data, menghapus data, dan menampilkan seluruh data mahasiswa.

Program menerapkan tiga jenis Linked List, yaitu Single Linked List, Double Linked List, dan Circular Linked List.

## 2. Tujuan Project

- Memahami konsep Linked List dalam bahasa C++.
- Mempelajari penggunaan pointer dan node.
- Mengimplementasikan Single Linked List.
- Mengimplementasikan Double Linked List.
- Mengimplementasikan Circular Linked List.
- Membuat program pengolahan data mahasiswa.
- Menghitung Mutu Angka dan Mutu mahasiswa.

## 3. Teknologi yang Digunakan

- Bahasa Pemrograman: C++
- Aplikasi: Dev-C++ / Code::Blocks
- Konsep: Struktur Data dan Linked List

## 4. Struktur Folder

```text
Tugas-Linked-List/
│
├── main.cpp
└── README.md
```

Keterangan:

- `main.cpp`: Berisi seluruh kode program C++.
- `README.md`: Berisi dokumentasi dan penjelasan project.

## 5. Fitur Program

Program memiliki empat menu utama:

1. Single Linked List
2. Double Linked List
3. Circular Linked List
4. Keluar

Setiap jenis Linked List memiliki submenu:

1. Input Data Mahasiswa
2. Sisip Depan
3. Sisip Tengah
4. Sisip Belakang
5. Hapus Depan
6. Hapus Tengah
7. Hapus Belakang
8. Tampilkan Data Mahasiswa
9. Kembali ke Menu Utama

## 6. Data Mahasiswa

Data yang dimasukkan ke dalam program meliputi:

- NIM
- Nama
- Nilai Tugas (20%)
- Nilai Kehadiran (15%)
- Nilai UTS (30%)
- Nilai UAS (35%)

## 7. Rumus Perhitungan Mutu Angka

Mutu Angka dihitung menggunakan rumus:

```text
Mutu Angka =
(Tugas × 20%) +
(Kehadiran × 15%) +
(UTS × 30%) +
(UAS × 35%)
```

Kriteria penilaian:

| Mutu Angka | Mutu |
|---|---|
| < 45 | E |
| < 55 | D |
| < 65 | C |
| < 75 | B |
| ≥ 75 | A |

## 8. Penjelasan Jenis Linked List

### A. Single Linked List

Setiap node memiliki satu pointer untuk menunjuk ke node berikutnya.

### B. Double Linked List

Setiap node memiliki dua pointer, yaitu next dan prev, sehingga dapat terhubung ke node sebelumnya dan berikutnya.

### C. Circular Linked List

Node terakhir terhubung kembali ke node pertama sehingga membentuk sebuah lingkaran.

## 9. Langkah Menjalankan Program

1. Buka aplikasi Dev-C++ atau Code::Blocks.
2. Buka file `main.cpp`.
3. Compile program.
4. Jalankan program menggunakan tombol Run.
5. Pilih jenis Linked List pada menu utama.
6. Masukkan data mahasiswa.
7. Gunakan menu sisip, hapus, dan tampilkan data sesuai kebutuhan.

## 10. Kesimpulan

Program ini dibuat untuk menerapkan konsep struktur data Linked List menggunakan bahasa pemrograman C++.

Melalui program ini, pengguna dapat memahami perbedaan Single Linked List, Double Linked List, dan Circular Linked List serta mempraktikkan operasi penambahan, penghapusan, dan penampilan data mahasiswa.

Selain itu, program juga menerapkan perhitungan Mutu Angka berdasarkan bobot nilai Tugas, Kehadiran, UTS, dan UAS.

---

**Nama Project:** Program Data Mahasiswa Linked List

**Bahasa Pemrograman:** C++

**Jenis Project:** UTS Struktur Data
