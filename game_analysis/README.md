## Deskripsi Proyek:
Pada proyek kali ini kita akan menentukan apakah suatu game bisa dikatakan berhasil atau tidak di wilayah atau market-market tertentu dan menentukan game mana yang paling berpotensi dalam penjualan. Adapun data yang akan dipakai adalah data penjualan lama dari tahun 2016. Data ini berisi nama game, platform yang dipakai, tahun rilis, genre, penilaian dari pengguna dan kritikus, dan juga berisi tentang rating dari ESRB.

## Data:
**Features**
- *Name*
- *Platform*
- *Year_of_Release* - tahun rilis
- *Genre*
- *NA_sales* - penjualan di Amerika Utara dalam satuan juta USD
- *EU_sales* - penjualan di Eropa dalam satuan juta USD
- *JP_sales* - penjualan di Jepang dalam satuan juta USD
- *Other_sales* - penjualan di negara lainnya dalam satuan juta USD
- *Critic_Score* - skor ulasan dari kritikus, maksimal 100
- *User_score* - skor ulasan dari pengguna, maksimal 10
- *Rating* - ESRB

## Tujuan:
- Menentukan pola apa saja yang menguntungkan dalam penjualan suatu game.
- Membuktikan beberapa hipotesis berikut:
  - Rata-rata rating pengguna platform Xbox One dan PC adalah sama.
  - Rata-rata rating pengguna genre Action dan Sports berbeda.

## Library yang Digunakan:
- pandas
- numpy
- matplotlib
- scipy
- seaborn
