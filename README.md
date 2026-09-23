# Implementasi Clustering pada Prediksi Serangan Jantung

## Deskripsi Proyek
Perbandingan lima metode clustering (K-Means, K-Median, DBSCAN, Mean Shift, Fuzzy C-Means) pada dataset Heart Attack Prediction (1.025 observasi, 14 variabel). K-Means menjadi metode terbaik dengan silhouette score 0,1228, Dunn Index 0,0307, dan WCSS 11.014,79.

## Tujuan
- Menerapkan lima metode clustering pada dataset heart disease.
- Menentukan metode clustering terbaik untuk pengelompokan data.

## Tools & Library
- R Programming, RStudio
- Package: `cluster`, `factoextra`, `ggplot2`, `dplyr`, `dbscan`, `e1071`
- RPubs (publikasi hasil)

## Hasil
| Metode | Silhouette | Dunn Index | WCSS |
|---|---|---|---|
| **K-Means** | **0,1228** | **0,0307** | **11.014,79** |
| K-Median | 0,1177 | 0,0073 | 11.188,85 |
| DBSCAN | 0,761* | 0,982* | 5,769* |
| Mean Shift | 0,0658 | 0,0034 | 10.971,17 |
| Fuzzy C-Means | 0,0312 | 0,0069 | 11.834,43 |

*\*DBSCAN hanya dihitung dari data non-noise.*

**Kesimpulan:** K-Means paling optimal untuk dataset heart disease dengan karakteristik distribusi terstruktur.

## File Terkait
- RPubs (Hasil Lengkap)]<br>(https://rpubs.com/zhrraidaaa/Modul3Clustering)
- Dataset [Heart Attack Prediction (Kaggle)<br>(https://www.kaggle.com/datasets/juledz/heart-attack-prediction)

## Author
**Fauziah Roikhana Wardah** (dan tim)
- Program Studi S1 Sains Data, Universitas Negeri Surabaya
