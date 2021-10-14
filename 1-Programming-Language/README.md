# BAHASA PEMROGRAMAN (PROGRAMMING LANGUAGE)
Kali ini kita akan belajar bahasa pemrograman. Saya memilih python agar lebih mudah, karena memang syntax yang lebih simple, sehingga
lebih mudah untuk dimengerti. 

## **3 Hal Penting Dalam Pemrograman**
Setiap orang punya pendapat berbeda terhadap pemrograman, saya pribadi menganggap 3 hal ini adalah core dari programming.
1. Assignment(Variable)
1. [Assignment(Variable)](#assignment(variable))
2. Condition
3. Loop

## **Assignment(Variable)**
Variable adalah sesuatu yang kita bisa *assign* value terhadapnya.
```
a = 10
```
Pada contoh diatas kita coba mendefiniskan bahwa a adalah 10. Di contoh ini kita melakukan *assignment* dengan tipe integer
```
a = "Ludes Developer"
```
Pada contoh diatas kita coba mendefinisikan bahwa a adalah "Ludes Developer". Di contoh ini kita melakukan *assignment* dengan tipe string
```
a = [1,2,3]
```
Pada contoh di atas kita mendefinisikan bahwa a adalah sebuah list/array yang berisikan tipe data integer
```
a = {"nama":"Seski Ramadhan","pekerjaan":"DevOps Engineer"}
```
Pada contoh di atas kita mendefinisikan bahwa a adalah sebuah dictionary yang memiliki 2 key, yaitu "nama" yang memiliki value "Seski Ramadhan",
dan "pekerjaan" yang memiliki value "DevOps Engineer".

Mengetahui variable dan tipe data sangat penting. Kita akan berhadapan dengan banyak tipe kasus. Setiap kasus biasanya punya tipe data yang
memang cocok untuk kasus tersebut.

## **Condition**
Condition disebut juga *Flow Control*, dimana kita bisa melakukan sesuatu dikondisi tertentu.
```
a = 10
if a == 10:
  print("Nilai a adalah 10")
```
Pada contoh di atas kita melakukan kondisi, jika a == 10, yaitu jika nilai a adalah 10, maka program akan menuliskan "Nilai a adalah 10"

Kita juga bisa menambahkan opsi lain dengan "elif" dan "else"
```
a = 10
if a > 5:
  print("Nilai a lebih dari 5")
elif a < 5:
  print("Nilai a kurang dari 5")
else:
  print("Nilai a adalah yang lain")
```
