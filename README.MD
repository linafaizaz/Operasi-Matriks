//Perkalian Matriks

int[][] matriks1 = {} : menginisialisasi dua array dengan tipe data integer.
int[][] hasilKali = perkalianMatriks(matriks1, matriks2); :  untuk menghitung hasil perkalian matrik 1 dan matriks 2.
System.out.println("Hasil Perkalian Matriks:"); : mencetak teks hasil perkalian matriks.
public static int[][] perkalianMatriks(int[][] matriks1, int[][] matriks2) {} : mendeklarasikan metode perkalian matriks untuk menghitung perkalian matriks.
int baris1 = matriks1.length;
int kolom1 = matriks1[0].length;
int kolom2 = matriks2[0].length;
int[][] hasil = new int[baris1][kolom2];
menentukan jumlah baris dan kolom dari dua matriks lalu membuat matriks hasil dengan jumlah baris dari matriks pertama dan matriks kedua, biasanya untuk perkalian matriks.
for (int i = 0; i < baris1; i++) {}
for (int j = 0; j < kolom2; j++) {}
for (int k = 0; k < kolom1; k++) {}
hasil[i][j] += matriks1[i][k] * matriks2[k][j];
melakukan perkalian dua matriks dengan menjumlahkan hasil perkalian elemen-elemen yang sesuai, menggunakan tiga loop untuk mengiterasi baris, kolom, dan elemen yang dikalikan.
public static void cetakMatriks(int[][] matriks) {}
for (int i = 0; i < matriks.length; i++) {}
for (int j = 0; j < matriks[0].length; j++) {}
System.out.print(matriks[i][j] + " ");
System.out.println(); 
mencetak matriks dengan menggunakan dua loop untuk mengakses elemen dan menampilkannya dalam bentuk baris.

//TransposeMatriks
public static void main(String[] args) {}
int[][] matriks = {}
{6, 7, 5},
{5, 4, 3}
mendeklarasikan dan menginisialisasi sebuah matriks 2x3 dengan elemen.
public static int[][] transposeMatriks(int[][] matriks) {}
int baris = matriks.length;
int kolom = matriks[0].length;
int[][] hasil = new int[kolom][baris];
menyiapkan proses transpose matriks dengan menentukan jumlah baris dan kolom dari matriks awal, lalu membuat matriks hasil dengan jumlah baris dan kolom yang ditukar.
for (int i = 0; i < baris; i++) {}
for (int j = 0; j < kolom; j++) {}
hasil[j][i] = matriks[i][j];
melakukan transpose matriks dengan menukar elemen baris menjadi kolom.
public static void cetakMatriks(int[][] matriks) {}
for (int i = 0; i < matriks.length; i++) {}
for (int j = 0; j < matriks[0].length; j++) {}
System.out.print(matriks[i][j] + " ");
System.out.println();
mencetak elemen matriks dalam bentuk baris,setiap elemen dalam satu baris dipisahkan oleh spasi, lalu pindah ke baris baru setelah setiap baris selesai dicetak.

//menentukan diagonal utama dan diagonal samping
public static void main(String[] args) {}
int[][] matriks = {}
{13, 12, 14},
{1, 2, 3},
{4, 5, 6}
mendeklarasikan matriks berukuran 3x3 dengan elemen-elemen yang sudah ditentukan.
public static void cetakDiagonalUtama(int[][] matriks) {}
for (int i = 0; i < matriks.length; i++) {}
System.out.print(matriks[i][i] + " ");
mencetak elemen pada sebuah matriks, yaitu elemen dengan indeks baris dan kolom yang sama (matriks[i][i]).
public static void cetakDiagonalSamping(int[][] matriks) {}
int n = matriks.length;
for (int i = 0; i < n; i++) {}
System.out.print(matriks[i][n - 1 - i] + " ");
System.out.println();
mencetak elemen pada diagonal samping sebuah matriks persegi, yaitu elemen dengan indeks baris `i` dan indeks kolom `n - 1 - i`.

      
      


        




        
    
