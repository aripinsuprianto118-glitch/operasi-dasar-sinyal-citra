# operasi-dasar-sinyal-citra

# Eksperimen Operasi Dasar pada Sinyal dan Citra

Nama: Aripin suprianto
Mata Kuliah: Pengenalan Pengolahan Sinyal Digital

## 1. Deskripsi Singkat Project
Project ini berisi implementasi eksperimen dari operasi fundamental pada sinyal diskrit 1D dan citra digital 2D menggunakan bahasa pemrograman Python. Eksperimen ini mencakup penerapan operasi dasar (penjumlahan, penggeseran/shifting, dan amplifikasi) serta pembuktian matematis secara komputasional terkait konsep sistem linier, yaitu pengujian sifat homogenitas dan additivitas.

## 2. Library yang Digunakan
Project ini berjalan menggunakan beberapa library utama di ekosistem Python:
 `NumPy` - Untuk komputasi array dan manipulasi matriks matematis.
 `Matplotlib` - Untuk visualisasi plot sinyal diskrit 1D dan histogram citra.
 `OpenCV` (`cv2`) - Untuk pembacaan, manipulasi, dan transformasi spasial citra 2D.
`SciPy` - Untuk dukungan operasi saintifik tambahan.

## 3. Cara Menjalankan Notebook
Ikuti langkah-langkah berikut untuk menjalankan eksperimen secara lokal:
1. Clone repository ini ke komputer lokal Anda: 
   `git clone https://github.com/USERNAME_GITHUB_ANDA/operasi-dasar-sinyal-citra.git`
2. Buka terminal/command prompt dan arahkan ke direktori project.
3. Install semua dependencies yang dibutuhkan dengan perintah: 
   `pip install -r requirements.txt`
4. Buka Jupyter Notebook dengan menjalankan perintah `jupyter notebook` atau upload file `.ipynb` ke Google Colab.
5. Jalankan sel kode secara berurutan dari atas ke bawah.

## 4. Struktur Folder Project
```text
operasi-dasar-sinyal-citra/
├── notebook/
│   └── operasi_sinyal_citra.ipynb
├── images/
│   ├── citra1.png
│   ├── citra2.png
│   └── (dan file gambar screenshot lainnya)
├── report/
│   └── laporan.pdf
├── README.md
└── requirements.txt
