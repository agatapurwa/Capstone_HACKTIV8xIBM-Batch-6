# Capstone_HACKTIV8xIBM-Batch-6
Capstone Project Data Classification and Summarization Hacktiv8xIBM

# Title Project: Analisis Interaksi FED Rate, BI Rate, dan Inflasi Indonesia 2017–2024 dalam Perspektif Kebijakan Moneter

# Project Overview
Tujuan proyek ini adalah mengembangkan sistem analisis hubungan antara FED Rate, BI Rate, dan inflasi Indonesia periode 2017–2024 untuk mendukung rekomendasi kebijakan moneter dan fiskal. Latar belakang penelitian didasari oleh kebutuhan Bank Indonesia dan Pemerintah dalam merespons dinamika global serta menjaga stabilitas harga domestik. Permasalahan yang diangkat bersifat spesifik dan relevan, yaitu bagaimana pergerakan suku bunga global memengaruhi kebijakan suku bunga domestik dan inflasi nasional. Pendekatan dilakukan secara runtut melalui pengumpulan data historis, analisis statistik, visualisasi tren, hingga pemanfaatan LLM untuk menghasilkan insight dan rekomendasi kebijakan yang berbasis data.

# Raw Dataset Link
Federal Funds Effective Rate (FEDFUNDS): 
https://fred.stlouisfed.org/series/FEDFUNDS

BI-Rate:
https://www.bi.go.id/id/statistik/indikator/bi-rate.aspx

Data Inflasi:
https://www.bi.go.id/id/statistik/indikator/data-inflasi.aspx

Dataset terdiri dari ketiga tambel di atas, dengan rentang 1 Januari 2017 - 31 Desember 2024. Kemudian diupload ke google colab dalam folde "dataset"

# Insight and Findings
Analisis Tren
FED Rate: Naik 2017–2019, turun drastis 2020–2021 akibat pandemi, lalu melonjak 2022–2024 karena inflasi global.
BI Rate: Stabil di awal, turun saat pandemi, kemudian naik signifikan sejak 2022 mengikuti arah FED Rate.
Inflasi Indonesia: Turun hingga 2021, melonjak 2022 (4,95%), lalu kembali terkendali 2023–2024.
Analisis Hubungan
FED Rate ↔ BI Rate: Korelasi kuat (0,78), BI Rate cenderung mengikuti FED.
BI Rate ↔ Inflasi: Korelasi sedang-kuat (0,65), menunjukkan BI Rate efektif sebagai alat pengendali inflasi.
FED Rate ↔ Inflasi: Korelasi lemah (0,32), inflasi Indonesia lebih dipengaruhi faktor domestik.
Insight Utama
BI Rate sangat responsif terhadap pergerakan FED Rate dan berperan penting dalam mengendalikan inflasi domestik. Inflasi Indonesia lebih dipengaruhi kebijakan moneter lokal daripada langsung oleh FED Rate.

# AI Support Explanation
LLM (Large Language Model) digunakan untuk:
Menghasilkan insight otomatis dari data FED Rate, BI Rate, dan Inflasi Indonesia.
Melakukan summarization tren ekonomi agar mudah dipahami.
Menyusun rekomendasi kebijakan moneter & fiskal yang berbasis data.

Manfaat AI:
Mengubah data kompleks menjadi narasi yang jelas.
Mendukung pengambilan keputusan strategis.
Mempercepat proses analisis & dokumentasi.

Alasan Menggunakan IBM Granite 3.3-8B Instruct
Instruction-tuned → akurat ikuti arahan analisis
Efisien (8B) → cocok untuk Colab
Output profesional & cepat
Dukungan enterprise dari IBM
