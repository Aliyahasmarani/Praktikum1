## Latihan1 

## TUGAS BAHASA PEMROGRAMAN

## INSTALASI GIT
Membuka website resmi GIT yaitu (git-scm.com), lalu mendownload sesuai OS 
![Gambar1](gambar/git.png)

## MEMBUKA GIT BASH
Setelah mendownload lalu membuka GIT BASH
![Gambar2](gambar/git1.png)

## MENAMBAHKAN GLOBAL CONFIG
Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi user.name dan user.email
Konfigurasi ini bisa dilakukan untuk globab repositiry atau indovidual repository.
Apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi kegagalan saat menjalankan perintah git commit
Config Global Repository
![Gambar3](gambar/git2.png)

## MEMBUAT REPOSITORY LOCAL
Buka direktory aktif, misal: /d/praktikum1
```
mkdir praktikum1
cd praktikum1
```
![Gambar4](gambar/git3.png)

## MENJALANKAN GIT INIT
Dengan perintah
```
git init
```
![Gambar5](gambar/git4.png)

## MENAMBAHKAN FILE BARU PADA REPOSITORY
Untuk membuat file dapat menggunakan text editor, lalu menyimpan filenya pada direktori aktif (repository)
```
echo "#Latihan1" >> README.md
```
![Gambar6](gambar/git5.png)

Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add.
```
git add README.md
```
![Gambar7](gambar/git6.png)

## MENYIMPAN PERUBAHAN KE DATABASE (COMMIT)
Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah
```
git commit -m "simpan1"
```
![Gambar8](gambar/git7.png)

## MEMBUAT REPOSITORY SERVER
Server repository yang akan digunakan adalah
```
https://github.com
```
Kalian harus membuat akun terlebih dahulu.
Pada laman github, klik tombol start a project, atau dari menu (icon +) klik New Repository
![Gambar9](gambar/git8.png)

## MEMBUAT REPOSITORY SERVER
Isi nama repositorynya, misal:Rani1.
Lalu klik tombol Create repository
![Gambar10](gambar/git9.png)

## MENAMBAHKAN REMOTE REPOSITORY
Remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository, sehingga dapat diakses oleh banyak user.
untuk menambahkan remote repository server, gunakan perintah
```
git remote add origin [url]
git remote add origin https://github.com/Aliyahasmarani/Praktikum1.git
```
![Gambar11](gambar/git10.png)

## MENGIRIM PERUBAHAN KE SERVER (PUSH)
Untuk mengirim perubahan pada local repository ke server gunakan perintah git push.
```
git push -u origin master
```
![Gambar12](gambar/git11.png)
perintah ini akan meminta memasukkan username dan password pada akun github.com

