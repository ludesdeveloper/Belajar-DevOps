# GIT DASAR (GIT)
Git bisa kita katakan adalah mesin waktu yang kita dapat gunakan untuk bisa melakukan tracking terhadap perubahan, bahkan kembali ke masa
lampau bila terjadi kesalahan.
### **Inisialisasi**
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
### **Staging File**
1. Tambahkan untracked file ke staging area
```
git add belajar-git
```
Check kembali menggunakan git status
```
git status
```
output
```
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   belajar-git
```
### **Commit**
1. Melakukan commit atau save terhadap perubahan
```
git commit -m "menambahkan file belajar-git"
```
output
```
[master (root-commit) c370219] menambahkan file belajar-git
 1 file changed, 1 insertion(+)
 create mode 100644 belajar-git
```
lakukan pengecekan menggunakan git status
```
git status
```
output
```
On branch master
nothing to commit, working tree clean
```
Tutorial tambahan [link](https://ludesdeveloper.wordpress.com/2021/06/17/basic-penggunaan-git/)
### **LATIHAN**
> Buatlah sebuah repository di GitHub yang memiliki file di atas "belajar-git" 
