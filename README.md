# Pertemuan 05 Perulangan Python

## Identitas

Nama: Ziana Alfia Zahra
NIM: 2225250076
Kelas: 3A

## Tujuan

Tujuan dari tugas ini adalah mempelajari penggunaan perulangan `for` dan `while` dalam Python, melakukan tracing perubahan variabel, memilih jenis perulangan yang sesuai, serta menguji kondisi berhenti pada program.

## Cara Menjalankan Program

Program dijalankan melalui VS Code menggunakan Python.

Langkah-langkah:

1. Buka folder tugas di VS Code.
2. Buka file Python yang akan dijalankan.
3. Jalankan program melalui terminal.
4. Masukkan input sesuai dengan yang diminta program.
5. Periksa hasil program berdasarkan test case yang diberikan.

## Algoritma Kuis 2

1. Masukkan suku pertama `a`.
2. Masukkan beda `d`.
3. Masukkan banyak suku `n`.
4. Jika `n` kurang dari atau sama dengan 0, masukkan kembali nilai `n` sampai bernilai positif.
5. Atur nilai awal `total` menjadi 0.
6. Gunakan perulangan `for` sebanyak `n` kali.
7. Hitung nilai setiap suku.
8. Tambahkan setiap suku ke dalam `total`.
9. Tampilkan nomor dan nilai setiap suku.
10. Setelah perulangan selesai, tampilkan jumlah seluruh suku dengan dua angka di belakang koma.

## Pengujian

| Test Case |   a |   d |  n | Hasil Deret     | Jumlah |
| --------- | --: | --: | -: | --------------- | -----: |
| 1         |   2 |   3 |  5 | 2, 5, 8, 11, 14 |  40.00 |
| 2         |  10 |  -2 |  4 | 10, 8, 6, 4     |  28.00 |
| 3         | 1.5 | 0.5 |  3 | 1.5, 2.0, 2.5   |   6.00 |

## Refleksi

Salah satu kesalahan yang dapat terjadi pada perulangan `while` adalah kondisi perulangan tidak berubah sehingga program dapat terus berjalan. Kesalahan tersebut dapat diperbaiki dengan memastikan nilai yang digunakan pada kondisi `while` diperbarui sehingga kondisi akhirnya menjadi salah dan perulangan berhenti.