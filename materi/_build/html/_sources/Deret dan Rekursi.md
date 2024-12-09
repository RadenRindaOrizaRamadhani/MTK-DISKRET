---
title: Deret dan Rekursi

---

# Deretan
Deretan adalah suatu urutan atau susunan elemen atau objek yang disusun secara teratur berdasarkan suatu aturan tertentu. Elemen dalam deretan biasanya berupa angka, huruf, simbol, atau objek lainnya, dan urutannya dapat didasarkan pada pola, nilai, atau hubungan tertentu

Definisi: Sebuah deretan adalah fungsi dari subset suatu himpunan bilangan bulat (biasanya N atau P) ke sebuah himpunan S.
N = {1, 2, 3, 4, … }
   S misalnya {2, 4, 6, 8, …},   {1/3, 1/5, 1/7, …},  dsb

- Notasi deretan: {an}
- Deretan umumnya dinyatakan dalam suatu formula, misalnya:
	an = 2n
	an = 1/n
	an = 7 – 3n


Dalam konteks matematika, deretan sering merujuk pada barisan bilangan, yaitu kumpulan bilangan yang disusun dalam suatu pola tertentu.
 Misalnya:
Deretan bilangan ganjil: 1,3,5,7,…
Deretan bilangan genap: 2,4,6,8,…
Deretan bilangan yang membentuk deret aritmetika: 3,6,9,12....

## Contoh-contoh deretan dan formulanya:

1. Deret Aritmetika
Deret dengan pola kenaikan atau penurunan tetap.
- Contoh: 2,5,8,11,14,…
-  Rumus suku ke-n: 𝑈𝑛=𝑎+(𝑛−1)⋅𝑏
Di mana:
𝑎: suku pertama
𝑏: beda (selisih antar suku)
𝑛: nomor suku yang dicari

