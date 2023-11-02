#PERTEMUAN 7

##PROFIL
| Variable | Isi |
| -------- | --- |
| *Nama* | HABIB SUPRAYOGA |
| *NIM* |  312310608 |
| *Kelas* | TI.23.A.6 |
| *Mata Kuliah* | Bahasa Pemrograman |



## Tugas modul praktikum 2 
### Latihan 

*Buat program sederhana dengan input tiga buah bilangan, dari ketiga bilangan
 tersebut tampilkan bilangan terbesarnya. Gunakan statement if.*

```Python
#Masukan inputan
A = int(input("masukan bilangan A"))
B = int(input("masukan bilangan B"))
C = int(input("masukan bilangan C"))

if  A > B:
    maks = A

else:
    maks = B


if C > maks:
    maks = C

print("bilangan terbesar adalah", maks)
```

![Gambar](4.png)



## Tugas struktur kondisi 
### Latihan 1

*Buat program sederhada dengan input 2 buah bilangan, kemudian
 tentukan bilangan terbesar dari kedua bilangan tersebut
 menggunakan statement if.*

 ```Python
#Masukan inputan

# Menginput 2 buah bilangan
bil1 = int(input("masukan bilangan A: "))
bil2 = int(input("masukan bilangan B: "))

# Menggunakan statement if untuk menentukan bilangan terbesar
if bil1 > bil2:
    maks = bil1
elif bil2 > bil1:
    maks = bil2
else:
    maks = "Bilangan tersebut sama."

# Menampilkan bilangan terbesar
print("bilangan terbesar adalah", maks)
```
![gambar](5.png)
