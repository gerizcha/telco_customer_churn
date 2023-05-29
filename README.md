# Background

## Theory 

`Customer Lifecycle` atau siklus pelanggan terdiri dari 5 tahapan: <br>

> **1. Awareness** <br>
> **2. Acquisition** <br>
> **3. Engagement** <br>
> **4. Retention** <br>
> **5. Loyalty** <br>

Tahapan itu merepresentasikan bagaimana *customer* atau pelanggan bermula dari mengetahui produk atau jasa perusahaan sampai menjadi pelanggan yang sangat setia. <br>
<br>
1. Mengetahui `(Awareness)` adalah permulaan dari segalanya. Perusahaan pasti memiliki strategi pemasaran yang dapat menjangkau target marketnya.<br><br>
2. Saat target mengetahui produk/jasa perusahaan dan tertarik untuk melakukan *purchase*, orang tersebut akan terkonversi menjadi pelanggan perusahaan `(Acquisition)` <br><br>
3. Selanjutnya, perusahaan akan menjaga relasi dengan pelanggan dengan menerapkan CRM management seperti mengirimkan *newsletter* bulanan, memberikan promosi di hari ulang tahun pelanggan, mengirimkan *push notification* secara berkala, dan lainnya. Hal-hal tersebut bertujuan untuk mengondisikan pelanggan untuk selalu ingat dan merasa dekat dengan perusahaan `(Engagement)`. <br><br>
4. Kemudian, perusahaan akan selalu berusaha mengetahui apa yang pelanggan butuhkan dengan meminta umpan balik atau *feedback* dari pelanggan dengan pengisian survey atau sarana komplain seperti *Customer Service*, *email help support*, diskon, dsb. Tujuannya adalah agar pelanggan kembali menggunakan produk/jasa perusahaan secara kontinu atau yang biasanya disebut *repeat order* `(Retention)`.<br><br>
5. Pelanggan yang puas dengan produk/jasa perusahaan dan selalu melakukan *repeat order* adalah aset yang sangat berharga bagi perusahaan. Secara emosional, pelanggan selalu merasa bahwa produk/jasa perusahaan berhasil memenuhi kebutuhannya. Pelanggan setia bahkan bisa saja merekomendasikan produk/jasa perusahaan kepada orang lain secara cuma-cuma. `(Loyalty)`.<br>

Seperti *quote* yang sering dikumandangkan: <br>
<br>
`"It costs many times more to acquire a new customer than to retain an existing one"`

Pelanggan yang berhenti menggunakan produk/jasa perusahaan disebut dengan istilah **CHURN**. Pastinya, hal ini sangat tidak diinginkan oleh perusahaan. Pelanggan yang *churn* otomatis akan berhenti juga berkontribusi terhadap pendapatan atau *revenue* perusahaan. Hal tersebut berpotensi mengakibatkan penurunan profit perusahaan.

## Real Case

PT Telco Connect adalah salah satu perusahaan yang menyediakan beragam layanan jasa yang berbasis internet, mulai dari *Internet Service, Online Security, Online Backup, Device Protection, dan Technical Support*. Saat ini perusahaan sedang berfokus pada angka `CHURN` karena angka persentase Churn konsisten meningkat dalam 12 bulan terakhir. <br> <br>

Masalah ini harus segera ditindaklanjuti karena semakin banyak atau semakin besar persentase pelanggan user yang *churn* akan semakin mengurangi pendapatan atau *revenue* perusahaan. Terlebih lagi, apabila perusahaan tidak cukup berhasil mendapatkan pelanggan baru yang dapat menutupi hilangnya pelanggan lama. Akan tetapi, kembali lagi, mendapatkan pelanggan baru menghabiskan biaya (cost) yang berkali-kali lipat lebih besar perusahaan dibandingkan mempertahankan pelanggan lama. Sehingga, meminimalisasi pelanggan lama dan mencegah *Churn* adalah fokus yang tepat bagi perusahaan PT Telco Connect.

PT Telco Connect memiliki sejumlah dana yang selalu dialokasikan setiap bulan untuk `Customer Retention`. Customer retention adalah kemampuan perusahaan untuk membuat pelanggan kembali membeli atau menggunakan layanannya. Pihak management perusahaan ingin memastikan bahwa dana ini digunakan secara optimal dan tepat sasaran. **Kasus ini menjadi sangat penting karena jika tidak ada implementasi strategi yang tepat sasaran untuk mencegah pelanggan yang berpotensi Churn, akan semakin banyak pelanggan yang berhenti menggunakan layanan yang mengakibatkan berkurangnya pendapatan perusahaan dari pelanggan-pelanggan tersebut.**

