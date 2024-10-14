---
title: Aljabar boolean

---

## Aljabar boolean dan Gerbang logika

Aljabar Boolean adalah sistem matematika yang bekerja dengan dua nilai, yaitu True (1) dan False (0), serta menggunakan operator logika untuk manipulasi ekspresi logika. Aljabar Boolean merupakan dasar dalam desain dan analisis sirkuit digital, pemrograman komputer, serta sistem logika.

Aljabar boolean secara luas digunakan untuk menganalisis dan menyederhanakan sirkuit digital atau gerbang logika. Teori ini telah menjadi dasar dalam pengembangan sistem digital elektronika modern. Aljabar boolean juga sering digunakan dalam teori himpunan dan statistik.

Bahkan pada setiap bahasa pemrograman modern, Boolean dianggap sebagai salah satu tipe data dasar dimana hanya memiliki 2 nilai, yaitu true dan false.
Kaidah-kaidah Hukum Aljabar Boolean

Terdapat 11 kaidah hukum Aljabar Boolean, yakni

Berikut adalah penjelasannya:

1. Hukum Komutatif

Hukum komutatif menyatakan bahwa penukaran urutan variabel tidak memiliki efek pada output dari rangkaian logika.
A . B = B . A
A + B = B + A

2. Hukum Asosiatif

Hukum ini menyatakan bahwa operasi logika dapat dilakukan dalam urutan apa pun ketika prioritas variabelnya sama, terlepas dari adanya pengelompokan variabel dalam suatu persamaan.

( A . B ) . C = A . ( B . C )
( A + B ) + C = A + ( B + C)

3. Hukum Distributif

Hukum distributif menjelaskan bahwa variabel input pada operasi aljabar boolean dapat disebarkan atau difaktorkan keluar dari ekspresi tanpa mengubah output suatu rangkaian logika.

A . ( B + C) = (A . B) + (A. C)
A + (B . C) = (A + B) . ( A + C)
4. Hukum Absorbsi

Hukum ini memungkinkan pengurangan ekspresi logika rumit menjadi lebih sederhana dengan menyerap suku-suku serupa.

A + (A . B) = A
A . (A + B) = A

5. Hukum Identitas

Dalam  matematika, identitas adalah pernyataan yang benar untuk semua kemungkinan nilai dari variabel.

Dalam Aljabar Boolean, hukum identitas menyatakan bahwa variabel apa pun yang dijumlahkan dengan nilai 0 atau false akan menghasilkan nilai variabel itu sendiri. 

Hal ini juga berlaku apabila sebuah variabel dikalikan dengan 1 atau nilai true maka akan mengembalikan nilai variabel itu sendiri.
A + 0 = A
A . 1 = A

6. Hukum Idempoten

Hukum idempoten menyatakan bahwa menggabungkan suatu variabel dengan dirinya sendiri baik dengan operasi penambahan (OR) atau perkalian logika (AND) akan menghasilkan nilai yang setara dengan variabel tersebut.

A + A = A
A . A = A

7. Hukum Komplemen

Hukum komplemen menyatakan bahwa variabel input yang dijumlahkan dengan invers dari variabel tersebut akan menghasilkan nilai 1 atau true, sedangkan jika dilakukan operasi perkalian menghasilkan nilai 0 atau false.

A + A' = 1
A . A' = 0

8. Hukum Dominasi

Hukum dominasi menyatakan bahwa dalam suatu konjungsi atau operasi perkalian, suatu nilai kebenaran akan selalu mendominasi.

A . 0 = 0
A . 1 = 1

9. Hukum Involusi (Negasi Ganda)

Dalam Aljabar Boolean, hukum involusi menyatakan bahwa negasi ganda pada variabel input menghasilkan output variabel itu sendiri.

