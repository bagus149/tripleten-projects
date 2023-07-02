# Deskripsi Proyek
Terdapat perusahaan jual beli mobil bekas yang sedang mengembangkan sebuah aplikasi untuk menarik pembeli baru. Dalam aplikasi tersebut, Anda bisa dengan cepat mengetahui nilai pasar mobil Anda. Anda memiliki akses ke data historis, spesifikasi teknis kendaraan, versi model endaraan, dan harga kendaraan.
Perusahaan ini tertarik pada:
- kualitas prediksi
- kecepatan prediksi
- waktu yang diperlukan untuk melatih model

# Dataset
Fitur:
- _DateCrawled_ — tanggal ketika profil diunduh dari database
- _VehicleType_ — jenis bodi kendaraan
- _RegistrationYear_ — tahun registrasi kendaraan
- _Gearbox_ — jenis transmisi
- _Power_ — daya (hp)
- _Model_ — model kendaraan
- _Mileage_ — jarak tempuh (diukur dalam satuan km berdasarkan dataset regional tertentu)
- _RegistrationMonth_ — bulan registrasi kendaraan
- _FuelType_ — jenis bahan bakar
- _Brand_ — merek kendaraan
- _NotRepaired_ — apakah kendaraan pernah direparasi sebelumnya
- _DateCreated_ — tanggal pembuatan profil
- _NumberOfPictures_ — jumlah gambar kendaraan
- _PostalCode_ — kode pos pemilik profil (pengguna)
- _LastSeen_ — tanggal aktivitas terakhir pengguna
Target:
- _Price_ — harga (dalam satuan Euro)

# Library
- pandas
- matplotlib
- seaborn
- sklearn
- catboost
- lightgbm
- xgboost
