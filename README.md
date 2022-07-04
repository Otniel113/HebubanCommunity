# HebubanCommunity
Mengidentifikasi komunitas di Twitter menggunakan Metode Louvain dengan topik game Heaven Burns Red yang dilakukan bersama Made Indrayana Putra

## Abstrak
Salah satu media sosial yang cukup populer adalah Twitter. Ada banyak cuitan <i>tweet</i> di Twitter dari berbagai pengguna khususnya pada suatu topik tertentu. Dalam pembahasan topik tertentu, terdapat beberapa komunitas terbentuk yang terdiri dari beberapa pengguna. Pada masing-masing komunitas biasanya memiliki pandangan dan pembahasan yang berbeda. Identifikasi komunitas tersebut penting karena membantu untuk lebih mengerti perbedaan pandangan orang-orang terhadap topik tersebut. Salah satu topik tersebut adalah game Heaven Burns Red dengan genre gabungan Visual Novel dan Turn-Based RPG. Dalam penelitian ini telah dibangun analisis jejaring sosial berbentuk graf dan mengidentifikasi komunitas pada jejaring sosial tersebut dengan menggunakan Metode Louvain. Telah didapatkan banyaknya komunitas sebanyak 130 komunitas dengan nilai modularity adalah 0,59.

## Tujuan
Tujuan dalam penelitian ini adalah membangun model jejaring sosial pada topik game Heaven Burns Red dan mengidentifikasi komunitas dalam topik Heaven Burns Red menggunakan Metode Louvain.

## Dataset
Dataset didapatkan dengan melakukan metode crawling pada media sosial Twitter bertopik games Heaven Burns Red dengan menggunakan <i>hashtag</i> #ヘブバン. Tweet yang diambil sebanyak 15000 tweet terbaru dari tanggal 7 April 2022. Banyak data akhir yang berhasil dikumpulkan adalah 14853 karena data yang bernilai error tidak dimasukan ke dalam dataset.

## Hasil
1. Spesifikasi graf
| Parameter | Nilai |
| -- | -- |
| Banyak node | 4367 |
| Banyak edge | 7112 |
| Berarah | Tidak |
| Berbobot | Tidak |
| Multiedge | Tidak |
| Loop | Tidak |
| Jenis graf | Simple graph |

2. Graf jejaring sosial
![Gambar1](https://user-images.githubusercontent.com/57952404/177080634-9e9d0299-2169-426c-90d1-27ecb3801028.png)

3. Graf setelah dilakukan pembagian komunitas
![Gambar2](https://user-images.githubusercontent.com/57952404/177080690-dca15bbe-0ee8-4837-9439-bf618647aaf5.png)

4.Banyaknya anggota masing-masing komunitas
![Gambar3](https://user-images.githubusercontent.com/57952404/177080892-e1372b8f-bfdf-45b7-9a95-785278528c75.png)

## Kesimpulan dan Saran
1. Berdasarkan hasil penelitian yang dilakukan, dapat disimpulkan bahwa telah berhasil dibangun model jejaring sosial berdasarkan tweet dengan menggunakan graf berjenis simple graph yang memiliki banyak node 4367 dan banyak edge 7112, serta telah diidentifikasi komunitas dalam topik Heaven Burns Red menggunakan Metode Louvain berupa banyak komunitas adalah 130 dengan nilai modularity 0,59. 
2. Penelitian ini masih memiliki keterbatasan seperti jenis media sosial adalah Twitter dengan topik game Heaven Burns Red, dan menggunakan Metode Louvain. Saran untuk penelitian selanjutnya adalah dengan melakukan penelitian dengan media sosial yang lain seperti Facebook atau Instagram, menggunakan topik yang berbeda baik masih di bidang game ataupun tidak, dan menggunakan metode pencarian komunitas yang lainnya, seperti Girvan-Newman, Agglomerative Methods, Betweenness Centrality, atau metode yang lainnya.

## Laporan
Untuk laporan lengkap dapat dilihat di: https://www.overleaf.com/read/bjgkcjbpzcmp

## Presentasi
Presentasi dapat dilihat di: https://youtu.be/8mJnbQ--ehg
