# Helmet Detection Using YOLO

## Overview

Proyek ini merupakan implementasi sistem deteksi helm menggunakan model YOLO (You Only Look Once). Sistem dikembangkan untuk mendeteksi penggunaan helm pada pengendara sepeda motor melalui citra maupun video secara otomatis.

Model dilatih menggunakan dataset yang berisi objek pengendara dengan dan tanpa helm, kemudian digunakan untuk melakukan proses deteksi secara real-time maupun pada data uji.

## Objectives

* Mendeteksi penggunaan helm pada pengendara sepeda motor.
* Menerapkan algoritma YOLO untuk object detection.
* Mengevaluasi performa model pada data pengujian.
* Menampilkan hasil deteksi dalam bentuk visualisasi bounding box.

## Project Structure

```text
helmet-detection/
├── Coding/
├── Dataset/
├── Deteksi_Helm/
├── Media/
├── Weights/
├── YOLO_Helmet_Detection_Sample_Images/
├── project/
├── runs/detect/
├── README.md
└── .gitignore
```

## Technologies

* Python
* YOLO
* OpenCV
* NumPy
* Pandas
* Matplotlib

## Workflow

1. Persiapan dataset.
2. Pelabelan data objek.
3. Pelatihan model YOLO.
4. Evaluasi model.
5. Pengujian menggunakan gambar atau video.
6. Visualisasi hasil deteksi.

## Detection Result

Model akan mengidentifikasi objek pada gambar dan memberikan bounding box beserta label hasil prediksi. Hasil deteksi disimpan pada folder `runs/detect`.

## Notes

File model berukuran besar tidak disertakan dalam repository ini. Untuk menjalankan sistem secara penuh, model hasil pelatihan perlu ditambahkan kembali ke folder `Weights`.