(A')' = A

10. Hukum De Morgan

Dua teorema penting yang banyak digunakan dalam aljabar Boolean adalah hukum I De Morgan dan hukum II De Morgan. Kedua teorema ini digunakan untuk mengubah ekspresi Boolean.

Teorema ini pada dasarnya membantu untuk mengurangi ekspresi boolean yang diberikan dalam bentuk yang disederhanakan.

Hukum I De Morgan

Hukum pertama menyatakan bahwa komplemen perkalian variabel sama dengan jumlah komplemen individu variabelnya.

(A.B)’ = A’ + B’

Hukum II De Morgan

Hukum kedua menyatakan bahwa komplemen dari penjumlahan variabel sama dengan perkalian dari komplemen individualnya terhadap suatu variabel.

(A+B)’ = A’ . B’

11. Hukum Inversi

Hukum inversi menjelaskan bahwa komplemen dari nilai kebenaran adalah invers dari nilai tersebut.

0' = 1
1' = 0



## Gerbang logika 
adalah perangkat yang melakukan operasi logika dengan menggunakan aljabar Boolean, suatu sistem matematika yang digunakan untuk menganalisis dan menyederhanakan ekspresi logika.
Gerbang Logika Dasar dalam Konteks Aljabar Boolean
Gerbang NOT
Gerbang NOT, atau gerbang inverter, membalik logika masukan. Tanda lingkaran kecil pada keluaran gerbang merupakan tanda pembalik.

Notasi Boolean untuk gerbang NOT adalah adanya garis di atas suatu variabel. Misalnya, NOT A dinotasikan sebagai \( \overline{A} \). Notasi lain untuk NOT A adalah \( A’ \), \( !A \), dan \( \sim A \).


| A | Y=A | 
| -------- | -------- |
| 0   | 1    | 
|1    |0     |

Gerbang OR
Output dari gerbang OR akan bernilai 1 jika salah satu dari inputnya adalah 1. Dalam notasi Boolean, gerbang OR dilambangkan dengan simbol ( + ). Operasi OR antara A dan B dinyatakan sebagai ( A + B ).



| A | B | Y = A+B |
| -------- | -------- | -------- |
| 0    | 0     | 0    |
|0     |1      | 0    |
|1     |0      |0     |
|1     | 1     |1     |

Gerbang AND
Output dari gerbang AND akan bernilai 1 hanya jika semua inputnya bernilai 1. Dalam notasi Boolean, gerbang AND dilambangkan dengan simbol ( . ) (kali). Operasi AND antara A dan B dinyatakan sebagai ( A \C_B ) dan tabel pembuktiannya sama dengan gerbang OR

| A | B | Y = A.B |
| -------- | -------- | -------- |
| 0    | 0     | 0     |
|0     |1      |0      |
|1     |0      |0      |
|1     |1      |1      |

Gerbang NOR

Gerbang NOR (NOT-OR) dapat dibentuk dari gabungan gerbang OR dan NOT. Gerbang NOR menghasilkan output 1 hanya jika semua inputnya adalah 0. Jika salah satu atau lebih input bernilai 1, maka outputnya akan menjadi 0.



| A        | B        | A+B      | Y= A+B|
| -------- | -------- | -------- | ------
| 0     | 0     | 0     |1       |
|0      |1      |1      |0       |
|1      |0      |1      |0
|1      |1      |1      |0

Gerbang NAND
Gerbang NAND (NOT-AND) dibentuk dari gerbang AND dan NOT. Gerbang NAND menghasilkan output 0 hanya jika semua inputnya adalah 1. Sebaliknya, jika salah satu atau lebih inputnya adalah 0, outputnya akan menjadi 1.



| A | B | Y = AB |
| -------- | -------- | -------- |
| 0    |0     | 1     |
|0     |1     |1
|1     |0     |1
|1     |1     |0


Referensi :https://www.trivusi.web.id/2022/08/aljabar-boolean.html?m=1
https://inovasi.ac.id/wiki/prinsip-gerbang-logika/