### Questions
> 1. Bagaimana profil umum pelanggan berdasarkan data secara keseluruhan? <br>
> 1. Bagaimana profil pelanggan berdasarkan kecenderungannya untuk *churn*? <br>
> 1. Berapa kerugian perusahaan karena pelanggan yang *Churn*? <br>
> 1. Bagaimana pembuatan model *maching learning* terbaik yang dapat digunakan dalam kasus ini? <br>
> 1. Bagaimana akurasi dan limitasi dari model tersebut? <br>
> 1. Apa saja solusi *(actionable recommendations)* yang dapat dilakukan perusahaan untuk mencegah pelanggan *Churn*? <br>
> 1. Apa dampak dari solusi tersebut terhadap bisnis perusahaan?<br>
> 1. Apa saja rekomendasi untuk meningkatkan *project* agar lebih baik lagi? <br>

### Goals 
- Mendapatkan prediktor pelanggan yang berpotensi *Churn* seakurat mungkin
- Mendapatkan pelanggan-pelanggan yang tepat sasaran untuk dilakukan pencegahan *Churn*
- Menentukan solusi dan strategi yang tepat untuk mencegah pelanggan untuk *Churn*
- Mengetahui dampak dari solusi terhadap PT Telco Connect secara terukur

<br>

# Key Takeaways and Conclusion

Mayoritas pelanggan tidak memiliki tanggungan. Pelanggan lebih memilih paket bulanan *(Month to Month)* dibandingkan paket jangka lama seperti satu tahun maupun dua tahun. Pelanggan juga lebih banyak yang memilih Paperless Billing dibandingkan tagihan cetak. Layanan internet yang paling banyak diminati adalah Fiber Optic, tetapi tidak jauh berbeda dengan DSL. Mayoritas pelanggan tidak memanfaatkan fasilitas layanan Online Security, Online Back Up, Device Protection, dan Tech Support.

Terkait kecenderungan untuk *Churn*, pelanggan yang tidak memiliki tanggungan justru Churn lebih banyak daripada yang memiliki tanggungan.
Pelanggan yang menggunakan layanan internet dengan Fiber Optic lebih banyak yang Churn daripada yang menggunakan DSL maupun yang tidak menggunakan layanan internet sama sekali. Pelanggan dengan paket bulanan *(month-to-month)* signifikan Churn lebih banyak dibandingkan paket tahunan maupun paket 2 tahun. Pelanggan yang menggunakan Paperless Billing lebih banyak yang Churn daripada yang non-Paperless Billing. Pelanggan yang tidak menggunakan fasilitas layanan Online Security, Online Back Up, Device Protection, dan Tech Support lebih banyak yang Churn dibandingkan dengan pelanggan yang menggunakan layanan tersebut.

Dalam kasus ini, pelanggan yang berhenti menggunakan layanan mengakibatkan perusahaan mengalami kerugian mencapai 30% dari total pendapatan atau setara dengan 96 ribu dollar.

Model machine learning yang digunakan adalah klasifikasi, karena target yang ingin dicari berupa label yaitu *Churn* dan *tidak Churn*. Pembuatan machine learning akan dijabarkan, sebagai berikut:
- Preprocessing data dengan pengecekan *missing value*, menghapus data duplikat, penyesuaian format tipe data, dan merapikan isi data observasi yang ambigu. 
- Pengecekan distribusi data target dan menemukan bahwa dataset tidak seimbang dengan data non-Churn tiga kali lipat lebih banyak dibandingkan data Churn.
- Features selection dengan menggunakan fitur numerikal terlebih dahulu kemudian menggunakan seluruh fitur kategorikal juga. 
- Feature engineering yang digunakan adalah One-Hot Encoding pada fitur kategorikal dan MinMax Scaler pada fitur numerikal. 
- Membuat model tahap pertama dengan menggunakan fitur numerikal saja yaitu durasi berlangganan dan nominal tagihan bulanan (Tenure dan MonthlyCharges) tetapi hasil model belum ada yang cukup baik dan reliabel untuk digunakan.
- Membuat model tahap kedua dengan menggunakan semua fitur termasuk kategorikal (Dependants, InternetService, DeviceProtection, dll) tetapi masih belum ada model yang cukup baik dan reliabel untuk digunakan.
- Model yang diuji coba antara lain Logistic Regression, KNN, Decision Tree, SVM, dan Random Forest.
- Hyperparameter tuning dan cross validation dilakukan dalam pemodelan ini.
- Evaluasi yang digunakan adalah Confusion Matrix yang berfokus pada skor Recall karena pada kasus ini FN (False Negative) adalah yang kritikal. False Negative adalah pelanggan yang sebenarnya akan Churn tetapi diprediksi tidak Churn oleh model. 
- Penggunaan metode SMOTE karena indikasi pembuatan model sulit karena data yang tidak seimbang.
- Pengujian ulang dan model Random Forest yang terbaik dengan skor Recall mencapai 100%. Ibaratnya dari 100 pelanggan yang sebenarnya akan Churn, model dapat mendeteksi secara akurat sepenuhnya 100 pelanggan tersebut. Selain itu, model ini pun memiliki skor tinggi pada nilai keseluruhan (Accuracy Score), Precision, maupun F1 score. 
- Catatan bahwa pengulangan model bisa menurunkan skor Recall tetapi hanya di 98%-99% saja. 
- Limitasi dari model ini adalah dapat digunakan pada data pelanggan dengan durasi berlangganan 0 sampai 72 bulan dan tagihan bulanan dalam rentang $18.8 sampai dengan $118.65; Data observasi dengan angka di luar batasan tersebut tidak dapat menggunakan model ini dan perlu penyesuaian pada model.

