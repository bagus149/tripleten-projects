## Deskripsi Proyek:
Ptojek kali ini adalah tentang paket yang ditawarkan oleh suatu perusahaan. Paket yang ditawarkan ada dua yaitu paket Ultimate dan paket Surf. Masing-masing paket memiliki keunggulannya masing-masing sesuai dengan kebutuhan pengguna. Data pengguna terdiri dari 500 yang diambil di tahun 2018. Adapun tujuan projek kali ini adalah:
- Menganalisis prilaku pengguna dalam memilih paket.
- Menganalisis paket mana yang paling menguntungkan.
- Menganalisis pendapatan paket Ultimate dan Surf.
- Menganalisis pendapatan dari beberapa kota.

## Data:

### Tabel *users*:
- *user_id* - pengguna
- *firs_name* - nama depan pengguna
- *last_name* - nama belakang pengguna
- *age* - usia pengguna
- *reg_date* - tanggal mulai berlangganan
- *churn_date* - tanggal pengguna berhenti layanan
- *city* - kota tempat tinggal pengguna
- *plan* - nama paket telpon

### Tabel *calls*:
- *id* - ID sesi telpon unik
- *call_date* - tanggal panggilan
- *duration* - durasi pangglan dalam menit
- *user_id* - ID pengguna yang melakukan panggilan

### Tabel *messages*:
- *id* - ID SMS unik
- *message_date* - tanggal SMS dikirim
- *user_id* - ID pengguna yang mengirim SMS

### Tabel *internet*:
- *id* - ID sesi web unik
- *mb_used* - volume data yang dihabiskan dalam sesi
- *session_date* - tanggal sesi web
- *user_id* - ID pengguna

### Tabel *plans*:
- *plan_name* - nama paket telpon
- *usd_monthly_fee* - biaya bulanan dalam dolar AS
- *minutes_included* - alokasi menit panggilan bulanan
- *messages_included* - alokasi SMS bulanan
- *mb_per_month_included* - alokasi volume data bulanan
- *usd_per_minute* - harga per menit jika sudah melebihi batas paket
- *usd_per_message* - harga per SMS jika sudah melebihi batas paket
- *usd_per_gb* - harga per ekstra gigabita jika sudah melebihi batas paket

## Target:
- Uji hipotesis Rata-rata pendapatan dari pengguna paket telepon Ultimate dan Surf berbeda.
- Uji hipotesis Rata-rata pendapatan dari pengguna di wilayah NY-NJ berbeda dengan pendapatan pengguna dari wilayah lain.

## Library yang digunakan:
- *pandas*
- *numpy*
- *scipy*
- *matplotlib*
