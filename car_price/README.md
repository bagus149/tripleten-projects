# Deskripsi Proyek
Terdapat perusahaan jual beli mobil bekas yang sedang mengembangkan sebuah aplikasi untuk menarik pembeli baru. Dalam aplikasi tersebut, Anda bisa dengan cepat mengetahui nilai pasar mobil Anda. Anda memiliki akses ke data historis, spesifikasi teknis kendaraan, versi model endaraan, dan harga kendaraan.
Perusahaan ini tertarik pada:
- kualitas prediksi
- kecepatan prediksi
- waktu yang diperlukan untuk melatih model

# Dataset
Fitur:
- DateCrawled — tanggal ketika profil diunduh dari database
- VehicleType — jenis bodi kendaraan
- RegistrationYear — tahun registrasi kendaraan
- Gearbox — jenis transmisi
- Power — daya (hp)
- Model — model kendaraan
- Mileage — jarak tempuh (diukur dalam satuan km berdasarkan dataset regional tertentu)
- RegistrationMonth — bulan registrasi kendaraan
- FuelType — jenis bahan bakar
- Brand — merek kendaraan
- NotRepaired — apakah kendaraan pernah direparasi sebelumnya
- DateCreated — tanggal pembuatan profil
- NumberOfPictures — jumlah gambar kendaraan
- PostalCode — kode pos pemilik profil (pengguna)
- LastSeen — tanggal aktivitas terakhir pengguna
Target:
- Price — harga (dalam satuan Euro)

# Library
- pandas
- matplotlib
- seaborn
- sklearn
- catboost
- lightgbm
- xgboost
