# LRFM
## Analisis LRFM
Proyek ini bertujuan untuk menganalisis perilaku nasabah bank berdasarkan `Length`, `Recency`, `Frequency`, `Monetary`.
## Tujuan
Analisis ini dapat dimanfaatkan untuk:
- Strategi retensi pelanggan
- Kampanye pemasaran yang lebih personal
- Pengembangan program loyalitas
- Mengurangi resiko churn
## Data
Deskripsi kolom yang penting (diasumsikan):
- `customer_id` - ID unik untuk setiap nasabah
- `transaction_date` - Tanggal transaksi
- `amount` - Nilai transaksi dengan mata uang lokal
- `signup_date` - Tanggal nasabah bergabung
## Definisi LRFM
- `Length` - Mengukur durasi atau panjang hubungan antara pelanggan dan perusahaan
- `Recency` - Mengukur seberapa baru atau terkini transaksi terakhir
- `Frequency` - Mengukur seberapa sering pelanggan melakukan transaksi dalam periode waktu tertentu
- `Monetary` - Mengukur total nilai atau jumlah uang yang dihabiskan oleh pelanggan
## Menghitung LRFM
- `Length` - Tanggal analisis - tanggal transaksi pertama pelanggan
- `Recency` - Tanggal analisis - tanggal transaksi terakhir pelanggan
- `Frequency` - Jumlah transaksi pelanggan selama periode
- `Monetary` - Total nilai transaksi pelanggan selama periode
## Link Tableau Public:
[Tableau](https://public.tableau.com/app/profile/adrian.irsanda/viz/DashboardLRFM/DashboardLRFM)
