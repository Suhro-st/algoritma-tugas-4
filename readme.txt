flowchart

https://drive.google.com/file/d/1cGKZ4M3Sv_SCZn7iNNjUojqCxvdyIsN7/view?usp=drivesdk

pseudocode

// Definisikan matriks a dan b
a = [[1, 1, 2] [2, 3, 2], [1, 2, 1]]
b = [[2, 1, 2], [4, 3, 2], [3, 2, 1]]

// Cek ukuran matriks
IF (jumlah_kolom_a != jumlah_baris_b) THEN
PRINT "Matriks tidak dapat dikalikan"
ELSE
// Hitung hasil perkalian baris pertama
c = a[0][0]*b[0][0] + a[0][1]*b[1][0] + a[0][2]*b[2][0]
d = a[0][0]*b[0][1] + a[0][1]*b[1][1] + a[0][2]*b[2][1]
e = a[0][0]*b[0][2] + a[0][1]*b[1][2] + a[0][2]*b[2][2]
// Tampilkan hasil
PRINT "[" + c + ", " + d + ", " + e + "]"

// Hitung hasil perkalian baris kedua
  f = a[1][0]*b[0][0]+a[1][1]*b[1][0]+a[1][2]*b[2][0]
  g = a[1][0]*b[0][1]+a[1][1]*b[1][1]+a[1][2]*b[2][1]
   h = a[1][0]*b[0][2]+a[1][1]*b[1][2]+a[1][2]*b[2][2]
// Tampilkan hasil
PRINT "[" + f + ", " + g + ", " + h + "]"

// Hitung hasil perkalian baris ketiga
i = a[2][0]*b[0][0]+a[2][1]*b[1][0]+a[2][2]*b[2][0]
 j = a[2][0]*b[0][1]+a[2][1]*b[1][1]+a[2][2]*b[2][1]
 k = a[2][0]*b[0][2]+a[2][1]*b[1][2]+a[2][2]*b[2][2]
// Tampilkan hasil
PRINT "[" + i + ", " + j + ", " + k + "]"