2.Deret Geometri
Deret dengan pola kelipatan tetap.
- Contoh: 3,6,12,24,48,…
- Rumus suku ke-n  𝑈𝑛=𝑎⋅𝑟^((𝑛−1) )
Di mana:
 𝑎: suku pertama 
 𝑟: rasio (perbandingan antar suku
 𝑛: nomor suku yang dicari
 
3.Deret Bilangan Kuadrat
Deret dengan pola nilai berupa kuadrat bilangan bulat.
- Contoh: 1,4,9,16,25,…
- Rumus suku ke-n: 𝑈𝑛=𝑛^2

4.Deret Bilangan Kubik
Deret dengan pola nilai berupa kubik bilangan bulat.
- Contoh: 1,8,27,64,125,…
- Rumus suku ke-n: 𝑈𝑛=𝑛^3

5.Deret Fibonacci
Deret dengan pola di mana setiap suku merupakan jumlah dua suku sebelumnya.
- Contoh: 0,1,1,2,3,5,8,…
- Rumus suku ke-n (rekursif): 𝐹𝑛 =𝐹(𝑛−1)+𝐹_(𝑛−2),𝐹_0=0,𝐹_1=1

6.String 
adalah deretan berhingga karakter berbentuk
		a1,a2,a3,a4,…an

    Panjang string S adalah jumlah karakter di dalam string tersebut
     
    Contoh:  informatika adalah string dengan panjang 11 karakter
	         10100101 adalah string biner dengan panjang 8 bit

String kosong dilambangkan dengan , panjangnya = 0

### Penjumlahan deretan
Jumlah deretan 
	am, am+1, am+2, …, an
  adalah
	 am + am+1 + am+2 + … + an
  atau dalam notasi sumasi:
	∑_(𝑘=n)^m▒𝑎_𝑘   
   
    k adalah indeks summasi, 
    m adalah batas bawah indeks,
    n adalah batas atas indeks

Contoh 2: Berapa nilai ![image](https://hackmd.io/_uploads/HkWCJEe71x.png)

Jawaban: 
	![image](https://hackmd.io/_uploads/B1N_ZNeQJg.png): 12 + 22 + 32 + 42 + 52 = 1 + 4 + 9 + 16+ 25 =55


Contoh 3: Batas bawah sumasi kadangkala perlu digeser agar dapat dijumlahkan dengan sumasi lain yang memiliki batas bawah berbeda. Pada contoh 2 di atas batas bawah digeser dari 1 menjadi 0, akibatnya:
![image](https://hackmd.io/_uploads/SJMZzNgQyg.png)![image](https://hackmd.io/_uploads/HycQfVeQ1x.png)


	 


Contoh 4: Sumasi dapat dipecah dengan membagi dua indeksnya, misalnya
![image](https://hackmd.io/_uploads/rJn9f4xQye.png)![image](https://hackmd.io/_uploads/rJ-TM4l7Jl.png)

Contoh 5: Hitung nilai ![image](https://hackmd.io/_uploads/rklu4NgX1g.png)

Jawaban:
![image](https://hackmd.io/_uploads/SkI9VExQJl.png)

 Gunakan rumus                                                  :

![image](https://hackmd.io/_uploads/ByfmrNgmyx.png)

### Sumasi ganda
Di dalam algoritma, kita perlu menghitung berapa kali suatu operasi tertentu dilakukan di dalam sebuah kalang bersarang (nested loop). Penjumlahan semua operasi di dalam kalang bersarang dinyatakan dalam bentuk sumasi ganda.

contoh:![image](https://hackmd.io/_uploads/Hyf2SNl7Jg.png)
Untuk menghitung sumasi ganda, mula-mula ekspansi sumasi terdalam, lalu  dilanjukan dengan sumasi terluar:
![image](https://hackmd.io/_uploads/BJ-1U4lXke.png)

Contoh penggunaan: Berapa kali operasi + dilakukan di dalam algoritma di bawah ini? 
![image](https://hackmd.io/_uploads/SyKV8NgQke.png)
Penyelesaian:
Operasi + terdapat di dalam pernyataan x = x + 2
Operasi ini dilakukan satu kali pada setiap pengulangan
Jumlah seluruh operasi + adalah:
![image](https://hackmd.io/_uploads/rkCdUExXyl.png)


# Rekursi
* Sebuah objek dikatakan rekursif  (recursive) jika ia didefinisikan dalam terminologi dirinya sendiri. 

* Proses mendefinisikan objek dalam terminologi dirinya sendiri disebut rekursi (recursion).

Perhatikan tiga buah gambar pada tiga slide berikut ini.

* objek fraktal adalah contoh bentuk rekursif
![image](https://hackmd.io/_uploads/S1bShSgQyg.png)![image](https://hackmd.io/_uploads/B1SI3Sx7yl.png)

#### fungsi rekursif 
Fungsi rekursif didefinisikan oleh dua bagian:
 (i)  Basis 
Bagian yang berisi nilai fungsi yang terdefinisi secara eksplisit. 
Bagian ini juga sekaligus menghentikan rekursif (dan memberikan sebuah nilai yang terdefinisi pada fungsi rekursif).
 
 (ii)  Rekurens
Bagian ini mendefinisikan fungsi dalam terminologi dirinya sendiri. 
Berisi kaidah untuk menemukan nilai fungsi pada suatu input dari nilai-nilai lainnya pada input yang lebih kecil. 

Contoh :  Misalkan f didefinsikan secara rekusif sbb
![image](https://hackmd.io/_uploads/r14SaSgm1x.png)
Tentukan nilai f(4)!
![image](https://hackmd.io/_uploads/HkkuaHeQye.png)

Contoh : Nyatakan n! dalam definisi rekursif
solusi:![image](https://hackmd.io/_uploads/SygC6HxQ1g.png)
Misalkan f(n) = n! ,maka  
![image](https://hackmd.io/_uploads/HkYN0Sx7yg.png)
![image](https://hackmd.io/_uploads/B1GI0HgQJl.png)

![image](https://hackmd.io/_uploads/rJmt0BlX1x.png)
![image](https://hackmd.io/_uploads/rkJoCSe7ke.png)
soal:

1. Definisikan an secara rekursif, yang dalam hal ini a adalah bilangan riil tidak-nol dan n adalah bilangan bulat tidak-negatif.

2. Nyatakan a b secara rekursif, yang dalam hal ini a dan b adalah bilangan bulat positif.

solusi:
1.![image](https://hackmd.io/_uploads/SkEPl8lQJg.png)

sehingga:![image](https://hackmd.io/_uploads/S1YueLgX1e.png)

2.![image](https://hackmd.io/_uploads/rJSilUxmJg.png)
lalu:![image](https://hackmd.io/_uploads/ByNkWUlXJl.png)

### Struktur Rekursif
* Struktur data yang penting dalam komputer adalah pohon biner (binary tree). 
![image](https://hackmd.io/_uploads/BkBBb8xmJl.png)
* Simpul (node) pada pohon biner mempunyai paling banyak dua buah anak.

* Jumlah anak pada setiap simpul bisa 1, 2, atau 0.

* Simpul yang mempunyai anak disebut simpul cabang (branch node) atau simpul dalam (internal node)

* Simpul yang tidak mempunyai anak disebut simpul daun (leave).

* Pohon biner adalah struktur yang rekursif, sebab setiap simpul mempunyai cabang yang juga berupa pohon. Setiap cabang disebut upapohon (subtree).
![image](https://hackmd.io/_uploads/r1Knm8l7ye.png)
* Oleh karena itu, pohon dapat didefinisikan secara rekursif sebagari berikut:

	(i) Basis: kosong adalah pohon biner
	(ii) Rekurens: Jika T1 dan T2 adalah pohon biner, maka adalah pohon biner
    
    Proses pembentukan pohon biner secara rekursif:
![image](https://hackmd.io/_uploads/Hk8Y4Ll7kg.png)
(ii)![image](https://hackmd.io/_uploads/Bk7oV8gmye.png)
























