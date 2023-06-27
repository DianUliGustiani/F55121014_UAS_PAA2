# F55121014_UAS_PAA2

A. Analisis Algoritma Bubble Sort dan Insertion Sort
   1. Worst Case:
      - Bubble Sort : Worst case terjadi ketika daftar dalam urutan terbalik.
        Dalam kasus ini, setiap elemen akan bergeser ke posisi yang tepat melalui pertukaran berulang.
        Kompleksitas waktu Bubble Sort dalam worst case adalah O(n^2).
      - Insertion Sort : Worst case terjadi ketika daftar dalam urutan terbalik.
        Dalam kasus ini, setiap elemen harus dimasukkan ke posisi yang tepat melalui pergeseran linier.
        Kompleksitas waktu Insertion Sort dalam worst case juga O(n^2).
   2. Best Case:
      - Bubble Sort: Best case terjadi ketika daftar sudah dalam urutan yang benar.
        Dalam kasus ini, Bubble Sort akan memiliki kinerja terbaik karena hanya perlu melewati iterasi sekali tanpa ada pertukaran yang dilakukan.
        Namun, meskipun daftar sudah terurut, Bubble Sort tetap melakukan perbandingan dan iterasi pada setiap elemen.
        Kompleksitas waktu Bubble Sort dalam best case adalah O(n).
      - Insertion Sort : Best case terjadi ketika daftar sudah dalam urutan yang benar.
        Pada kasus ini, Insertion Sort akan memiliki kinerja terbaik karena hanya perlu membandingkan elemen dengan satu elemen sebelumnya
        sebelum memasukkannya ke posisi yang tepat. Kompleksitas waktu Insertion Sort dalam best case adalah O(n).
   3. Average Case:
      - Bubble Sort : Average case adalah kasus di mana daftar acak disortir.
        Kedua perulangan di Bubble Sort membutuhkan O(n) untuk memindahkan elemen terbesar ke posisi yang benar pada setiap iterasi.
        Sehingga, kompleksitas waktu Bubble Sort dalam average case adalah O(n^2).
      - Insertion Sort : Average case adalah kasus di mana daftar acak disortir.
        Insertion Sort memiliki kompleksitas waktu O(n^2) pada average case, karena pada setiap iterasi,
        pergeseran linier harus dilakukan untuk memasukkan elemen ke posisi yang benar.

B. Analisis Algoritma TSP dan Dijkstra
   1. Worst Case:
      - TSP: worst case terjadi ketika jumlah simpul (n) dalam graf sangat besar.
        Karena algoritma TSP secara eksponensial mencoba semua kemungkinan permutasi jalur, kompleksitasnya adalah O(n!).
        Jadi, semakin banyak simpul, semakin lama waktu yang dibutuhkan untuk menemukan jalur terpendek.
      - Dijkstra: worst case terjadi ketika terdapat banyak simpul dan tepi dalam graf.
        Dalam hal ini, setiap simpul akan dikunjungi dan setiap tepi akan dipertimbangkan. Kompleksitas algoritma Dijkstra adalah O(n^2).
   2. Best Case:
      - TSP: best case terjadi ketika terdapat sedikit simpul dalam graf.
        Dalam kasus ini, algoritma TSP masih mencoba semua kemungkinan permutasi jalur, tetapi jumlah permutasi yang harus
        diperiksa lebih sedikit daripada ketika terdapat banyak simpul.
      - Dijkstra: best case terjadi ketika hanya ada satu simpul dalam graf.
        Dalam hal ini, karena tidak ada tepi lain yang harus dipertimbangkan, algoritma Dijkstra dapat langsung menghasilkan jarak terpendek 0.
   3. Average Case:
      - TSP: Tidak ada kasus rata-rata yang dapat ditentukan secara umum karena kompleksitasnya bergantung pada jumlah simpul dalam graf.
        Namun, secara umum, algoritma TSP memiliki kompleksitas O(n!) yang menjadikannya tidak efisien untuk graf dengan jumlah simpul yang besar.
      - Dijkstra: kompleksitasnya adalah O(n^2). Dalam kasus rata-rata, algoritma Dijkstra memberikan
        kinerja yang baik untuk menemukan jalur terpendek dalam graf dengan jumlah simpul dan tepi yang moderat.
