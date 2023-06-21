# Deskripsi Proyek:
Data ini diindeks sesuai dengan tanggal dan waktu perolehannya (fitur date). Terkait waktu, parameter yang letaknya bersebelahan umumnya bersifat mirip. Sebagian parameter tidak tersedia karena pengukuran dan/atau penghitungannya dilakukan jauh setelahnya. Itulah sebabnya, beberapa fitur yang ada di training set mungkin tidak ada di test set. Test set-nya pun juga tidak memuat target. Dataset sumber memuat training dan test set dengan semua fitur-fiturnya.
# Dataset:
Proses Teknologi:
- _Rougher feed_ - bahan mentah untuk proses flotasi.
- _Rougher addtions_ - reagen untuk flotasi: Xanthate, Sulphate, Depressant.
    - _Xanthate_ - penggerak atau aktivator flotasi
    - _Sulphate_ - natrium sulfida, khusus untuk proses ini.
    - _Depressant_ - natrium silikat.
- _Rougher process_ - flotasi.
- _Rougher tails_ - residu produk.
- _Float banks_ - unit flotasi.
- _Cleaner process_ - pemurnian.
- _Rougher Au_ - konsentrat emas yang lebih kasar.
- _Final Au_ - konsentrat emas akhir.

Parameter dari Tahap-Tahap yang Tersedia:
- _air amount_ - volume udara.
- _fluid levels_
- _feed size_ - ukuran partikel umpan.
- _feed rate_

# Library:
- _pandas_
- _matplotlib_
- _sklearn_
