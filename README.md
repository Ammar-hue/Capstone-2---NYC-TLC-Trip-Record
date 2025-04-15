# Capstone 2 - NYC TLC Trip Record

## Latar Belakang

Perusahaan penyedia layanan taksi perlu memastikan armada mereka didistribusikan secara optimal untuk memenuhi permintaan pelanggan. Ketidakefisienan dalam pengaturan shift pengemudi dapat menyebabkan meningkatnya biaya operasional, waktu tunggu pelanggan yang lama, dan menurunnya kualitas layanan.

Berdasarkan data historis perjalanan taksi di New York City, diketahui bahwa lonjakan permintaan layanan terjadi secara dinamis tergantung pada waktu dan lokasi. Kondisi ini menjadi tantangan utama bagi perusahaan penyedia layanan taksi dalam mengoptimalkan armada dan jadwal pengemudi.

## Pernyataan Masalah

Perusahaan ingin mengetahui bagaimana karakteristik pola permintaan layanan taksi di Kota New York, khususnya berdasarkan dimensi waktu seperti jam, hari, dan minggu. Selain itu, perusahaan juga ingin memahami bagaimana sebaran dan distribusi permintaan layanan berdasarkan lokasi penjemputan dan penurunan.

Dengan memahami pola permintaan tersebut, perusahaan diharapkan dapat merumuskan strategi kebijakan dalam mengoptimalkan armada dan jadwal pengemudi berbasis data, yang mampu mendukung pengambilan keputusan secara lebih tepat. Kebijakan ini ditujukan dalam mengoptimalkan pengaturan armada dan jadwal pengemudi untuk efisiensi penempatan armada, meminimalisirkan waktu tunggu pelanggan yang lama, serta menekan biaya operasional terutama dalam upaya meminimalkan perjalanan kosong yang tidak menghasilkan pendapatan.


## Tujuan

1. Analisis ini dilakukan untuk mendukung perusahaan dalam merumuskan strategi pengaturan armada dan jadwal pengemudi yang lebih efektif dan efisien di Kota New York, dengan menggunakan data perjalanan taksi periode Januari 2023 sebagai dasar evaluasi dan perencanaan operasional untuk periode selanjutnya.

2. Memberikan rekomendasi dalam mengoptimalkan armada dan jadwal pengemudi berbasis pola historis perjalanan dengan mempertimbangkan penempatan armada, Pendapatan, Rute Perjalanan, Jarak Perjalanan, Risiko, dan Kualitas Layanan dalam meningkatkan perencanaan dan efisiensi operasional.


## Kesimpulan

Analisis ini dilakukan untuk mendukung perusahaan dalam merumuskan strategi pengaturan armada dan jadwal pengemudi yang lebih efektif dan efisien di Kota New York, dengan menggunakan data perjalanan taksi periode Januari 2023 sebagai dasar evaluasi dan perencanaan operasional untuk periode selanjutnya.

1. Pola Permintaan Berdasarkan Waktu
- Permintaan perjalanan tertinggi terjadi pada jam-jam sibuk, terutama antara pukul 16:00 - 20:00, yang berkaitan dengan aktivitas pulang kerja.
- Jam-jam sepi terjadi pada rentang pukul 00:00 - 05:00 dengan jumlah perjalanan yang jauh lebih rendah.
- Hari kerja (Senin-Jumat) memiliki volume perjalanan lebih stabil dibandingkan akhir pekan, namun akhir pekan menunjukkan adanya lonjakan di zona-zona tertentu yang berkaitan dengan aktivitas hiburan dan rekreasi.
- Hari tersibuk terjadi pada hari Jumat, sedangkan hari paling sepi umumnya adalah hari Minggu.
- Heatmap waktu menunjukkan konsistensi pola permintaan tinggi pada jam-jam tertentu (peak hours) di hampir semua hari, sementara pola sebaran perjalanan berdasarkan minggu (pickup_week) tidak menunjukkan fluktuasi signifikan karena data hanya mencakup 1 bulan observasi.

2. Pola Permintaan Berdasarkan Lokasi
- Zona penjemputan (pickup zone) tertinggi didominasi oleh area East Harlem North dan East Harlem South, menunjukkan area ini sebagai pusat aktivitas penjemputan taksi.
- Perbandingan pola permintaan pada jam sibuk dan jam sepi menunjukkan bahwa zona-zona pusat kota seperti Midtown, East Harlem, dan Downtown Brooklyn tetap aktif dalam kedua kondisi waktu tersebut.
- Zona penjemputan pada hari kerja didominasi oleh area perkantoran dan pusat aktivitas bisnis seperti Midtown Center, sedangkan pada akhir pekan terdapat peningkatan aktivitas di zona-zona dengan fungsi hiburan seperti Williamsburg dan Downtown Brooklyn.
- Heatmap berdasarkan hari dan zona menunjukkan bahwa zona-zona tertentu aktif secara konsisten sepanjang minggu, sementara beberapa zona hanya aktif di hari tertentu (misalnya akhir pekan saja).

3. Perbandingan Pickup dan Dropoff
- Terdapat ketidakseimbangan antara jumlah pickup dan dropoff di beberapa zona.
- Zona seperti Midtown Center memiliki dominasi sebagai zona penjemputan utama, sedangkan Upper East Side lebih dominan sebagai zona dropoff, mengindikasikan area hunian.
- Zona seperti Central Harlem North memiliki distribusi pickup dan dropoff yang seimbang, menunjukkan area transit dua arah.

4. Distribusi Perjalanan per Wilayah
- Mayoritas perjalanan terjadi di wilayah Manhattan, diikuti oleh Brooklyn dan Queens.
- Pola distribusi ini serupa baik di hari kerja maupun akhir pekan, meskipun pada akhir pekan ada peningkatan aktivitas di wilayah Brooklyn yang memiliki banyak area hiburan.

