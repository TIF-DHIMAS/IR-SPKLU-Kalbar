# Sistem Rekomendasi SPKLU Kalimantan Barat

## Mata Kuliah
Information Retrieval

## Nama
Dhimas Pratitis

## Deskripsi
Proyek ini merupakan implementasi sederhana sistem rekomendasi SPKLU di Kalimantan Barat menggunakan metode **Content-Based Filtering**.

Rekomendasi diberikan berdasarkan kemiripan atribut SPKLU menggunakan:

- TF-IDF (Term Frequency - Inverse Document Frequency)
- Cosine Similarity

## Dataset
Dataset berisi informasi SPKLU seperti:
- Nama SPKLU
- Kota
- Jenis Charger
- Daya (kW)

## Cara Menjalankan

1. Buka file **IR_SPKLU_Kalbar.ipynb** menggunakan Google Colab.
2. Jalankan setiap cell secara berurutan.
3. Upload dataset **spklu.xlsx**.
4. Pilih SPKLU pada dropdown.
5. Klik tombol **Tampilkan Rekomendasi**.

## Metode

1. Import Dataset
2. Membuat fitur (Content)
3. TF-IDF Vectorizer
4. Cosine Similarity
5. Menampilkan Top 5 Rekomendasi
