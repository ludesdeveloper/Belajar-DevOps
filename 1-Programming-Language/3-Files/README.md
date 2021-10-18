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
read_file = read_file.readlines()
print(read_file)
```