Tower of Hanoi menggunakan Python

Deskripsi

Tower of Hanoi adalah permainan logika yang bertujuan memindahkan semua cakram dari tiang A ke tiang C dengan bantuan tiang B.

Aturan permainan

1. Hanya satu cakram yang boleh dipindahkan dalam satu langkah.
2. Cakram yang lebih besar tidak boleh diletakkan di atas cakram yang lebih kecil.
3. Semua cakram harus dipindahkan dari tiang A ke tiang C.

Algoritma

Program menggunakan metode rekursi, yaitu fungsi memanggil dirinya sendiri untuk menyelesaikan masalah yang lebih kecil.

Langkah penyelesaian:

1. Pindahkan N-1 cakram dari tiang A ke tiang B menggunakan tiang C sebagai bantuan.
2. Pindahkan cakram terbesar dari tiang A ke tiang C.
3. Pindahkan N-1 cakram dari tiang B ke tiang C menggunakan tiang A sebagai bantuan.

Hasil

Untuk 3 cakram, program membutuhkan 7 langkah pemindahan.

Rumus jumlah langkah minimum:
T(n) = 2^n - 1

Keterangan:

* T(n) adalah jumlah langkah minimum.
* n adalah jumlah cakram.

Kesimpulan

Program Tower of Hanoi menerapkan algoritma rekursi untuk memindahkan cakram sesuai aturan permainan dengan jumlah langkah minimum.