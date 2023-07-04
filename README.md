# UAS_PENGOLAHAN_CITRA_B-
praktikum terlampir di file parhan.ipynb data movil2.jpg

library yang digunakan pada project ini:

- imutils
- opencv
- numpy
- matplotlib
                                                             
penjelasan

masukkan library yang dibutuhkan lalu memasukkan variabel citra,mengubah citra dari BGR ke grayscale,
buat filter grayscale dan pengaplikasiannya bilateral-filter berfungsi untuk mengurangi noise pada citra dan agar tetap mempertahankan detail di tepi gambar, cv2.Canny berfungsi untuk membantu mendeteksi tepi gambar pada gambar yang telahdi upoad,selanjutnya mengambil kontur citra untuk crop plat nomor mobil,cv2.RETR_TREE berfungsi untuk mengambil semua kontur dengan hirarki lengkap
kontur menggunakan library imutils,mengurutkan kontur secara descending dan menggunakan looping pada bagian akhir memastikan citra edge dan biner apakah true atau tidak
