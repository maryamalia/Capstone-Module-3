# Capstone-Project-3
## E-commerce Customer Churn
Perusahaan electronic commerce (E-commerce) atau perdagangan elektronik adalah perusahaan yang melakukan kegiatan jual atau beli secara online dengan menggunakan internet. Perusahan e-commerce perlu melakukan evaluasi pelanggan untuk mengetahui customer churn pada perusahaan.
<br>
Sebuah perusahaan e-commerce ingin mengetahui customer churn atau pelanggan yang tidak menggunakan jasa perusahaan lagi, sehingga dapat menimbulkan kerugian bagi perusahaan. Oleh karena itu, perusahaan perlu melakukan prediksi terhadap customer, agar sebelum costumer benar-benar churn, perusahaan dapat menjangkau customer tersebut dengan memberikan layanan yang lebih baik, seperti memberikan promo yang menarik. Namun, sebaiknya promo diberikan kepada orang yang tepat. Dengan demikian, perusahaan dapat menghindari kerugian yang akan terjadi akibat kehilangan pelanggan.
<br>
Machine Learning mampu mengatasi masalah yang ada pada perusahaan e-commerce ini, yaitu untuk melakukan prediksi pada customer yang akan melakukan churn. Algoritma machine learning yang digunakan pada model ini adalah XGBoost yang dilakukan tuning sebanyak dua kali, dengan nilai akurasi model sebesar 78% menggunakan f2 score. Model ini mampu menurunkan kerugian perusahaan sebesar 76.59%, dengan menekan angka false negative.
Berdasarkan explainable machine learning menggunakan feature importance dan SHAP, faktor-faktor yang mempengaruhi customer melakukan churn adalah tenure (lama menjadi customer perusahaan) dan complaint.
