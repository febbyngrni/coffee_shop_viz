# Coffee Shop Executive Dashboard

PT Kopi Kenalan (KKn) adalah startup coffee shop yang berkembang pesat sejak awal 2023 dengan beberapa cabang di berbagai wilayah. Namun, pengelolaan data penjualan masih dilakukan secara manual, yang menyebabkan keterlambatan dalam pemantauan performa cabang, menghambat efisiensi operasional, serta mengurangi akurasi dalam pengambilan keputusan strategis.

Saat ini, Board of Directors (BoD) membutuhkan dashboard yang mampu memberikan wawasan real-time mengenai pencapaian revenue dan performa area manager, sehingga mereka dapat mengambil keputusan yang cepat dan berbasis data untuk memastikan target revenue setiap quarter dapat tercapai.

## Objectives
- Menyediakan dashboard interaktif yang memungkinkan Board of Directors untuk memantau progress revenue terhadap target quarter ini secara real-time.
- Mengidentifikasi cabang atau area manager yang performanya di bawah target, sehingga dapat diambil tindakan yang tepat waktu.

## Dashboard
![dashboard](https://github.com/user-attachments/assets/cb3c1ddc-c495-4ff7-a092-a4addf6f81dc)

Dashboard ini dibuat menggunakan Power BI dengan tujuan untuk melacak pencapaian revenue pada kuartal ini dan memastikan apakah target yang telah ditetapkan sebesar $420K dapat tercapai.

Melalui dashboard ini, Board of Directors (BoD) dapat:
- Memantau total revenue yang telah dihasilkan sejauh ini.
- Melihat sisa hari dalam kuartal ini untuk mengevaluasi waktu yang tersisa dalam mencapai target.
- Membandingkan revenue kuartal ini dengan kuartal sebelumnya untuk memahami tren pertumbuhan.
- Menampilkan forecast cumulative revenue hingga akhir kuartal berdasarkan tren historis.
- Mengidentifikasi area dan toko yang memerlukan dorongan tambahan untuk meningkatkan revenue dan mencapai target yang telah ditetapkan.

## Insights
Pada kuartal ini, Kopi Kenalan telah meraup revenue sebesar $326K, yang setara dengan 79.9% dari target revenue sebesar $420K. Masih tersisa 22 hari hingga akhir kuartal, atau 24% dari total hari dalam kuartal ini, sehingga masih ada waktu untuk mengejar sisa $94K agar target dapat tercapai.

Revenue yang dihasilkan pada current date adalah $3.6K, namun angka ini hanya mencapai 73.0% dari revenue pada hari yang sama di kuartal sebelumnya. Ini mengindikasikan adanya penurunan performa harian dibandingkan periode yang sama di kuartal lalu, yang dapat menjadi perhatian bagi manajemen untuk mengevaluasi penyebabnya.

### Revenue Forecast
![Screenshot (108)](https://github.com/user-attachments/assets/343097b0-339d-4b6d-abf3-cf30880f827d)

Berdasarkan cumulative revenue kuartal ini dibandingkan dengan kuartal sebelumnya, terlihat adanya peningkatan yang cukup signifikan. Grafik menunjukkan tren pertumbuhan yang lebih tinggi dibandingkan kuartal lalu, yang mengindikasikan bahwa Kopi Kenalan berada di jalur yang cukup baik untuk mencapai target revenue.

Kemudian untuk mendukung statement tersebut, forecast dilakukan menggunakan tiga skenario cumulative revenue: maksimum (max), median, dan minimum (min).
- **Skenario Max & Median** → Hasil forecast menunjukkan bahwa target revenue $420K kemungkinan besar dapat tercapai.
- **Skenario Min** → Jika revenue bergerak pada level minimum, Kopi Kenalan masih belum mencapai target di akhir kuartal.

Jika perusahaan ingin bermain aman dan memastikan pencapaian target, maka diperlukan strategi tambahan untuk meningkatkan performa revenue dalam sisa 22 hari ke depan.

### Revenue by Store Area
| Store Area      | Revenue This Quarter | Target per Area | % Achieved |
|-----------------|----------------------|-----------------|------------|
| Astoria         | $128,473.69          | $157,500.00     | -18.43%    |
| Hell's Kitchen  | $120,301.83          | $157,500.00     | -23.62%    |
| Lower Manhattan | $77,281.84           | $105,000.00     | -26.40%    |

Dari tiga store area (Astoria, Hell’s Kitchen, dan Lower Manhattan), ketiganya masih belum mencapai target revenue. Hal ini masih dapat dimaklumi karena masih ada 22 hari tersisa di kuartal ini untuk mengejar target.

Namun, Lower Manhattan menjadi area dengan pencapaian terendah, hanya mencapai -26.4% dari target yang ditetapkan. Jika ingin memastikan bahwa target revenue kuartal ini tercapai, maka perlu dilakukan peningkatan revenue terutama di store area dengan gap terbesar terhadap targetnya.

### Revenue by Store
![Screenshot (112)](https://github.com/user-attachments/assets/02060fd1-d1b4-432e-b231-780ac8213bf0)

Setiap store di tiga area (Astoria, Hell’s Kitchen, Lower Manhattan) memiliki target revenue sebesar $52.5K. Saat ini belum ada satu pun toko yang mencapai target tersebut.
- **Store dengan pencapaian terendah** → Manhattan Coffee di Lower Manhattan memiliki % achieved terendah (-34.5%), yang berarti perlu perhatian khusus untuk meningkatkan revenue.
- **Store dengan pencapaian terbaik** → Inferno Coffee di Hell’s Kitchen memiliki % achieved -9.5%, yang artinya sudah mendekati target dan berpotensi mencapainya lebih cepat.

## Conclusion
- Progress revenue saat ini sudah mencapai 79.9% dari target ($326K dari $420K), dengan sisa waktu 22 hari di kuartal ini untuk mengejar kekurangannya.
- Tren cummulative revenue menunjukkan peningkatan yang signifikan dibandingkan kuartal sebelumnya, yang berarti masih ada peluang besar untuk mencapai target.
- Forecast revenue dengan skenario median dan max menunjukkan target bisa tercapai, namun skenario minimum revenue masih belum mencapainya.
- Lower Manhattan memiliki % achieved revenue terendah (-26.4%) dibandingkan area lain, dengan Manhattan Coffee sebagai store dengan pencapaian paling rendah (-34.5%).
- Inferno Coffee di Hell’s Kitchen memiliki pencapaian terbaik (-9.5%) dan berpotensi mencapai target lebih cepat dibanding store lainnya.

## Recommendations
- Berikan insentif atau strategi promosi khusus untuk store dengan pencapaian revenue terendah, terutama Manhattan Coffee.
- Inferno Coffee hampir mencapai target, bisa dilakukan promo khusus atau insentif bagi karyawan untuk meningkatkan revenue dalam waktu singkat.
- Gunakan teknik upselling/cross-selling (contoh: bundling menu, diskon untuk pembelian dalam jumlah tertentu).
- Pantau daily revenue lebih ketat untuk memastikan tren tetap positif.
- Jika daily revenue tetap lebih rendah dibanding kuartal lalu, perlu dilakukan intervensi cepat, seperti promosi harian atau strategi harga yang lebih kompetitif.
- Campaign berbasis urgency seperti diskon terbatas menjelang akhir kuartal.
