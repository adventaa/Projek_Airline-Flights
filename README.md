# ✈️ Passenger Segmentation on Airline Flights Using K-Means Clustering
Proyek ini bertujuan untuk melakukan segmentasi penumpang pesawat berdasarkan pola perjalanan dan karakteristik tiket dari berbagai maskapai menggunakan algoritma K-Means Clustering. Dengan menganalisis fitur-fitur dalam dataset, kemudian mengelompokkan penumpang ke dalam kelompok dengan karakteristik berbeda.

---
# 📁 Dataset
- Kaggle: https://www.kaggle.com/datasets/rohitgrewal/airlines-flights-data
- Jumlah data: 300.152 dan 11 kolom
---
# 🔎 Tujuan
Tujuan utamanya adalah untuk memahami pola antar maskapai serta membantu maskapai dan agen perjalanan dalam menyusun strategi yang lebih tepat sasaran sesuai segmen pelanggan.

---
# ⚙️ Tools & Library
- Python (data processing: Pandas, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook
- Model: K-Means Clustering
---
# 🗹 Step
Menerapkan Knowledge Discovery in Databases (KDD) methodology:
- Data Cleaning (cek missing value, duplicate data)
- Data Integration
- Data Selection
- Data Transformation (encode data, transformation data)
- Data Mining
- Pattern Evaluation
- Knowledge Presentation
---
# ✔️ Hasil
- Menggunakan Elbow Method untuk  menentukan jumlah klaster (K) yang optimal sebelum melakukan pemodelan. Hasilnya terlihat titik elbow atau tekukan berada pada k=3. Setelah k=3 terjadi penurunan nilai inertia mulai melambat, yang menandakan bahwa penambahan jumlah klaster setelah titik tersebut hanya memberikan sedikit peningkatan (tidak efisien).
# 📌 Kesimpulan
- Cluster 0 adalah penumpang dengan tiket keberangkatan menggunakan kelas ekonomi, dengan mayoritas rute memiliki 1 pemberhentian. Umumnya membeli tiket lebih awal dengan keberangkatan pada dini hari (early morning) dan tiba di kota tujuan pada malam hari. Harga tiket pada cluster ini dimulai dari harga yang paling murah dengan rata-rata durasi perjalanan terpendek dibandingan dengan cluster lainnya. Kota asal terbanyak berasal dari Banglore dan kota tujuan paling dominan yaitu Mumbai. Cluster ini menggambarkan penumpang yang sangat memperhatikan harga tiket, merencanakan perjalanan jauh-jauh hari, dan memilih keberangkatan lebih awal untuk sampai di kota tujuan.
- Cluster 1  adalah penumpang dengan tiket keberangkatan menggunakan kelas bisnis, dengan mayoritas keberangkatan di pagi hari dan sampai di kota tujuan pada malam hari. Mereka membayar tiket dengan harga tinggi dibandingkan dengan cluster lain dan memiliki rata-rata durasi perjalanan sedang. Rute yang dilalui mayoritas berada di kota-kota besar, seperti Mumbai, Delhi, dan Banglore. Cluster ini menggambarkan pelanggan dengan kelas atas atau bekerja sebagai pebisnis yang memprioritaskan kenyamanan, fleksibilitas waktu, dan efisien dalam berpergian, yang dibuktikan dari kelas tiket adalah kelas bisnis, harga tiket paling tinggi, hanya menggunakan maskapai yang memiliki kelas bisnis.
- Cluster 2 adalah penumpang dengan tiket keberangkatan menggunakan kelas ekonomi dengan harga rata-rata tiket menengah dan memiliki rata-rata durasi penerbangan paling panjang di antara seluruh cluster. Penumpang pada cluster ini paling banyak memilih waktu keberangkatan di pagi hari dan tiba di malam hari. Kota asal dominan adalah Mumbai dan kota tujuan utama ke Banglore dan Chennai. Cluster ini menggambarkan penumpang ekonomi pada rute-rute populer dengan tetap memperhatikan harga dan kenyamanan perjalanan.
- Berdasarkan hasil pengelompokkan dari seluruh data penumpang, dapat disimpulkan bahwa maskapai yang sering digunakan untuk berpergian antar kota-kota di India yaitu menggunakan maskapai Vistara dan Air_India, yang berarti kedua maskapai tersebut telah dipercayai oleh masyarakat.
---
# ✨ Rekomendasi
- Memberikan potongan harga atau cashback untuk pesanan 30+ hari sebelum keberangkatan, memberikan tambahan kapasitas penerbangan pada mayoritas keberangakatan early morning, menawarkan paket hemat perjalanan kepada penumpang cluster 0.
- Memberikan layanan premium, seperti prioritas boarding, akses lounge di bandara, dan fasilitas tambahan saat penerbangan. Menawarkan paket bisnis atau program keanggotaan loyalitas (membership) untuk meningkatkan kepercayaan dan kenyamanan kepada penumpang cluster 1.
- Memberikan promosi paket bundling atau paket liburan keluarga, memberikan promo harga dengan jam keberangkatan pagi dan tanpa transit, memberikan tambahan penerbangan di keberangkatan pagi atau siang kepada penumpang cluster 2.
- Meningkatkan layanan di bandara saat jam sibuk (rush hour), seperti menyediakan area tunggu tambahan, jalur cepat (fast track), atau tambahan petugas pelayanan  agar dapat meningkatkan kenyamanan dan efisiensi layanan bagi seluruh penumpang.
- Meningkatkan keamanan tambahan pada malam hari di setiap bandara, terutama untuk area kedatangan dan transportasi lanjutan dikarenakan mayoritas kedatangan berada di malam hari. Sedangkan di pagi hari, bandara perlu menyiapkan proses boarding dan take-off secara efisien karena tingginya jumlah keberangkatan.
- Menjalin kerja sama promosi dengan agen perjalanan atau online travel agent pada maskapai yang dominan seperti Vistara dan Air_India, agar dapat menyusun strategi untuk promo eksklusif atau penawaran bundling.
- Untuk maskapai Indigo, AirAsia, GO_FIRST, dan SpiceJet disarankan untuk fokus pada penumpang ekonomi pada penumpang cluster 0 dan 2 dengan startegi harga hemat dan bundling.


