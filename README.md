# Submission 1: Disaster Tweets Classification

Nama: Andrew Benedictus Jamesie

Username Dicoding: [andrewbj](https://www.dicoding.com/users/andrewbj)

|     | Deskripsi |
| --- | --------- |
| Dataset | [Natural Language Processing with Disaster Tweets](https://www.kaggle.com/competitions/nlp-getting-started) |
| Latar Belakang | Menurut data Badan Pusat Statistik (BPS) Indonesia, tercatat ada sebanyak 43.208 desa/kelurahan yang terkena bencana alam dalam 3 tahun terakhir (2019, 2020, dan 2021). Data bencana alam tersebut mencakup seperti tanah longsor, banjir, banjir bandang, gempa bumi, tsunami, gelombang pasang air laut, angin puting beliung, gunung meletus, kebakaran hutan, dan juga kekeringan. Sedangkan yang tidak ada terjadi bencana alam, yaitu 52.670 desa/kelurahan. Hal tersebut menunjukkan bahwa Indonesia masih termasuk ke dalam wilayah yang rawan terjadi bencana alam baik yang disebabkan oleh manusia maupun alam itu sendiri, dengan persentase sebesar 45% wilayah desa/kelurahan yang terkena bencana alam. |
| Masalah | Berdasarkan latar belakang di atas, terdapat masalah yang sering kali terjadi di Indonesia, yaitu berita palsu atau *hoax* yang dapat dengan cepat tersebar dengan adanya bantuan teknologi komunikasi, salah satunya adalah Twitter yang banyak digunakan oleh masyarakat Indonesia. Berita palsu tersebut akan menimbulkan dampak negatif bagi banyak orang jika tidak benar-benar menyaringnya terlebih dahulu, apakah sebenarnya berita ini merupakan berita asli atau berita palsu, terutama berita mengenai bencana alam. |
| Solusi Machine Learning | Dengan begitu, diperlukan sebuah sistem yang dapat mendeteksi berita bencana alam tersebut menggunakan machine learning, di mana sistem tersebut dapat melakukan klasifikasi berita yang termasuk ke dalam berita asli atau berita palsu. |
| Metode Pengolahan Data | Metode pengolahan data yang digunakan pada proyek ini adalah dengan menghapus atau *drop* beberapa fitur atau kolom yang tidak dibutuhkan, melakukan tahap *Data Ingestion* dengan membagi *dataset* menjadi *data training* dan *data evaluation* dengan rasio 9:1. Kemudian melakukan tahap *Data Validation* dengan cara melihat statistik data, *data schema*, serta mengidentifikasi anomali pada *dataset*. Setelah itu melakukan tahap *Data Preprocessing* dengan melakukan transformasi fitur input pada data. |
| Arsitektur Model | Arsitektur model yang dibangun menggunakan sebuah input layer yang menerima data teks atau string dan akan masuk ke layer TextVectorization untuk memproses input teks tersebut menjadi representasi numerik agar dapat dengan mudah dipahami oleh model machine learning. Kemudian terdapat sebuah layer Embedding dan layer Bidirectional LSTM untuk mempelajari input kata yang telah diproses sebelumnya. Lalu terdapat 2 hidden layer (Dense layer) serta 1 output layer. |
| Metrik evaluasi | Deksripsi metrik yang digunakan untuk mengevaluasi performa model |
| Performa model | Deksripsi performa model yang dibuat |
