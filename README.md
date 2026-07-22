# Deskripsi

Asesmen ini melakukan Optical Character recognition pada plat nomor kendaraan menggunakan 
VLM (misalnya LLava Bakllava) dijalankan melalui LMSTUDIO dan diintegrasikan dengan python
Output berupa file CSV berisi hasil prediksi dan evaluasi menggunakan metrik Character Error Rate (CER).

Dataset yang digunakan: Indonesian License Plate Recognition (folder test).

1. Persiapan
Unduh dataset dari Kaggle dan ekstrak ke folder dataset/test/.

Install LMStudio dan jalankan model multimodal (contoh: llava, bakllava).

Pastikan LMStudio API aktif di http://localhost:1234/v1/chat/completion.
