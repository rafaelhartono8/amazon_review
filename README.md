## ANALISIS REVIEW PRODUK AMAZON DENGAN MENGGUNAKAN LLM IBM INSTRUCT
## Overview Proyek

* **Tujuan Utama:** Menganalisis sentimen dan pola dari ulasan produk yang diberikan oleh konsumen di Amazon.
* **Latar Belakang:** Ulasan konsumen adalah sumber daya berharga untuk memahami kepuasan pelanggan, mengidentifikasi kekuatan/kelemahan produk, dan memandu strategi bisnis.
* **Permasalahan:** Mengorganisir dan mengekstrak wawasan yang berarti dari volume besar teks ulasan yang tidak terstruktur.
* **Pendekatan:** Melakukan tahapan awal eksplorasi data, termasuk pengunduhan, pemuatan, dan inspeksi struktur data ulasan.

## Raw Dataset Link
https://www.kaggle.com/datasets/arhamrumi/amazon-product-reviews

## Insight & Findings 
**Untuk Pembeli :**
1. Dari 7 produk yang ditemukan ada 3 yang di  rekomendasikan untuk dibeli
   ![image](https://github.com/user-attachments/assets/5169791f-6283-4f07-a5f7-4ffca780f177)

2. Berikut peta persebaran tingkat rekomendasi berdasarkan tiap produk
  ![image](https://github.com/user-attachments/assets/e8ac2ab9-bf3c-48b9-89be-97c7d3b4246d)
   
**Untuk Penjual : **
  1. 3 dari 7 produk perlu di tinjau kembali untuk meningkatkan penjualan
    ![image](https://github.com/user-attachments/assets/2308a689-3984-4435-8ff7-3a61915f48af)

  2. Pemetaan kata perbaikan yang dibutuhkan yang dapat berpotensi meningkatkan penjualan
    ![image](https://github.com/user-attachments/assets/379de9d7-aaab-464d-80f9-4bbce32fdb4f)


## Kesimpulan & Rekomendasi

### Kesimpulan

Proyek ini telah berhasil menyiapkan dan melakukan eksplorasi awal dataset ulasan produk Amazon. Data yang tersedia sangat sesuai untuk analisis sentimen mendalam dan pengembangan model prediktif.

### Rekomendasi Selanjutnya

1.  **Klasifikasi Sentimen:** Kembangkan sistem untuk mengklasifikasikan ulasan menjadi kategori sentimen (misalnya, Positif, Netral, Negatif) berdasarkan `Score` dan analisis teks.
2.  **Analisis Sentimen Berbasis Teks Lanjutan:** Terapkan teknik Pemrosesan Bahasa Alami (NLP) yang lebih canggih (misalnya, analisis sentimen leksikon atau berbasis model) pada kolom `Text` dan `Summary` untuk wawasan yang lebih granular.
3.  **Identifikasi Topik:** Gunakan algoritma pemodelan topik (misalnya, Latent Dirichlet Allocation/LDA) untuk mengidentifikasi topik atau tema umum yang dibahas dalam ulasan.
4.  **Rekomendasi Aksi:** Berdasarkan sentimen dan topik yang teridentifikasi, berikan rekomendasi konkret dan dapat ditindaklanjuti untuk perbaikan produk, strategi pemasaran, atau layanan pelanggan.

## Penjelasan Dukungan AI

Dalam proyek ini, AI (Artificial Intelligence) mendukung proses awal melalui:

* **Otomatisasi Pengumpulan Data:** Penggunaan `kagglehub` memungkinkan pengunduhan dataset secara otomatis, yang merupakan langkah kunci dalam alur kerja berbasis AI/ML.
* **Dasar untuk Model AI:** Meskipun kode ini belum mengimplementasikan model AI secara langsung (seperti LLM untuk klasifikasi atau ringkasan), data yang disiapkan merupakan fondasi penting untuk melatih dan mengevaluasi model AI di kemudian hari untuk tugas-tugas seperti:
    * **Klasifikasi Teks:** Mengkategorikan ulasan secara otomatis berdasarkan sentimen.
    * **Summarization (Peringkasan):** Meringkas poin-poin kunci dari ulasan panjang.
    * **Analisis Sentimen:** Memahami nuansa emosional dalam teks ulasan.

---
