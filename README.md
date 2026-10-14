# Preprocessing Data - Industri Olahan Makanan Jawa Tengah 2025

Tugas mata kuliah Data Mining: preprocessing data (cleaning, transformation) menggunakan Python di Google Colab.
## Link Google Colab
- Notebook di Google Colab: [https://colab.research.google.com/drive/1CXDWVl89JxPKuCstszqPYhmjZF-e6f3J?usp=sharing]

## Sumber Data
- Dataset: Data Sebaran Industri Olahan Makanan di Jawa Tengah (s.d. Agustus 2025)
- Penerbit: Dinas Perindustrian dan Perdagangan Provinsi Jawa Tengah (SIINas)
- Portal: https://data.jatengprov.go.id/dataset/data-industri-olahan-pangan-di-jateng-2025
- Tanggal unduh: 11 Oktober 2026
- Ukuran: 3.243 perusahaan, 7 kolom

## Isi Repository
- `preprocessing_data_colab.ipynb` : kode preprocessing (jalankan di Google Colab)
- `data-industri-olahan-pangan-di-jateng-2025.xlsx` : data mentah (tidak diubah)
- `data-industri-olahan-pangan-di-jateng-2025_bersih.csv` / `.xlsx` : data hasil preprocessing

## Ringkasan Langkah
1. Membaca data dan memeriksa struktur (header, tabel samping, catatan kaki)
2. Memeriksa kualitas data (missing value, duplikat, kategori tidak konsisten)
3. Membersihkan format (spasi, penulisan kategori, kode KBLI tetap teks)
4. Menangani missing value dan duplikasi
5. Mendeteksi outlier dengan IQR (tidak dihapus)
6. Validasi sebelum dan sesudah, catatan perubahan di sheet Excel

## Cara Menjalankan
Buka notebook di Google Colab, jalankan semua sel, lalu unggah file data mentah saat diminta.
