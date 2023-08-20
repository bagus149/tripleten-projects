## Deskripsi Proyek
Anda bekerja sebagai seorang analis untuk Zuber, sebuah perusahaan berbagi tumpangan (ride-sharing) baru yang diluncurkan di Chicago. Tugas Anda adalah untuk menemukan pola pada informasi yang tersedia. Anda ingin memahami preferensi penumpang dan dampak faktor eksternal terhadap perjalanan. Dengan menggunakan basis data, Anda akan menganalisis data dari kompetitor dan menguji hipotesis terkait pengaruh cuaca terhadap frekuensi perjalanan.

## Data
Basis data yang memuat informasi perjalanan taksi di Chicago:
Tabel `neighborhoods`: data terkait wilayah di kota Chicago

- _name_: nama wilayah
- _neighborhood_id_: kode wilayah

Tabel `cabs`: data terkait taksi

- _cab_id_: kode kendaraan
- _vehicle_id_: ID teknis kendaraan
- _company_name_: nama perusahaan yang memiliki kendaraan

Tabel `trips`: data terkait perjalanan

- _trip_id_: kode perjalanan
- _cab_id_: kode kendaraan yang beroperasi
- _start_ts_: tanggal dan waktu perjalanan dimulai (waktu dibulatkan dalam satuan jam)
- _end_ts_: tanggal dan waktu perjalanan berakhir (waktu dibulatkan dalam satuan jam)
- _duration_seconds_: durasi perjalanan dalam satuan detik
- _distance_miles_: jarak perjalanan dalam satuan mil
- _pickup_location_id_: kode wilayah penjemputan
- _dropoff_location_id_: kode wilayah pengantaran

Tabel `weather_records`: data terkait cuaca

- _record_id_: kode catatan cuaca
- _ts_: tanggal dan waktu saat pencatatan cuaca dilakukan (waktu dibulatkan dalam satuan jam)
- _temperature_: suhu saat pencatatan cuaca dilakukan
- _description_: deskripsi singkat tentang kondisi cuaca, seperti "light rain" (hujan ringan) atau "scattered clouds" (berawan)

## Libraries
- _pandas_
- _requests_
- _BeautifulSoup_
- _matplotlib_
- _numpy_
- _scipy_
- _seaborn_
