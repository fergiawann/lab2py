# lab2py
# Praktikum2 
# Fergiawan Satrio Bagaskoro
## Penjelasan Proses Praktikum
### 1. Cara Mendownload Python
Agar kode program yang ditulis dalam bahasa Python bisa diproses menjadi aplikasi komputer, kita butuh sebuah Python Interpreter. Python interpreter inilah yang akan membaca satu persatu perintah dalam bahasa Python dan memprosesnya menjadi kode-kode yang bisa dipahami komputer.
File Python interpreter bisa di download dari web resmi Python di www.python.org. Silahkan buka alamat tersebut lalu klik menu “Download” (1).

![ss1](https://user-images.githubusercontent.com/115530180/196879850-dee1647e-1783-46ff-9e82-70fa5c9542e9.png)

### 2. Instalasi Python
* Setelah berhasil di download, selanjutnya adalah proses installasi.
* Double klik pada file installer python yang sudah di download, atau klik kanan lalu pilih Run as Administrator . Jika muncul warning Run as Administrator, silahkan pilih Yes.
* Centang Install launcher for all users dan Add python to PATH.
* Kemudian klik Install Now.

![ss2](https://user-images.githubusercontent.com/115530180/196880168-9b5728a1-8735-481c-89b7-81f1eb070853.png)

Installasi selesai jika sudah muncul “Setup was succesful”.

![ss4](https://user-images.githubusercontent.com/115530180/196880295-d4a61402-f019-4294-a608-95d6c26787a3.png)

### Contoh Perintah Dasar Python
**# Mengambil input**

**nama = input ("fergiawan")**

**umur = input ("999")**

**# Menampilkan Output**

**print("Hello",nama,"umur kamu adalah",umur,"tahun")**

## Latihan 1
**Menjalankan Python Console**
* Menampilkan Tulisan "Hello" dilayar
* Menampilkan tulisan "Saya sedang belajar python" dilayar

![ss5](https://user-images.githubusercontent.com/115530180/196890797-74089ad1-9f5b-42c3-892a-a34b7f32f5e7.png)
## Latihan 2
**Menjumlahkan dua buah bilangan menggunakan variabel a dan b**
* Mendefinisikan variabel a dengan nilai 10
* Mendefinisikan variabel b dengan nilai 14
* Mencetak nilai variabel a dan b
* Mencetak hasil penjumlahan a+b
Maka Output nya akan seperti ini

![ss6](https://user-images.githubusercontent.com/115530180/196893759-738c3a9e-2665-4fff-80c1-288cf5fe955a.png)

## Latihan 3
### Menginput nilai Variable dengan IDLE Python
Penggunaan IDLE python untuk menginput nilai variabel dengan cara
```
# input nilai variable
a=input("masukkan nilai a:")
b=input("masukkan nilai b:")
# cetak nilai variable
print("Variable a:10",a)
print("Variable b:12",b)
```
Maka Outputnya akan seperti ini

![ss7](https://user-images.githubusercontent.com/115530180/197197528-c5e3f381-c2c2-4990-9b63-9f33fd730085.png)

### Lalu Menjumlahkan Kedua Variable
untuk penggabungan nilai kedua variabel dengan cara String Format dengan cara
```
print("Hasil penggabungan {1}+{0}=%s".format(a,b) %(a+b))
```
Maka Outputnya akan seperti ini

![ss8](https://user-images.githubusercontent.com/115530180/197197400-17aac896-dd40-4051-801b-794b00c39886.png)
# Konversi Kedua Nilai Variabel
Penggunaan python untuk mengkonversi nilai kedua variabel dengan
```
a=int(a)
b=int(b)
print("Hasil Penjumlahan {1}+{0}=%d").format(a,b) %(a+b))
print("Hasil Pembagian {1}+{0}=%d").format(a,b) %(a/b))
```
Maka Outputnya akan seperti ini

![ss9](https://user-images.githubusercontent.com/115530180/197197333-44fdcfc0-3877-4229-b918-abb995d8d5e3.png)
