# Program Penyelesaian Sistem Persamaan Tiga Variabel

### Deskripsi
Program ini adalah sebuah alat untuk menyelesaikan sistem persamaan tiga variabel. Pengguna diminta untuk memasukkan koefisien dan konstanta dari tiga persamaan linear, dan program akan menghitung dan menampilkan solusi dari sistem persamaan tersebut.

### Cara Menggunakan
1. Jalankan program dengan menjalankan skrip Python `solve_equations.py`.
2. Ikuti panduan yang ditampilkan untuk memasukkan koefisien dan konstanta dari masing-masing persamaan.
3. Program akan menghitung determinan dan solusi sistem persamaan tiga variabel.
4. Hasilnya akan ditampilkan, termasuk persamaan-persamaan yang dimasukkan oleh pengguna dan nilai-nilai variabel x, y, dan z.

### Contoh Penggunaan
#### Input:
```yaml
Masukkan koefisien x pada persamaan 1 : 2
Masukkan koefisien y pada persamaan 1 : 3
Masukkan koefisien z pada persamaan 1 : 4
Masukkan konstanta   pada persamaan 1 : 10
--------------------------------------------
Masukkan koefisien x pada persamaan 2 : 4
Masukkan koefisien y pada persamaan 2 : -2
Masukkan koefisien z pada persamaan 2 : 6
Masukkan konstanta   pada persamaan 2 : 8
--------------------------------------------
Masukkan koefisien x pada persamaan 3 : 3
Masukkan koefisien y pada persamaan 3 : 2
Masukkan koefisien z pada persamaan 3 : -1
Masukkan konstanta   pada persamaan 3 : 5
--------------------------------------------
```
#### Output:
```yaml
Persamaan 1: 2x + 3y + 4z = 10
Persamaan 2: 4x - 2y + 6z = 8
Persamaan 3: 3x + 2y - z = 5

Nilai x: 1.0
Nilai y: 2.0
Nilai z: 3.0

Ingin Menghitung Ulang? (Y/N) : N

Terimakasih!
```

### Struktur Kode
- Fungsi `solve_equations`: Memproses input, menghitung determinan, dan menampilkan solusi.
- Fungsi `print_equation`: Menampilkan persamaan dengan format yang sesuai.
- Fungsi `print_term`: Menampilkan suku dalam persamaan dengan format yang sesuai.

### Keterangan
- Program menggunakan metode kofaktor dan aturan Cramer untuk menyelesaikan sistem persamaan tiga variabel.
- Apabila sistem persamaan memiliki banyak solusi atau tidak memiliki solusi, program memberikan informasi yang sesuai.

### Catatan
Pastikan Python telah terinstal di sistem Anda sebelum menjalankan program ini. Program ini ditulis dalam bahasa Python dan tidak memerlukan pustaka eksternal.
