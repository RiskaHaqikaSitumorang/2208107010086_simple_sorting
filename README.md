# Cara Menjalankan Kode Program

1. Pastikan Anda memiliki kompiler C yang terinstal di sistem Anda.
2. Salin kode program yang diberikan ke dalam sebuah file dengan ekstensi .c, misalnya 2208107010086_simple_sorting.c
3. Buka terminal atau command prompt.
4. Navigasikan ke direktori tempat Anda menyimpan file  2208107010086_simple_sorting.c menggunakan perintah cd.
5. Compile program menggunakan perintah berikut:
   gcc  2208107010086_simple_sorting.c -o  2208107010086_simple_sorting
   Pastikan tidak ada pesan kesalahan saat kompilasi.
6. Jalankan program dengan mengetikkan nama file eksekusi yang telah Anda tentukan, misalnya:
   ./ 2208107010086_simple_sorting
7. Tunggu hingga program menyelesaikan pengujian dan pengurutan. Hasil eksekusi akan ditampilkan di layar.

# Fungsi yang Digunakan dalam Kode Program

1. generateNumbers(int *arr, int n): Fungsi ini digunakan untuk menghasilkan array of integers dengan nilai acak dari 0 hingga 
   999999.
2. bubbleSort(int *arr, int n): Fungsi ini mengurutkan array menggunakan algoritma Bubble Sort
3. selectionSort(int *arr, int n): Fungsi ini mengurutkan array menggunakan algoritma Selection Sort.
4. insertionSort(int *arr, int n): Fungsi ini mengurutkan array menggunakan algoritma Insertion Sort.
5. writeUnsortedToFile(int *arr, int start, int end, char *filename): Fungsi ini menulis elemen-elemen array yang belum 
   diurutkan ke dalam sebuah file dengan nama yang ditentukan.
6. writeUnsortedToFile(int *arr, int start, int end, char *filename): Fungsi ini menulis elemen-elemen array yang belum 
   diurutkan ke dalam sebuah file dengan nama yang ditentukan.
7. main(): Fungsi utama program yang mengatur pengujian dan pengurutan array dengan tiga algoritma yang berbeda (Bubble Sort, 
   Selection Sort, Insertion Sort) dengan berbagai ukuran array.
