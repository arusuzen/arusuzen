# Machine Learning
<p>Pembahasan Projek Machine Learning yang dilakukan oleh Mohamed Jafir Ashraf. Projek yang dilakukan berupa memprediksi emisi CO2 yang dikeluarkan dari sebuah mobil menggunakan diagram Polinomial Regression</p>
<a href='https://github.com/MdJafirAshraf'>Berikut adalah GitHub Mohamed Jafir Ashraf</a>
<br>

# Penjelasan
<p>Machine Learning merupakan salah satu penerapan dari kecerdasan buatan atau AI dalam memproses data dan algoritma yang dimasukkan secara otomatis. Algoritma machine learning bekerja dengan mengidentifikasi pola, membuat keputusan, dan memprediksi hasil berdasarkan data historis. Machine learning berfokus pada pengembangan program komputer yang dapat mengakses data dan menggunakannya untuk belajar sendiri.</p>
<p>Projek yang dilakukan berupa prediksi emisi CO2 pada mobil dan dijelaskan secara lengkap di website blog yang disediakan oleh pemilik projek</p>
<p>Secara lengkapnya ada di <a href='https://techyscientists.blogspot.com/search/label/Machine%20learning'>Techy Scientists</a></p>

<p>Berikut penjelasan ringan dan langkah-langkah dari projeknya</p>
<p>Projek menggunakan scikit-learn untuk implementasi polinomial regression di emisi CO2 dari sebuah mobil dan menggunakan model untuk nilai yang tidak diketahui</p>
<p>Daftar isinya berupa:</p>
<ol>
  <li>Setup Environtment</li>
  <li>Persiapan Data</li>
  <li>Analisis Data Eksploratif</li>
  <li>Model Polinomial Regression</li>
  <li>Evaluasi Model</li>
</ol>
<p>Aplikasi yang diperlukan</p>
<ol>
  <li>python</li>
  <li>numpy</li>
  <li>pandas</li>
  <li>matplotlib</li>
  <li>scikit-learn</li>
</ol>
<p>Langkah-langkah</p>
<ol>
  <li>Pemilik projek telah mengunduh beberapa data konsumsi bahan bakar yang berisi peringkat konsumsi bahan bakar spesifik model dan perkiraan emisi karbon dioksida untuk kendaraan tugas ringan baru untuk dijual eceran di negara Kanada.</li>
  <li>Menginput berbagai data dari yang sudah diunduh ke dalam file python</li>
  <li>Membaca data menggunakan pandas</li>
  <li>Informasi data</li>
  <li>Mencari data yang hilang</li>
  <li>
    Mulai analisis data eksploratif pada data kita. Pertama, plot masing-masing fitur ini vs Emisi, untuk melihat seberapa linier hubungannya. Berikut salah satu contoh:
    <img src='https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgASX63xBnF2bkdaJndb9YrvJPasvauPywHFYuuqGXw4ykqeIBCJkDE9_xwFFoRS_Hhk9nUYpTH01y1VnnlQaoSVUPFBuS4aXCZLh8y5LXpJPaHXVXxzIIkmFvOV5CTplrmZNiZPqdKSE2s/w353-h235/engsize.jpg'>
    <p>Ukuran Mesin vs Emisi</p>
  </li>
  <li>Regresi polinomial, di mana hubungan antara variabel bebas x dan variabel terikat y dimodelkan sebagai polinomial derajat ke-n dalam x. Pertama-tama pisahkan datanya. Membuat model, harus membaginya menjadi pelatihan dan pengujian. Model dilatih dengan dataset pelatihan lalu terapkan evaluasi model yang digunakan oleh dataset pengujian.Definisikan data. Koefisien dan Perpotongan dalam regresi linier sederhana, adalah parameter garis kecocokan. Plot garis kecocokan pada data.
    <img src='https://blogger.googleusercontent.com/img/a/AVvXsEjJRfwyx1PNI_dINivu-76RQa54aLBsfszbjXZdJktctnyA_Tw1JLFSCm4r7Z5Ow3x1-QtWSC7PbCJOTwr4Q0mF2WcRQ6apN0CbytqvRf1MYcOcqk08kW1T_Cy-202XAH6QkaYw1Nzf__XSGaSlcK7Fq9KiT2MuA_JFNumHY-WUAS-1K8ZNxOBZjnslNQ=w414-h276'>
  </li>
  <li>Bandingkan nilai aktual dan nilai prediksi untuk menghitung akurasi model regresi. Metrik evaluasi berperan penting dalam pengembangan model, karena memberikan wawasan tentang area yang memerlukan perbaikan
  <ul>
    <li>Kesalahan absolut rata-rata: Ini adalah rata-rata nilai absolut kesalahan. Ini adalah metrik yang paling mudah dipahami karena ini hanyalah kesalahan rata-rata.</li>
    <li>Root Mean Squared Error (RMSE): Ini adalah akar kuadrat dari Mean Square Error</li>
    <li>R-kuadrat bukanlah kesalahan, tetapi merupakan metrik populer untuk akurasi model. Ini menunjukkan seberapa dekat data dengan garis regresi yang disesuaikan. Semakin tinggi R-kuadrat, semakin baik model tersebut sesuai dengan data. Skor terbaik yang mungkin adalah 1,0 dan bisa negatif (karena modelnya bisa lebih buruk).</li>
  </li>
</ol>
<p>Kesimpulan. Pemilik projek memperkirakan emisi CO2 dari berbagai mobil menggunakan regresi polinomial pada konsumsi bahan bakar dan data emisi karbon dioksida dari mobil yang telah diterapkan menggunakan Scikit-learn</p>