5. Total Pendapatan per Wilayah
- Pendapatan terbesar berasal dari wilayah Manhattan, mencerminkan intensitas aktivitas ekonomi dan tarif rata-rata perjalanan yang lebih tinggi.
- Brooklyn dan Queens berkontribusi secara signifikan namun masih jauh di bawah Manhattan.

6. Rasio Produktivitas Berdasarkan Zona
- Zona dengan rasio produktivitas tertinggi (jarak tempuh per menit perjalanan) berada di area pinggiran kota seperti Queens, Bronx, dan Staten Island. Hal ini menunjukkan bahwa perjalanan di area ini cenderung lebih jauh dengan waktu tempuh yang relatif singkat.
- Sebaliknya, zona dengan rasio produktivitas rendah berada di pusat kota seperti Midtown, yang padat aktivitas, rawan kemacetan, dan sering kali perjalanannya singkat karena jarak antar lokasi yang dekat.

7. Rata-rata Jarak Perjalanan
- Rata-rata jarak perjalanan terpendek terjadi pada jam-jam kerja (07:00 - 17:00), mencerminkan perjalanan jarak dekat dalam kota.
- Rata-rata jarak perjalanan meningkat pada malam hingga dini hari (00:00 - 05:00), mencerminkan perjalanan antar wilayah atau menuju bandara.

8. Kontribusi Pendapatan Berdasarkan Zona Penjemputan
- Zona-zona yang mendominasi jumlah perjalanan seperti East Harlem North dan East Harlem South juga memberikan kontribusi pendapatan yang besar.
- Namun, zona seperti Midtown Center tetap menjadi salah satu zona dengan kontribusi pendapatan tertinggi meskipun volumenya tidak setinggi zona East Harlem, karena jarak tempuh dan tarif dasar yang lebih tinggi di area pusat bisnis.

**Ringkasan**

Analisis terhadap data historis perjalanan taksi di New York City pada Januari 2023 mengungkap pola permintaan yang sangat dipengaruhi oleh waktu dan lokasi. Permintaan tertinggi terjadi pada hari kerja di jam 16:00–20:00, dengan konsentrasi zona penjemputan di Midtown Center, East Harlem, dan Downtown Brooklyn. Zona-zona ini menunjukkan kombinasi antara volume penumpang tinggi dan tarif rata-rata yang besar, menjadikannya pusat aktivitas utama layanan taksi.

Sebaliknya, permintaan menurun drastis pada pukul 00:00–05:00, terutama di zona pemukiman, namun tetap muncul kebutuhan layanan di area bandara. Akhir pekan menunjukkan pergeseran zona permintaan ke area hiburan dan wisata seperti Williamsburg dan Times Square, menandakan pentingnya fleksibilitas distribusi armada.

Selain itu, terdapat proporsi signifikan perjalanan dengan jarak tempuh pendek namun frekuensi tinggi di zona sentral Manhattan, serta perjalanan jarak jauh dari bandara ke pinggiran kota yang menghasilkan pendapatan tinggi. Beberapa zona juga teridentifikasi sebagai zona produktivitas rendah dengan waktu tunggu lama dan jumlah perjalanan rendah, berisiko menurunkan efisiensi armada jika tidak ditangani secara dinamis.



## Rekomendasi

**1. Pengaturan Shift Pengemudi Berbasis Permintaan**

- Gunakan pola waktu permintaan untuk membagi shift ke dalam 3 blok:

    - Pagi (06:00–14:00): permintaan stabil
    - Sore–Malam (14:00–22:00): puncak permintaan
    - Malam–Subuh (22:00–06:00): layanan terbatas, fokus bandara

- Shift fleksibel tambahan di jam sibuk (16:00–20:00) di zona Midtown dan Brooklyn.

**2. Distribusi Armada Berbasis Zona Produktivitas**

- Fokuskan armada di zona dengan rasio trip tinggi dan tarif rata-rata besar:

    - Midtown Center, East Harlem, Downtown Brooklyn.

- Hindari penumpukan armada di zona dengan rasio dropoff tinggi tapi pickup rendah seperti zona pemukiman (Upper East Side).

- Terapkan sistem redistribusi otomatis berdasarkan real-time demand (contoh: setelah dropoff di zona hunian → redirect ke pusat aktivitas).

**3. Pengelolaan Hari Kerja dan Akhir Pekan**

- Hari kerja: Dominasi permintaan di pusat bisnis dan perkantoran → distribusi armada fokus Manhattan tengah.

- Akhir pekan: Fokus ke zona hiburan (Chelsea, Williamsburg, Times Square), siapkan armada malam hari tambahan.

**4. Armada Khusus untuk Perjalanan Jarak Jauh dan Bandara**

- Tempatkan unit khusus di area:

    - Bandara JFK, LaGuardia, Newark (EWR).

- Waktu operasional armada bandara: 00:00–06:00 untuk antisipasi perjalanan pulang malam dan wisatawan.

**5. Optimalisasi Rute dan Efisiensi Perjalanan**

- Gunakan data perjalanan historis untuk merekomendasikan rute tercepat dan minim kemacetan di jam sibuk.

- Prioritaskan penggunaan rute alternatif di area rawan macet seperti Midtown dan Financial District.

**6. Sistem Monitoring Berbasis Data**

- Implementasikan dasbor pemantauan waktu nyata untuk:

    - Heatmap permintaan harian
    - Pergerakan armada
    - Waktu tunggu & rasio produktivitas per zona

Lakukan evaluasi rutin terhadap pola permintaan bulanan untuk menyesuaikan strategi jadwal pengemudi dan pengaturan armada secara adaptif.
