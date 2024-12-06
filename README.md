# SVM-Sentiment-Analysis
Pada repository ini saya membuat Sentiment Analysis dengan menggunakan Model SVM (Support Vector Machine)

# Sentiment Analysis
Sentiment Analysis adalah Teknik (Natural Language Processing, NLP) yang digunakan untuk mengidentifikasi dan mengkategorikan emosi atau opini dalam teks. Teknik ini sering digunakan untuk memahami opini publik terhadap suatu produk, layanan, atau topik tertentu.


          #Apa saja yang perlu dipersiapkan?
          
          1. Data 
             yang digunakan adalah data review aplikasi yang diambil dari scraping data di google play store. 
             Kemudian data yang diambil adalah data hanya di tahun 2024 di wilayah Indonesia.

          2. Preprocessing 
             Tahapan untuk menghilangkan permasalahan yang dapat mengganggu hasil dari proses data karena 
             data dari Google Play Store belum bersih. Kita harus membersihkan dan memilih fitur sebelum masuk
             ke analisis sentiment.

                    1. Data cleansing 
                       Proses pembersihan data yang meliputi:
                       - Remove Lowercase
                       - Remove Punctuation
                       - Remove Whitespace
                       - Remove Mention (@username)
                       - Remove hastag (#tag)
                       - Remove URL or link
                       - Remove ASCII and Unicode
                       - Remove newline
  
                    2. Normalisasi 

                    3. Filtering
                       Disini dilakukan StopWords yaitu penghapusan kata yang tidak penting digunakan dan tidak relevan dalam analisis teks.

                    4. Tokenez

                    5. Stemming

          3. TF-IDF
             Mengukur seberapa sering suatu kata muncul. Semakin sering kata muncul, semakin tinggi nilai TF-nya. Ini digunakan untuk 
             mengubah teks menjadi representasi numerik (vektor) yang dapat digunakan oleh algoritma pembelajaran mesin, seperti SVM.

          5. Implementasi Model SVM
             SVM efektif untuk data dengan dimensi tinggi(seperti gambar atau teks) dan dapat menangani data non-linear dengan menggunakan kernel.
![Proporsi Sentimen Pelanggan](https://github.com/user-attachments/assets/987b4c70-a73f-4dcc-9933-fab10ee884b4)

![Classification Report](https://github.com/user-attachments/assets/8819264b-dccd-48c7-abc8-ac8fce93594f)



