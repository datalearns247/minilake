# Minilake
Minilake adalah sebuah solusi platform data lakehouse yang berjalan secara lokal, ringan, dan tanpa konfigurasi yang rumit. Tujuannya sederhana yaitu membantu siapa pun yang ingin membangun, belajar, dan bereksperimen dengan teknologi data terkini secara cepat dan efisien. Tidak perlu server, tidak perlu cloud, hanya diperlukan laptop dan data.

## Apa yang Membuat Minilake Berbeda?
1. Teknologi Open Source – Pemilihan teknologi hanya yang bersifat open source, sehingga siapaun bebas menggunakannya
2. Ringan \& Portabel – Dapat dijalankan di laptop biasa, cocok untuk lingkungan akademik
3. Zero Configuration – (Hampir) Tidak memerlukan instalasi yang rumit
4. Local-first – Fokus pada pembelajaran dan eksperimen data secara offline, tanpa memerlukan server dan cloud
5. Mudah Dipahami – Dirancang agar bisa digunakan sebagai alat pembelajaran untuk generasi baru praktisi data

## Siapa Penggunanya?
* Mahasiswa yang ingin memahami dan mencoba teknologi data lakehouse tanpa tergantung infrastruktur kampus
* Dosen bisa menggunakan Minilake sebagai alat bantu praktikum untuk mata kuliah Big Data atau Data Engineering
* Data Engineer \& Analyst yang ingin prototyping pipeline secara lokal sebelum deployment ke lingkungan production
* Komunitas data bisa menggunakan Minilake untuk pelatihan ataupun workshop tanpa khawatir soal setup infrastruktur

## Teknologi Utama Yang Digunakan
* Storage Layer - Minio
* File Format -  Apache Parquet
* Open Table Format - Apache Iceberg
* Metadata Catalog - Local REST Catalog
* Query Engine - SparkSQL
* Processing Engine - Apache Spark
* Analytics Tools - Jupyter Lab
* Orchectrator - Apache Airflow (sedang dalam pengujian)
* BI Tools - Metabase (sedang dalam pengujian)

## Penggunaan
1. Clone repository
   ```
   git clone https://github.com/datalearns247/minilake.git
   cd minilake
   ```

2. Jalankan docker
   ```
   docker compose up -d
   ```
   
3. Mengakses service melalui browser:
   - Jupyter Notebook : http://localhost:8888
   - Minio : http://localhost:9001
