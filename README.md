# PYTHON-5
# Fiona Puspitasari 

# Marketing Data ETL

Repositori ini memuat kelas Python yang bernama MarketingDataETL. Kelas ini dirancang untuk menjalankan proses ETL (Extract, Transform, Load) pada data pemasaran. Tugas utama kelas ini adalah mengekstrak informasi dari berkas CSV, melakukan transformasi data (bila perlu), dan menyimpan data yang telah diolah ke dalam sebuah berkas CSV baru.

## Fungsi

- Ekstraksi data dari berkas CSV : Digunakan untuk mengekstrak data dari sebuah berkas CSV.
- Transformasi data (belum diimplementasikan) : Tidak diimplementasikan di sini dan dapat diperluas sesuai kebutuhan untuk melakukan transformasi data.
- Store(output_file) : Penyimpanan data yang telah diproses ke dalam berkas CSV baru.

## Targeted Marketing ETL

Kelas TargetedMarketingETL adalah turunan dari kelas MarketingDataETL dan memiliki metode tambahan transform() yang di-override. Di dalam metode transform(), data dibersihkan dan diubah menjadi format yang sesuai. Selain itu, metode segment_customers() digunakan untuk mengelompokkan pelanggan berdasarkan jumlah pengeluaran dan kategori produk yang dibeli.

Pada blok kode terakhir, sebuah objek dari kelas TargetedMarketingETL dibuat dengan menyediakan nama berkas CSV sebagai argumen. Data diekstrak, diubah, dan kemudian disimpan ke dalam sebuah berkas baru dengan menggunakan metode yang sesuai.
