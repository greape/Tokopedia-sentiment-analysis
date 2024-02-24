Sebagai seorang analis data yang tertarik pada tren konsumen dan pengalaman pengguna, saya ingin berbagi beberapa pemikiran menarik yang saya temukan dalam analisis sentimen terhadap ulasan Tokopedia di Google Play Store.

Dalam melakukan sentimen analysis saya melakukan beberapa tahapan yaitu:

**1. Data**
Dalam melakukan pengambilan data saya melakukan scraping pada review tokopedia di aplikasi playstore, jumlah data yang saya ambil adalah 1000 data dari yang terbaru dan selanjutnya saya melakukan manual labelling dengan 0 dan 1 yang menandakan negative sentimen dan positive sentiment

**2. Preprocessing**
Dalam melakukan pembuatan model NLP maka tentu saja text atau data yang digunakan harus di preprocessing terlebih dahulu. Tahapan ini akan menghilangkan tanda baca, mengubah ke huruf kecil, menghilangkan stopword yang tidak informatif seperti kata hubung "dan".

**3. Modeling**
Dalam membuat model sentiment analysis digunakan 2 base model yaitu RNN dan LSTM, diperoleh LSTM sebagia base model terbaik lalu dilakukan improvement model dengan teknik transfer learning, penambahan layer, dan juga penambahan epoch. Best model memiliki nilai f1-score sebesar 84% dalam memprediksi negative sentiment dan 60% dalam memprediksi positive sentiment

**Further improvement:**
Untuk meningkatkan kemampuan model dalam melakukan prediksi sentiment negative maupun positive sebaiknya dilakukan training dengan data yang lebih banyak agar memiliki f1-score yang lebih baik


Melalui pengumpulan dan analisis ribuan ulasan pengguna, saya dapat memperoleh wawasan yang dalam tentang bagaimana pengguna merasakan layanan dan pengalaman berbelanja di Tokopedia. Ada banyak aspek positif dan juga negatif yang dapat kita lihat pada wordcloud yang saya tampilkan di gambar

Untuk sentimen negative pada tokopedia kebanyakan berkutat pada masalah dalam pengiriman, jika dilihat pada negative sentiment di wordcloud pengiriman, kurir, dan barang merupakan yang terbesar lalu disusul oleh aplikasi yang bisa jadi disebabkan karena masalah pada mobile app dari tokopedia. Pada positive sentiment yang menarik adalah kebanyakan hanya memberi kalimat yang ada di suggestion apabila memberikan bintang 5 seperti good,nice, ok dll sangat berbeda dengan negative sentiment yang langsung memberikan keluhannya, tetapi terdapat juga positive sentiment yang menyampaikan alasan mereka memberi sentiment yang positive misalnya kata seperti promo dan belanja

Dari data analisa yang saya lakukan tokopedia dapat melakukan pembenahan dalam masalah pengiriman dan juga aplikasinya dengan harapan pengguna dapat lebih nyaman dalam berbelanja dan mendatangkan keuntungan yang lebih banyak untuk tokopedia.Saya berharap postingan ini memberikan gambaran pentingnya analisis sentimen dalam konteks layanan pelanggan dan pengalaman pengguna
