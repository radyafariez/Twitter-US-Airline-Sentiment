# Submission 1: US Airline Sentiment
-------------------------------------------------------------------

Nama : Mohammad Radya Fariez

Username Dicoding : radyafariez

|	                       | Deskripsi                                                            |
|------------------------|----------------------------------------------------------------------|
|Dataset                 | [Twitter US Airline Sentiment](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment?select=Tweets.csv)                                                                              |
|Masalah                 | Permasalahan layanan maskapai di US menjadi fokus perhatian perusahaan untuk menjadi acuan dalam penilaian performa maskapai. Hal itu membuat perusahaan membutuhkan pengolahan data terkait review atau sentimen terhadap maskapai. Dibutuhkan suatu sistem yang secara otomatis mampu mengelompokkan sentimen positif, negatif atau netral agar dapat dianalisa secara matang.                                                                        |
|Solusi machine learning | Diperlukan solusi pengembangan Machine Learning yang mampu melakukan klasifikasi terhadap sentimen negatif terhadap layanan maskapai melalui sosial media Twitter.                                 |
|Metode pengolahan	     | Metode pengolahan data menggunakan tokenisasi dari input berupa fitur teks yang dikonversi menjadi susunan angka untuk dapat diproses di tahap training model.                                     |
|Arsitektur model	       | Arsitektur model menggunakan layer TextVectorization yang berperan melanjutkan proses input dalam susunan angka, lalu Embedding layer mengidentifikasi _similarity_ atau kedekatan dari kata per kata untuk mengetahui apakah sentimen berupa sentimen negatif, positif atau netral.                                          |
|Metrik evaluasi	       | Evaluasi performa model pada proyek ini dilakukan dengan menggunakan metrik BinaryAccuracy, TruePositive, TrueNegative, FalsePositive dan FalseNegative                                     |
|Performa model	         | Deksripsi performa model yang dibuat                                 |
