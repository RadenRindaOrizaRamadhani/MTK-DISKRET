---
title: social network

---

# Social Network Analysis (SNA) 
metode untuk mempelajari dan menganalisis pola hubungan dan interaksi dalam sebuah jaringan sosial. SNA membantu memahami bagaimana individu, kelompok, atau organisasi saling terhubung dan bagaimana struktur jaringan memengaruhi perilaku atau hasil tertentu.
![image](https://hackmd.io/_uploads/By1LZXlQJg.png)

![image](https://hackmd.io/_uploads/BynDZmgQJe.png)
Social network 
terdapat node yang mewakili orang atau individu atau aktor. Relasi  antar objek  dapat dinyatakan dengan link atau edges yang terjadi antara aktor tersebut, Social network terdiri dari banyak aktor yang mempunyai relasi satu sama lain hingga membentuk peta jaringan sosial yang dinyatakan dengan graph.

* Tidak semua node dalam jaringan adalah penting  (aktor)
* Mencari node yang paling penting dalam suatu jaringan
* Centrality adalah penentuan aktor menggunakan ukuran pada Social Network Centrality 

Dalam teori graf dan social network dibagi menjadi empat jenis:
1. degree centrality, 
2. closeness centrality, 
3. betweennes centrality 
4. eigenvector centrality

## 1.Degree Centrality 
adalah salah satu ukuran dalam Social Network Analysis (SNA) yang digunakan untuk menilai tingkat konektivitas suatu node (simpul) dalam sebuah jaringan. Ukuran ini menunjukkan jumlah hubungan langsung yang dimiliki oleh sebuah node, yang merepresentasikan pengaruh atau pentingnya node tersebut dalam jaringan.
* Degree Centrality mengukur jumlah koneksi langsung suatu node dengan node lain.
* Node dengan nilai degree centrality yang tinggi dianggap lebih penting karena terhubung dengan banyak node dalam jaringan.

### degree centrality:![image](https://hackmd.io/_uploads/Sye1NXgXkx.png)
### normalisasi degree centrality:![image](https://hackmd.io/_uploads/HyveEXg7Je.png)

![image](https://hackmd.io/_uploads/rkJFNmxX1x.png)Untuk  node 1, degree centrality adalah 3;
Normalisasi degree centrality adalah  
3/(9-1)=3/8.

## 2. Closeness Centrality 
adalah salah satu ukuran dalam Social Network Analysis (SNA) yang digunakan untuk menilai seberapa dekat atau terhubung suatu node dengan semua node lain dalam jaringan. Ukuran ini mencerminkan kecepatan atau efisiensi suatu node dalam menyebarkan informasi ke seluruh jaringan.
### average distance :
![image](https://hackmd.io/_uploads/HJoVSmxQkl.png)
### closeness centrality:
![image](https://hackmd.io/_uploads/B1Y_BXeXkl.png)
 contoh:
 ![image](https://hackmd.io/_uploads/rJt3rQeXye.png)
![image](https://hackmd.io/_uploads/S1warmxmJe.png)
![image](https://hackmd.io/_uploads/BywCB7xmJl.png)
Node 4  lebih central  dari node 3

### 3.Betweenness Centrality
* Skor betweeness Centrality mewakili seberapa besar informasi yang tersebar dari suatu aktor. Semakin besar skor, artinya aktor tersebut semakin berperan dalam penyebaran informasi 

* Semakin banyak lintasan yang harus melewati persimpangan itu (misal tidak ada jalan alternatif), maka semakin penting arti persimpangan tersebut. Hal ini menandakan seberapa besar suatu node diperlukan sebagai penghubung dalam penyebaran informasi di dalam jaringan

* Ukuran ini juga dapat digunakan untuk mengidentifikasi boundary spanners, yaitu orang atau node yang berperan sebagai penghubung (jembatan) antara dua komunitas

* Menghitung jumlah lintasan terpendek yang melewati suatu node

* Node dengan  betweenness  tinggi  adalah  penting dalam komunikasi dan penyebaran informasi

Betweenness Centrality:
![image](https://hackmd.io/_uploads/BkMlPmgX1l.png)


penjelasan:
![image](https://hackmd.io/_uploads/ByWrwmxQyg.png) Jumlah lintasan terpendek antara s dan t
![image](https://hackmd.io/_uploads/ryOCD7xXke.png)

![image](https://hackmd.io/_uploads/BJqMdQxXJl.png)
![image](https://hackmd.io/_uploads/ByFQO7lm1e.png)
![image](https://hackmd.io/_uploads/rku4d7xXJx.png)
![image](https://hackmd.io/_uploads/BJl8uXemkg.png)
Normalisasi Betweenness Centrality
![image](https://hackmd.io/_uploads/rJ1O_mx7yx.png)




