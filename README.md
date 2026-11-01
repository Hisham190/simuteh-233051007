# SIMUTEH: Evaluasi Praktikum Computer Vision

## Identitas Mahasiswa

* **Nama:** Hisham Mahdi
* **NIM:** 233051007
* **Mata Kuliah:** Computer Vision
* **Studi Kasus:** SIMUTEH

## Deskripsi Proyek

Repositori ini digunakan untuk mendokumentasikan pengerjaan praktikum evaluasi Computer Vision P1-P4 dengan studi kasus SIMUTEH.

Tahapan praktikum meliputi persiapan lingkungan pengembangan, pengolahan citra digital, analisis histogram, penapisan citra, dan praproses citra.

## Struktur Direktori

```text
simuteh-233051007/
├── data/
│   └── sintetis/
│       ├── citra/
│       ├── bersih/
│       ├── mask_daun/
│       └── mask_bercak/
├── notebook/
│   └── B1_lingkungan.ipynb
├── src/
│   ├── buat_dataset_sintetis.py
│   └── utils_cv.py
├── hasil/
├── laporan/
├── requirements.txt
└── README.md
```

## Teknologi yang Digunakan

* Python
* OpenCV
* NumPy
* Matplotlib
* scikit-image
* Pandas
* Pillow
* Google Colab

Daftar dependensi dan versinya tersedia dalam file `requirements.txt`.

## Dataset

Dataset sintetis dibuat menggunakan skrip `src/buat_dataset_sintetis.py`. Proses pembangkitan dataset menggunakan nilai `SEED = 1007`, sesuai empat digit terakhir NIM.

Dataset disimpan dalam direktori `data/sintetis/`.

## Progres Praktikum

* [x] B1: Persiapan lingkungan dan formulasi masalah
* [ ] B2: Citra dan warna
* [ ] B3: Histogram
* [ ] B4: Penapisan
* [ ] B5: Praproses citra

## Menjalankan Proyek

Proyek dikembangkan menggunakan Google Colab. Notebook praktikum dapat dibuka melalui direktori `notebook/`.

Untuk memasang dependensi, jalankan perintah berikut:

```bash
pip install -r requirements.txt
```

## Catatan

Repositori ini merupakan dokumentasi pengerjaan praktikum Computer Vision. Hasil dan analisis setiap tahap akan ditambahkan sesuai perkembangan praktikum.
