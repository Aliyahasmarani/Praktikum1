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



