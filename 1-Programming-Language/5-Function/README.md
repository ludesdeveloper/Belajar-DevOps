# FUNCTION - BAHASA PEMROGRAMAN (PROGRAMMING LANGUAGE)
*Function* atau fungsi mempermudah kita untuk menggunakan ulang apa yang sudah kita buat.
### **Membuat Fungsi Dalam Python**
Untuk membuat fungsi dalam python, kita membutuhkan "def".
```
def fungsiSaya():
  print("Fungsi untuk print")
```
### **Menggunakan Fungsi**
```
fungsiSaya() # cara memanggil fungsi adalah dengan mengetikkan ulang namanya dan menambahkan "()" diujung nama fungsi
```
### **Memberikan Value Terhadap Fungsi**
```
stringSaya = "Fungsi untuk print" # mendefinisikan sebuah string yang bernilai "Fungsi untuk print"
def fungsiSaya(stringValue):      # membuat sebuah fungsi dan membuat variable baru bernama "stringValue" yang mana kita akan melemparkan string terhadapnya
  print(stringValue)              # mengambil value "stringValue" lalu melakukan print 
fungsiSaya(stringSaya)            # memanggil fungsi dan melemparkan nilai "stringSaya"
```
### **LATIHAN**
> Dengan menggunakan bahasa pemrograman python, buatlah sebuah program yang memiliki fungsi untuk membaca dan melakukan print terhadap isi
dari file. Buatlah 2 file, file pertama bernama file_1.txt, dan ketikkan "Saya belajar DevOps 1", file kedua bernama file_2.txt dan ketikkan
"Saya belajar DevOps 2". Buat code agar program bisa membaca dan melakukan print terhadap file_1.txt dan file_2.txt.