Cara kerja model:
- Pembuatan Sampel: Random Forest mengambil sampel acak dengan penggantian dari dataset pelatihan. Setiap sampel yang diambil akan memiliki ukuran yang sama dengan dataset pelatihan asli.
- Pembangunan Pohon Keputusan: Untuk setiap sampel yang diambil, pohon keputusan dibangun dengan menggunakan sebagian data pelatihan. Pada setiap node dalam pohon keputusan, beberapa fitur secara acak dipilih sebagai kandidat pemisah (splitter). Pemilihan pemisah dilakukan berdasarkan kriteria seperti Gini Impurity atau Information Gain.
- Penggabungan Pohon: Setelah pembangunan pohon keputusan, hasil prediksi dari setiap pohon digabungkan untuk menghasilkan prediksi akhir. Untuk masalah klasifikasi, penggabungan biasanya menggunakan voting mayoritas, yaitu prediksi kelas yang paling sering muncul dari semua pohon. Sedangkan untuk masalah regresi, penggabungan dapat menggunakan rata-rata atau median dari prediksi pohon.

Dengan adanya model ini, perusahaan PT Telco Connect memiliki kesempatan untuk mendeteksi pelanggan yang Churn seakurat dan sedini mungkin untuk dapat melakukan pencegahan. Sesuai dengan tujuan perusahaan dalam kasus ini yaitu menggunakan alokasi dana *Retention Customer* secara optimal dan tepat sasaran. Tentunya, target yang disasar adalah **pelanggan yang berpotensi akan Churn**. Pelanggan yang berpotensi akan Churn mulai tidak menemukan benefit dari menggunakan layanan. Oleh karena itu, alokasi dana ini dapat digunakan untuk:
- subscription CRM tool sebagai metode untuk selalu membangun koneksi dan interaksi dengan pelanggan, caranya seperti mengirimkan *Newsletter* rutin ke email pelanggan, mengirimkan *Push Notification* secara berkala dan relevan, menampilkan *Pop Up Banner* pada aplikasi untuk mendorong pelanggan melakukan purchase, dan lainnya
- memberikan potongan atau promosi agar pelanggan mau *Upselling* layanan, misalnya pelanggan yang sudah menggunakan layanan internet akan mendapatkan potongan ketika ingin menggunakan layanan Device Security
- memberikan harga spesial pada pelanggan untuk menambah layanan di hari ulang tahunnya
- memberikan promosi ketika pelanggan sudah menggunakan layanan tertentu selama kurun waktu tertentu
- dan lainnya

Dari dataset ini, faktanya adalah perusahaan kehilangan 26.5% pelanggan dan 30% pendapatan. 
Dampak dari solusi ini secara terukur adalah<br>
- **[1] Skenario Ideal** (anggap setiap strategi di atas berhasil sesuai harapan), pelanggan yang Churn dan pendapatan yang hilang turun secara signifikan menjadi nol atau hanya di 1-2% saja. Analoginya, yang tadinya dari 100 pelanggan perusahaan bisa kehilangan 26 pelanggan, sekarang tidak ada yang Churn atau hanya 1-2 pelanggan saja yang berhenti menggunakan layanan.
- **[2] Skenario Moderate** (tingkat kesuksesan hanya 50%), pelanggan yang Churn turun menjadi 13% saja dan pendapatan hilang 15%. Analoginya, dari 100 pelanggan yang semula akan Churn sebanyak 26 pelanggan sekarang menjadi kurang lebih 13 pelanggan. <br><br>

Skenario dan analogi di atas juga berlaku untuk pendapatan. 30% pendapatan yang setara 96 ribu dollar dalam dataset ini dapat kita turunkan secara signifikan. Persentase ini bersifat relatif, jika kedepannya jumlah tagihan bulanan semakin meningkat, maka persentase 30% dalam konteks ini pun akan semakin besar pula. 
**Catatan bahwa implementasi strategi ini hanya menggunakan dana yang memang sudah dialokasikan untuk Customer Retention tanpa overbudget.**
