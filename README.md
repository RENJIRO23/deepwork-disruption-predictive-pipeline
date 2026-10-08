# deepwork-disruption-predictive-pipeline
# about this project
Proyek ini menggunakan Pentaho Spoon untuk proses ETL untuk Transformation Data dan juga orchestration. Proyek ini menggunakan struktur Star Schema dengan tepat dan benar. Data diload kedalam MySQL sebelum di preprocess di Pentaho, setelah proses preprocessing seleasai data kembali diload ke MySQL. Data yang sudah bersih di export ke format csv dan dilakukan random forest dan XGBoost modeling.
#Hasil
Setelah membandingkan kedua model, XGBoost dipilih sebagai pilihan utama karena memiliki precision lebih besar(42.22%). XGBoost juga menghasilkan lebih sedikit false alarm. Hasilnnya, konten tipe reels dan stories yang merupakan fitur dari platform Instagram adalah yang paling mempengaruhi deepwork focus. Diantara Gen Millenial, X ,dan Z ditemukakn juga bahwa Gen Z lah yang paling terdampak
