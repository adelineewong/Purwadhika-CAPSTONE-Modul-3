## **E-commerce Customer Churn Analysis**

### **Deskripsi Project**

Proyek ini bertujuan untuk mengidentifikasi customer yang berpotensi churn (berhenti menggunakan layanan) di sebuah perusahaan e-commerce. Dengan tingkat churn sekitar 17%, penting bagi perusahaan untuk memahami faktor-faktor utama penyebab churn agar bisa merancang strategi retensi yang efektif dan efisien. Proyek ini menggunakan data historis customer untuk membangun model prediksi yang dapat membantu perusahaan dalam mencegah churn dengan menawarkan promosi atau diskon khusus hanya kepada customer yang berisiko tinggi.

### **Latar Belakang**
Dalam e-commerce dengan Customer Lifetime Value (CLV) yang tinggi, seperti penjualan elektronik atau barang mewah, kehilangan customer berpotensi merugikan perusahaan dalam jangka panjang. Mengingat biaya promosi yang signifikan, penting untuk mengarahkan upaya retensi pada customer yang paling berisiko berhenti, daripada mengalokasikan promosi ke semua customer.

Proyek ini berfokus pada membangun model klasifikasi yang dapat memprediksi customer yang berisiko churn dengan akurasi tinggi sehingga perusahaan dapat memaksimalkan efektivitas strategi retensi.

### **Tujuan Proyek**

1. Mengidentifikasi faktor-faktor utama yang mempengaruhi churn.
2. Mengembangkan model prediksi churn yang akurat.
3. Memberikan rekomendasi untuk mengoptimalkan alokasi biaya promosi dengan menargetkan customer yang benar-benar berisiko churn.
4. Meminimalkan churn dan meningkatkan retensi customer.

### **Pendekatan Analisis**
Analisis ini akan dimulai dengan eksplorasi data untuk menemukan pola-pola yang membedakan customer yang churn dan yang tidak. Berdasarkan pola tersebut, akan dibangun model Machine Learning untuk mengklasifikasikan customer yang berpotensi churn.

Model klasifikasi ini akan digunakan untuk memprediksi kemungkinan churn setiap customer, yang kemudian dapat membantu perusahaan dalam menargetkan customer berisiko dengan lebih tepat.

### **Metrik Evaluasi**

1. Precision: Mengukur seberapa akurat prediksi churn (meminimalkan false positives).
2. Recall: Fokus utama proyek ini, mengukur kemampuan model dalam mendeteksi customer yang benar-benar churn (meminimalkan false negatives).
3. F1-Score: Rata-rata harmonis antara precision dan recall.
4. ROC-AUC: Mengukur kemampuan model dalam memisahkan kelas churn dan tidak churn.

### **Fitur yang Digunakan**
1. Tenure: Lama waktu pelanggan berlangganan.
2. WarehouseToHome: Jarak antara gudang dan rumah pelanggan.
3. NumberOfDeviceRegistered: Jumlah perangkat yang terdaftar.
4. PreferedOrderCat: Kategori pesanan yang paling sering dipesan.
5. SatisfactionScore: Skor kepuasan pelanggan.
6. MaritalStatus: Status pernikahan pelanggan.
7. NumberOfAddress: Jumlah alamat yang ditambahkan.
8. Complaint: Keluhan yang diajukan dalam satu bulan terakhir.
9. DaySinceLastOrder: Hari sejak pesanan terakhir.
10. CashbackAmount: Rata-rata cashback yang diterima pelanggan.
11. Churn: Status churn (1: churn, 0: tidak churn).

### **Hasil & Kesimpulan**

Dari hasil evaluasi model, recall sebesar 79% berhasil dicapai, yang berarti 79% dari seluruh customer yang benar-benar churn berhasil terdeteksi. Simulasi biaya promosi menunjukkan bahwa model ini dapat membantu perusahaan menghemat 21,080 USD dalam biaya promosi sambil tetap menyelamatkan 79% customer berisiko. Meskipun ada beberapa false positives (customer yang tidak churn namun tetap menerima promosi), hal ini dapat ditoleransi mengingat CLV yang tinggi.

Kesimpulan dari proyek ini adalah penggunaan model prediksi churn lebih efisien dibandingkan menawarkan promosi ke semua customer, terutama pada e-commerce dengan CLV tinggi. Jika persentase churn meningkat secara signifikan (>50%), perusahaan mungkin perlu mempertimbangkan pendekatan yang lebih luas.

### **Rekomendasi**
Untuk meningkatkan performa model di masa depan:

1. **Pengujian A/B**: Menguji efektivitas strategi retensi yang diterapkan berdasarkan prediksi model melalui A/B testing.
2. **Penambahan Fitur**: Menambahkan fitur seperti frekuensi pembelian, program loyalitas, kategori produk yang dibeli, atau sumber referral yang bisa memberikan insight tambahan.
3. **Segmentasi Pelanggan**: Membagi pelanggan ke dalam segmen-segmen berdasarkan perilaku atau karakteristik demografis.
4. **Analisis Kesalahan**: Menganalisis kesalahan prediksi model (false positives dan false negatives) untuk memahami pola yang tidak terdeteksi.
5. **Monitoring Model**: Secara berkala melakukan re-evaluasi model untuk memastikan tetap relevan dan akurat dengan data terbaru.

Proyek ini menunjukkan bahwa dengan model prediksi churn yang tepat, perusahaan dapat lebih efisien dalam menargetkan customer berisiko dan memaksimalkan retensi customer.
