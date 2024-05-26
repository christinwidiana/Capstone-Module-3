## **Latar Belakang**

Daegu adalah kota terbesar keempat di Korea Selatan, yang memiliki populasi besar dan permintaan tinggi akan perumahan. Populasi terdaftar sebanyak 2.412.642 orang per Desember 2021. Per Desember 2021, jumlah total rumah tangga adalah 1.063.893, meningkat 0,7% (7.266 rumah tangga) dibandingkan dengan jumlah rumah tangga pada Desember 2020 (1.056.627). Rata-rata populasi per rumah tangga adalah 2,24. Dengan luas wilayah/populasi 883,57 km² / 2.464.002 orang (per 30 November 2018). Mengutip dari halaman web. [Daegu Population](https://www.daegu.go.kr/english/index.do?menu_id=00939612).

Permintaan yang tinggi terhadap perumahan di Daegu mendorong perkembangan pasar apartemen yang signifikan. Sebagai salah satu pusat ekonomi utama, Daegu menawarkan berbagai fasilitas dan aksesibilitas yang menarik bagi penduduknya. Pasar apartemen di Daegu memainkan peran penting dalam ekonomi lokal, dengan harga properti yang dipengaruhi oleh berbagai faktor seperti lokasi, aksesibilitas, fasilitas, dan karakteristik bangunan.

Memahami faktor-faktor yang mempengaruhi harga jual apartemen sangat penting bagi pengembang properti, pembeli, penjual, dan investor. Dengan memahami dinamika pasar dan faktor-faktor penentu harga, para pemangku kepentingan dapat membuat keputusan yang lebih baik dalam menentukan harga jual yang optimal dan menguntungkan.


## **Permasalahan Bisnis**

Masalah bisnis ini menyoroti pentingnya pemahaman mendalam tentang dinamika harga pasar dan faktor-faktor yang mempengaruhinya, sehingga memungkinkan pemilik apartemen untuk menetapkan harga optimal yang menarik pembeli sambil mencapai keuntungan yang wajar.

Tujuan dari analisis ini adalah untuk mengidentifikasi dan memahami faktor-faktor kunci yang mempengaruhi harga jual apartemen di Daegu. Dengan demikian, kita dapat memberikan wawasan yang berharga bagi para pemangku kepentingan di pasar properti, membantu mereka membuat keputusan yang lebih baik.

Mengingat interaksi kompleks dari berbagai faktor seperti lokasi, aksesibilitas ke transportasi umum, ketersediaan fasilitas terdekat, dan karakteristik apartemen, para pemangku kepentingan di pasar real estat memerlukan pemahaman mendetail untuk membuat keputusan yang tepat. Masalah bisnis ini dapat dinyatakan sebagai: **Bagaimana faktor-faktor seperti lokasi (dekat dengan stasiun kereta bawah tanah), ukuran apartemen, jumlah fasilitas di apartemen, dan tahun konstruksi mempengaruhi harga jual?**

## **Tujuan**

Tujuan utama dari analisis ini adalah sebagai berikut:

1. **Mengidentifikasi Penentu Utama Harga Apartemen:**

2. **Menganalisis Pengaruh Karakteristik Apartemen:**

3. **Mengembangkan Model Prediktif:**

4. **Memberikan Wawasan yang Dapat Ditindaklanjuti:**



Dengan mencapai tujuan-tujuan ini, kami bertujuan untuk meningkatkan pemahaman tentang faktor-faktor yang mempengaruhi harga jual apartemen dan menyediakan alat serta wawasan yang berharga untuk pengambilan keputusan di pasar real estat. Menggunakan model regresi untuk memprediksi harga jual berdasarkan karakteristik apartemen dapat sangat berguna bagi pengembang dan agen real estat untuk menilai nilai suatu properti.

## **Stakeholder**

**Agen real estate** dapat menggunakan analisis ini untuk memberi saran kepada klien mereka tentang waktu yang tepat untuk menjual atau membeli properti berdasarkan harga pasar yang diprediksi. Pengetahuan ini membantu dalam negosiasi harga dan menargetkan calon pembeli dengan lebih efektif.

## **Pendekatan Analitik**

Untuk mengatasi masalah dan mencapai tujuan yang telah ditetapkan, pendekatan analitik berikut akan dilakukan:

1. **Pra-pemrosesan Data:**

- Pembersihan Data: Menangani nilai yang hilang, memperbaiki ketidakkonsistenan, dan memastikan data dalam format yang dapat digunakan.
- Rekayasa Fitur: Membuat fitur baru atau memodifikasi fitur yang ada untuk meningkatkan analisis, seperti mengkategorikan stasiun kereta bawah tanah berdasarkan jarak atau menormalkan variabel numerik.

2. **Analisis Data Eksploratif (EDA):**

- Statistik Deskriptif: Merangkum fitur dasar dari dataset, termasuk kecenderungan sentral, dispersi, dan bentuk distribusi data.
- Analisis Korelasi: Mengidentifikasi hubungan antara variabel menggunakan matriks korelasi dan plot sebaran untuk menentukan seberapa kuat variabel terkait dengan harga jual apartemen.
- Visualisasi: Menggunakan berbagai teknik visualisasi (misalnya, histogram, plot kotak, diagram batang) untuk mendapatkan wawasan tentang distribusi data dan hubungan variabel.

3. **Analisis Statistik:**

- Analisis Regresi: Melakukan regresi linier berganda untuk mengukur dampak variabel yang berbeda terhadap harga jual apartemen. Ini akan membantu memahami signifikansi dan ukuran efek dari setiap faktor.
- ANOVA dan Pengujian Hipotesis: Melakukan analisis varians (ANOVA) dan pengujian hipotesis lainnya untuk menentukan signifikansi statistik dari variabel kategoris dan dampaknya terhadap harga.

4. **Pemodelan Prediktif:**

- Pengembangan Model: Mengembangkan model prediktif menggunakan algoritma pembelajaran mesin sepertilinear regression, decision trees, random forests, dan gradient boosting machines.
- Evaluasi Model: Mengevaluasi model menggunakan metrik seperti R-squared, Mean Absolute Error (MAE), dan Root Mean Squared Error (RMSE) untuk menilai kinerja dan akurasinya.
- Validasi Model: Melakukan validasi silang untuk memastikan ketahanan dan generalisasi model prediktif.

5. **Wawasan dan Rekomendasi:**

- Interpretasi Hasil: Menganalisis keluaran dari analisis statistik dan model prediktif untuk mendapatkan wawasan yang dapat ditindaklanjuti.
- Rekomendasi Strategis: Memberikan rekomendasi berdasarkan temuan untuk membantu pemangku kepentingan membuat keputusan yang tepat terkait investasi properti, pengembangan, dan strategi penjualan di pasar apartemen Daegu.

Dengan mengikuti pendekatan analitik yang terstruktur ini, kami bertujuan untuk menyelidiki secara menyeluruh faktor-faktor yang mempengaruhi harga jual apartemen di Daegu, mengembangkan model prediktif yang akurat, dan memberikan wawasan yang berharga bagi pemangku kepentingan.

## **Evaluasi Metrik**

Untuk mengevaluasi kinerja dan akurasi model prediktif kami, metrik-metrik berikut akan digunakan:

1. **R-squared (R²):** koefisien determinasi, mengukur proporsi varians dalam variabel dependen (harga jual apartemen) yang dapat dijelaskan oleh variabel independen dalam model.

2. **Mean Absolute Error (MAE):** mengukur rata-rata perbedaan absolut antara nilai yang diprediksi dan nilai aktual. Ini adalah rata-rata dari kesalahan absolut.

3. **Root Mean Squared Error (RMSE):** akar kuadrat dari rata-rata perbedaan kuadrat antara nilai yang diprediksi dan nilai aktual. Ini memberikan penalti lebih besar pada kesalahan yang lebih besar dibandingkan dengan MAE.
  
4. **Mean Absolute Percentage Error (MAPE):** Untuk mengukur rata-rata perbedaan persentase absolut antara nilai yang diprediksi dan nilai aktual, memberikan kesalahan dalam bentuk persentase.

5. **Cross-Validation Scores:** Validasi silang melibatkan pembagian data menjadi set pelatihan dan validasi beberapa kali untuk menilai kinerja dan generalisasi model.


Dengan menggunakan metrik evaluasi ini, diharapkan dapat digunakan untuk menilai secara komprehensif akurasi dan keandalan model prediktif, memastikan evaluasi tersesbut dapat memberikan wawasan yang berharga dan dapat ditindaklanjuti bagi stakeholder di pasar apartemen Daegu.

# **Data Understanding**
    
<p><div class=pull-left>
<p><div class="text-align:justify">
     
|Nama Kolom                     |Deskripsi                                     |  
|--------------------------------|------------------------------------------------|
|Hallway Type                    | Tipe Apartement                                 |
|TimeToSubway                    | Waktu yang dibutuhkan ke stasiun kereta bawah tanah terdekat     |
|SubwayStation                   | Nama stasiun kereta bawah tanah terdekat         |
|N_FacilitiesNearBy(ETC)         | Jumlah fasilitas terdekat                |
|N_FacilitiesNearBy(PublicOffice)| Jumlah fasilitas kantor publik terdekat |
|N_SchoolNearBy(University)      | Jumlah universitas terdekat              |
|N_Parkinglot(Basement)          | Jumlah tempat parkir                 |
|YearBuilt                       | Tahun apartemen dibangun               |
|N_FacilitiesInApt               | Jumlah fasilitas di apartemen          |
|Size(sqft)                      | Ukuran apartemen (dalam kaki persegi)            |
|SalePrice                       | Harga apartemen (Won)                      |
<br>
