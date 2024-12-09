---
title: Probabilitas Diskrit dan Probabilitas Bayesian

---

Naïve Bayes adalah algoritma klasifikasi berbasis probabilitas yang sederhana dan efisien, yang didasarkan pada Teorema Bayes dengan asumsi bahwa semua fitur (variabel) bersifat independen satu sama lain.

## Konsep Utama Naïve Bayes
	
1.	Teorema Bayes:
Naïve Bayes memanfaatkan teorema Bayes untuk menghitung probabilitas suatu kelas  C  berdasarkan fitur  ![image](https://hackmd.io/_uploads/HkiGsTMEye.png)

![image](https://hackmd.io/_uploads/HJhoj6MVyx.png)


2.	Asumsi Independensi:
Naïve Bayes mengasumsikan bahwa semua fitur bersifat independen, sehingga:

![image](https://hackmd.io/_uploads/SyNRjTGVJl.png)


Asumsi ini menyederhanakan perhitungan.


## Langkah Kerja Naïve Bayes
1.	Menghitung Probabilitas Prior:
Probabilitas awal untuk setiap kelas  C  dihitung berdasarkan data pelatihan.
2.	Menghitung Probabilitas Likelihood :
Probabilitas setiap fitur  untuk kelas  C  dihitung.
3.	Membandingkan Probabilitas Posterior:
Probabilitas dihitung untuk setiap kelas, dan kelas dengan probabilitas tertinggi dipilih sebagai prediksi.

## Jenis-Jenis Naïve Bayes
	
1.	Gaussian Naïve Bayes:
Digunakan untuk data kontinu, dengan asumsi bahwa fitur mengikuti distribusi normal (Gaussian).
2.	Multinomial Naïve Bayes:
Cocok untuk data diskret, seperti frekuensi kata dalam teks (digunakan pada pengklasifikasian teks).
3.	Bernoulli Naïve Bayes:
Digunakan untuk data biner, misalnya ketika fitur adalah 0 atau 1.

## Terorema Bayes

* Posterior adalah distribusi probabilitas setelah memperhitungkan data yang diamati. Dalam Bayesian statistics, posterior diperoleh dengan mengalikan prior dan likelihood, kemudian dinormalisasi agar menjadi distribusi probabilitas yang valid.

* Prior adalah informasi awal atau keyakinan tentang parameter sebelum melihat data. Biasanya, prior mencerminkan asumsi awal Anda atau pengetahuan sebelumnya yang Anda miliki tentang parameter yang sedang dikaji.

* Likelihood adalah probabilitas data yang diamati diberikan parameter tertentu. Likelihood berfokus pada hubungan antara parameter dan data yang diamati.



### Kelebihan Naïve Bayes
	
1.	Cepat dan Efisien:
	•	Mudah diimplementasikan, bahkan pada dataset besar.
	•	Cepat dalam pelatihan dan prediksi.
2.	Tidak Membutuhkan Banyak Data:
	•	Berfungsi baik bahkan dengan dataset kecil.
3.	Menangani Banyak Fitur:
	•	Efisien pada data dengan dimensi tinggi.
4.	Akurasi Baik untuk Data Tertentu:
	•	Efektif pada klasifikasi teks (e.g., filter spam, analisis sentimen).

### Kekurangan Naïve Bayes
1.	Asumsi Independensi:
	•	Kinerja bisa menurun jika fitur saling bergantung (karena asumsi independensi tidak valid).
2.	Kesalahan Estimasi Probabilitas Nol:
	•	Jika fitur tertentu tidak muncul dalam kelas tertentu di data pelatihan, probabilitasnya menjadi nol. Solusinya adalah smoothing (contoh: Laplace Smoothing).
3.	Kurang Cocok untuk Data Kompleks:
	•	Tidak selalu kompetitif dengan algoritma yang lebih canggih pada data non-linear atau kompleks.


#### Aplikasi Naïve Bayes
1.	Filter Spam: Mengklasifikasikan email menjadi spam atau bukan spam.
2.	Analisis Sentimen: Menentukan apakah teks (ulasan, tweet) bersifat positif, negatif, atau netral.
3.	Klasifikasi Dokumen: Mengelompokkan dokumen ke dalam kategori tertentu.
4.	Prediksi Penyakit: Memprediksi penyakit berdasarkan data gejala pasien.


#### Contoh Soal Cara Menghitung Terorema Bayes
![image](https://hackmd.io/_uploads/S12O0WmNJl.png)
* Bagaimana kemungkinan/probabilitas usia paruh baya tekanan darah sangat tinggi kemungkinan penyakit Hipertensi (H) atau Tidak (T)

* Hitunglah probabilitas Hipertensi terhadapa usia paruh baya tekanan darah sangat tinggi

* Hitunglah probabilitas Tidak Hipertensi terhadap usia paruh baya tekanan darah sangat tinggi

##### Jawaban

![158349de-2424-4606-b25a-917e01f4f0f6-min](https://hackmd.io/_uploads/rJX3QMQEkg.jpg)


