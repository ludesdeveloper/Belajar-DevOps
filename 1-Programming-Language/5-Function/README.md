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
