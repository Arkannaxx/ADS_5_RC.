# **README.md – Tugas Besar Analisis Data Statistika 2025**

_(Kelompok 5 – Kelas RC)_
# ⭐ **Anggota Kelompok 5 – Kelas RA**

1.  **Rakha Rabbani** – _NIM: 123450098_
    
2.  **Layina Ropiqo** – _NIM: 124450016_
    
3.  **Cerine Sihotang** – _NIM: 124450049_
    
4.  **Ahmad Bimo Akbar Arkana Putra** – _NIM: 124450113_
#  **Mitos Mahasiswa Sibuk: Analisis Hubungan Keterlibatan Organisasi dan Jam Belajar**

Repositori ini berisi seluruh dokumentasi, kode, data olahan, serta poster presentasi untuk memenuhi Tugas Besar Mata Kuliah **Analisis Data Statistika (ADS)** Institut Teknologi Sumatera.

Proyek ini bertujuan menguji apakah terdapat hubungan antara **keterlibatan organisasi mahasiswa** dengan **intensitas jam belajar per minggu**, menggunakan metode **statistika nonparametrik** (Uji Chi-Square Independensi).

#  **Cara Menjalankan Script**

1.  Pastikan kamu sudah meng-install **R** dan **RStudio**.

2.  Download repositori ini atau jalankan:
   
`git clone https://github.com/[username]/ADS_5_RA.git` 

3.  Masuk ke folder kode:
    

`cd code` 

4.  Buka file:
    

`codeR_5_RA.R` 

5.  Pastikan file dataset ada di folder:
    

`/data/ads-dataset.csv` 

6.  Jalankan seluruh script secara berurutan di RStudio:
    

`source("codeR_5_RA.R")` 

7.  Hasil analisis, grafik, tabel kontingensi, dan output uji statistik akan muncul di folder:
   
`/output/`

# **Paket R yang Digunakan**

Proyek ini menggunakan paket-paket berikut:

`library(dplyr) library(readr) library(stringr) library(ggplot2)` 



|Paket         | Fungsi Utama |
|**dplyr**  |pembersihan & manipulasi data|
| **readr** |membaca file CSV / dataset |
| **stringr**| membersihkan & mengekstrak data teks |
|**ggplot2**|visualisasi grafik|

# 📁 **Struktur Repositori**

Repositori ini mengikuti struktur yang ditentukan pada Tugas Besar ADS:

`ADS_5_RA/
│
├── data/
├── code/
├── output/
├── poster/
└── README.md
# 📑 **Penjelasan Singkat Dataset**

Dataset berasal dari **Survei Karakteristik Mahasiswa ITERA 2025** yang dibagikan melalui Google Form dan terdiri dari berbagai variabel profil mahasiswa.

Dalam penelitian ini, kami hanya menggunakan dua variabel utama:

### 1️⃣ **Keterlibatan Organisasi**

Jenis keterlibatan mahasiswa dalam organisasi kampus, berisi kategori seperti:

-   “Tidak Terlibat”
    
-   “Kurang Aktif”
    
-   “Aktif”
    

### 2️⃣ **Rata-rata Belajar Perminggu (dalam jam)**

Data dalam bentuk teks bebas (misal: “6 jam per hari”, “20 jam/minggu”).  
Kami membersihkan dan menyatukan menjadi tiga kategori:

-   **< 5 jam / minggu**
    
-   **5–10 jam / minggu**
    
-   **> 10 jam / minggu**
    

Dataset kemudian melalui tahap:

✔ cleaning  
✔ standardisasi kategori  
✔ sampling (untuk visualisasi)  
✔ analisis uji Chi-Square

----------

# 🧪 **Ringkasan Metode Analisis**

-   Cleaning data teks → 
    
-   Kategorisasi jam belajar → 3 grup
    
-   Standardisasi keterlibatan organisasi
    
-   Tabel kontingensi
    
-   Uji **Chi-Square Independensi** 
    
-   Visualisasi distribusi menggunakan barplot
    


----------

# 🙌 **Kontributor**

Kelompok 5 – Kelas RC
Mata Kuliah Analisis Data Statistika – Itera 2025/2026
