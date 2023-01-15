# An Airline Customer Value Analysis
Data pelanggan maskapai penerbangan digunakan untuk mengklasifikasikan pelanggan, menganalisis karakteristik kategori pelanggan yang berbeda, membandingkan nilai pelanggan dari kategori pelanggan yang berbeda, memberikan layanan yang dipersonalisasi ke kategori pelanggan dengan nilai yang berbeda, dan merumuskan strategi pemasaran yang sesuai.

## Deskripsi data:
Data ini berisi informasi dasar, informasi penerbangan dan informasi titik dari 62.988 pelanggan. Ini berisi nomor kartu anggota, waktu keanggotaan, jenis kelamin, usia, level kartu anggota, dan jarak tempuh di jendela observasi. 44 atribut karakteristik seperti jumlah dan waktu penerbangan.

## Insight K-Means Inertia
1. Cluster 0 (Mid-low level customer) :
- Durasi bergabung middle level
- Interval waktu penerbangan terakhir hingga pesanan penerbangan terakhir low level
- Jumlah penerbangan pelanggan middle level
- Total jarak (km) penerbangan yang telah dilakukan middle level
- Rata-rata diskon yang didapatkan pelanggan mid-Low level
- Total member cluster 0 middle level
2. Cluster 1 (High level customer) :
- Durasi bergabung high level
- Waktu penerbangan terakhir hingga interval pesanan penerbangan terakhir high level
- Jumlah penerbangan pelanggan mid-Low level
- Total jarak (km) penerbangan yang telah dilakukan mid-Low level
- Rata-rata diskon yang didapatkan pelanggan high level
- Total member cluster 1 mid-Low level
3. Cluster 2 (Middle level customer) :
- Durasi bergabung Mid-Low level
- Waktu penerbangan terakhir hingga interval pesanan penerbangan terakhir Mid-Low level
- Jumlah penerbangan pelanggan high level
- Total jarak (km) penerbangan yang telah dilakukan High level
- Rata-rata diskon yang didapatkan pelanggan Middle level
- Total member cluster 2 high level
4. Cluster 3 (Low level customer) :
- Durasi bergabung low level
- Waktu penerbangan terakhir hingga interval pesanan penerbangan terakhir low level
- Jumlah penerbangan pelanggan low level
- Total jarak (km) penerbangan yang telah dilakukan low level
- Rata-rata diskon yang didapatkan pelanggan low level
- Total member cluster 3 low level

## Insight K-Means Silhouette Score
1. Cluster 0 (High level customer) :
- Durasi bergabung high level
- Waktu penerbangan terakhir hingga interval pesanan penerbangan terakhir high level
- Jumlah penerbangan pelanggan high level
- Total jarak (km) penerbangan yang telah dilakukan high level
- Rata-rata diskon yang didapatkan pelanggan high level
- Total member cluster 0 high level
2. Cluster 1 (Low level customer) :
- Durasi bergabung low level
- Waktu penerbangan terakhir hingga interval pesanan penerbangan terakhir low level
- Jumlah penerbangan pelanggan low level
- Total jarak (km) penerbangan yang telah dilakukan low level, pada cluster 1 tidak terlalu jauh dari cluster 0
- Rata-rata diskon yang didapatkan pelanggan low level
- Total member cluster 1 low level
