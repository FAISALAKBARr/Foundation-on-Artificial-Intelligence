# Foundation-on-Artificial-Intelligence
Repository ini berisi source code mengenai penugasan kelompok pada Assignment 1 - Foundation for Artificial Intelligence. Antara lain:
1. Case 1 ("01-Kelompok F-3.ipynb"): 
Program ini adalah sebuah sistem kasir bank yang mengonversi jumlah uang tabungan nasabah ke dalam pecahan uang kertas dan koin yang tersedia di Indonesia.
Input yang diterima adalah nilai tabungan nasabah dalam bentuk integer antara 0 hingga 1 miliar Rupiah.
Program mengatur aturan sebagai berikut:
- Mengutamakan pecahan uang terbesar terlebih dahulu.
- Jika ada sisa saldo yang tidak bisa ditarik (kurang dari 100), sisa tersebut diinformasikan.
- Menghitung total jumlah uang kertas dan koin yang dibutuhkan.
Output: Program mengeluarkan daftar pecahan uang kertas dan koin yang diperlukan serta total masing-masing.

Program pertama bekerja melalui perhitungan matematika untuk pecahan uang, dengan logika pembagian dan pengulangan untuk setiap jenis pecahan yang disediakan.

2. Case 2 ("01-Kelompok F-3.ipynb"): 
Program ini melakukan analisis data Human Resources (HR) pada dataset tertentu, termasuk implementasi penggunaan pandas, analisis gaji, alasan pemutusan hubungan kerja, dan kinerja berdasarkan sumber rekrutmen. Data diambil dari file CSV yang berada di GitHub.
Beberapa pertanyaan analisis yang dijawab dalam program, yakni:
- Distribusi gaji minimum, median, maksimum, dan rata-rata berdasarkan status pernikahan dan jenis kelamin.
- Alasan teratas pemutusan kerja.
- Sumber rekrutmen terbaik berdasarkan kinerja karyawan.
- Jumlah manajer di setiap departemen.
- Rasio pemutusan hubungan kerja berdasarkan gender.
Output: Program ini menghasilkan berbagai visualisasi data seperti scatter plot, bar chart, pie chart, dan box plot, untuk memberikan wawasan visual terhadap data HR.

Program kedua menggunakan fungsi-fungsi agregat groupby dari pustaka Pandas dan fungsi visualisasi dari matplotlib dan seaborn untuk menjawab pertanyaan-pertanyaan analisis data.