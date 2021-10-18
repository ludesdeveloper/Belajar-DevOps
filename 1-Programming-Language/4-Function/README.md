# FILES - BAHASA PEMROGRAMAN (PROGRAMMING LANGUAGE)
Memanipulasi file adalah hal yang sangat sering kita lakukan untuk kebutuhan sehari hari.
### **Membuat File**
```
write_file = open("belajardevops.txt","w") # membuka file dengan mode "w" (write), sehingga kita bisa menulis di dalam file tersebut
write_file.write("Mari Belajar DevOps") # menulis "Mari Belajar DevOps" di dalam file tersebut
write_file.close() # menutup file
```
Di contoh di atas kita menggunakan mode *write* untuk membuat file.
### **Membaca File**
```
read_file = open("belajardevops.txt","r")
read_words = read_file.readlines()
print(read_words)
read_file.close()
```
Di contoh di atas kita menggunakan mode *read* untuk membaca file.
### **LATIHAN**
> Dengan menggunakan bahasa pemrograman python, buat sebuah program yang akan membuat file bernama belajarpython.txt, lalu ketikkan
"Saya suka belajar bahasa pemrograman" didalamnya. Setelah selesai menulis file, perintahkan program untuk membaca kata kata yang ada
di dalam file belajarpython.txt
