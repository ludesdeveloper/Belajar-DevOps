# GIT DASAR (GIT)
Git bisa kita katakan adalah mesin waktu yang kita dapat gunakan untuk bisa melakukan tracking terhadap perubahan, bahkan kembali ke masa
lampau bila terjadi kesalahan.
### **Inisialisasi (#)**
1. Mari kita buat sebuah folder dan sebuah file dulu ya.
```
mkdir belajar-git
cd belajar-git
touch belajar-git
```
2. Mari kita ketik sesuatu di dalam file tersebut
```
belajar git 1
```
3. Inisialisasi git di dalam folder
```
git init
```
4. Mari kita check dulu dengan menggunakan git status
```
git status
```
output
```
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	belajar-git

nothing added to commit but untracked files present (use "git add" to track)
```
Bisa kita lihat disini bahwa ada 1 file yang masih belum di-track oleh git.
5. Tambahkan untracked file ke staging area
```
git add belajar-git
```
