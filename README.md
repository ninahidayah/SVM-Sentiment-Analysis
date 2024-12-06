# SVM-Sentiment-Analysis
Pada repository ini saya membuat Sentiment Analysis dengan menggunakan Model SVM (Support Vector Machine)

Sentiment Analysis
Sentiment Analysis adalah Teknik (Natural Language Processing, NLP) yang digunakan untuk mengidentifikasi dan mengkategorikan emosi atau opini dalam teks. Teknik ini sering digunakan untuk memahami opini publik terhadap suatu produk, layanan, atau topik tertentu.
Apa saja yang perlu dipersiapkan?
1. Data
Data yang digunakan adalah data review aplikasi yang diambil dari scraping data di google play store. Kemudian data yang diambil adalah data hanya di tahun 2024 di wilayah Indonesia.
2. Preprocessing 
Tahapan untuk menghilangkan permasalahan yang dapat mengganggu hasil dari proses data karena data dari Google Play Store belum bersih. Kita harus membersihkan dan memilih fitur sebelum masuk ke analisis sentiment.
•	Data cleansing 
Proses pembersihan data yang meliputi:
    1. Remove Lowercase
    2. Remove Punctuation
    3. Remove Whitespace
    4. Remove Mention (@username)
    5. Remove hastag (#tag)
    6. Remove URL or link
    7. Remove ASCII and Unicode
    8. Remove newline
•	Normalisasi 
•	Filtering
Disini dilakukan StopWords yaitu penghapusan kata yang tidak penting digunakan dan tidak relevan dalam analisis teks.
•	Tokenez
•	Stemming
3. TF-IDF
Mengukur seberapa sering suatu kata muncul. Semakin sering kata muncul, semakin tinggi nilai TF-nya. Ini digunakan untuk mengubah teks menjadi representasi numerik (vektor) yang dapat digunakan oleh algoritma pembelajaran mesin, seperti SVM.
4. Implementasi Model SVM
SVM efektif untuk data dengan dimensi tinggi(seperti gambar atau teks) dan dapat menangani data non-linear dengan menggunakan kernel.




