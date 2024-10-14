# Telco-Company Customer Churn Analysis

## Project Overview
Proyek ini bertujuan untuk mengatasi churn pelanggan di DQLab Telco, sebuah perusahaan telekomunikasi yang sedang berkembang pesat dan didirikan pada tahun 2019. Meskipun berkomitmen untuk meningkatkan pengalaman pelanggan, DQLab Telco menghadapi tantangan signifikan dengan pelanggan yang beralih ke kompetitor. Untuk mengurangi churn, manajemen memutuskan untuk memanfaatkan teknik machine learning untuk analisis prediktif.

Proyek ini terdiri dari beberapa fase kunci:
- Exploratory Data Analysis (EDA): Menganalisis data pelanggan untuk mengungkap pola, tren, dan wawasan yang mempengaruhi perilaku churn.

- Data Preprocessing: Membersihkan dan mempersiapkan dataset dari bulan Juni 2020 untuk memastikan kualitas dan keandalan sebelum pemodelan.

- Machine Learning Modelling: Mengembangkan berbagai model machine learning untuk memprediksi churn pelanggan, menggunakan algoritma yang sesuai untuk menilai efektivitasnya.

- Model Evaluation: Membandingkan kinerja model untuk mengidentifikasi model yang paling akurat dan andal dalam memprediksi churn pelanggan.

Hasil dari proyek ini akan memberikan wawasan berharga dan strategi yang dapat diambil untuk mengurangi churn pelanggan, sehingga meningkatkan retensi pelanggan dan meningkatkan kinerja bisnis secara keseluruhan.

## Kesimpulan

Berdasarkan pemodelan yang telah dilakukan dengan menggunakan Logistic Regression, Random Forest dan Extreme Gradiant Boost, maka dapat disimpulkan untuk memprediksi churn dari pelanggan telco dengan menggunakan dataset ini model terbaiknya adalah menggunakan algortima Logistic Regression. Hal ini dikarenakan performa dari model Logistic Regression cenderung mampu memprediksi sama baiknya di fase training maupun testing (akurasi training 80%, akurasi testing 79%), dilain sisi algoritma lainnya cenderung Over-Fitting performanya. Akan tetapi hal ini tidak menjadikan kita untuk menarik kesimpulan bahwsannya jika untuk melakukan pemodelan apapun maka digunakan Logistic Regression, kita tetap harus melakukan banyak percobaan model untuk menentukan mana yang terbaik.

# Rekomendasi Bisnis untuk Mengatasi Permasalahan Churn:

- Fokus pada Retensi Pelanggan Baru (Tenure Rendah):
Pelanggan dengan tenure rendah (baru berlangganan) cenderung lebih tinggi untuk churn. Program onboarding yang lebih baik, penawaran paket khusus, dan interaksi pelanggan di awal masa langganan bisa membantu meningkatkan retensi.

- Penawaran Khusus untuk Pelanggan dengan Biaya Bulanan Tinggi:
Berikan insentif atau diskon kepada pelanggan dengan biaya bulanan tinggi. Mereka cenderung churn, sehingga diskon, upgrade paket, atau program loyalitas bisa meningkatkan kepuasan mereka.

- Tingkatkan Kualitas Layanan Internet:
Karena InternetService berperan dalam churn, analisis lebih lanjut diperlukan untuk menentukan apakah kualitas layanan, kecepatan internet, atau harga paket mempengaruhi churn. Menyediakan layanan yang lebih handal atau paket yang lebih fleksibel mungkin bisa mengurangi churn.

- Ubah Kebijakan Paperless Billing:
Menawarkan opsi untuk kembali ke metode pembayaran tradisional bagi pelanggan yang merasa tidak nyaman dengan penagihan tanpa kertas dapat membantu mengurangi churn, terutama untuk pelanggan yang kurang teknis.

- Perhatikan Segmen Pelanggan Senior:
Pelanggan senior menunjukkan kecenderungan churn yang lebih tinggi. Kampanye yang lebih personal, layanan pelanggan yang responsif, atau paket yang sesuai untuk kebutuhan pelanggan senior dapat membantu meningkatkan loyalitas mereka.

- Intervensi Dini untuk Pelanggan dengan Riwayat Pembayaran yang Berfluktuasi:
Pelanggan dengan TotalCharges yang lebih rendah atau berfluktuasi menunjukkan risiko churn yang lebih besar. Analisis lebih dalam terhadap pola pembayaran mereka, dan program dukungan seperti fleksibilitas pembayaran atau program loyalitas untuk mengurangi churn.

- Pengujian A/B dan Kampanye Terfokus:
Uji beberapa strategi retensi, seperti diskon, peningkatan layanan, atau penawaran khusus melalui kampanye yang ditargetkan kepada pelanggan dengan risiko churn yang lebih tinggi. Gunakan hasil untuk mengukur efektivitas setiap strategi.