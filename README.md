# labspy03

## Latihan 1
- Program Menampilkan n Bilangan acak yang lebih kecil dari 0.5

#### Program
![Gambar1](Screenshot/Sslat1(1).png)

#### Output
![Gambar2](Screenshot/Sslat1(2).png)

#### Penjelasan
- Import module random untuk membuat bilangan acak
```bash 
from random import random
```
- Untuk menginput nilai yang ingin dikonversikan kedalam bilangan bulat (Integer) yang akan di masukan kedalam variabel n
```bash
n=int(input("Masukan Nilai N : "))
```
- Untuk pengulangan range yang diinputkan oleh variable n
```bash
for i in range(n):
    while 1:
        n=random()
        if n < 0.5:
```
- Menampilkan hasil dari nMenampilkan hasil dari n
```bash
print("data ke: ",i,"=>",n)
```

## Latihan 2
- Program Menampilkan Bilangan terbesar dari n buah data yang diinputkan

#### Program
![Gambar3](Screenshot/Sslat2(1).png)

#### Output
![Gambar4](Screenshot/Sslat2(2).png)

#### Penjelasan
- Deklarasikan Variabel
```bash
max=0
```
- Untuk perulangan sampai waktu yang tidak terhitung (While Loop)
```bash
while True:
```
- Untuk menginput bilangan yang akan dimasukan kedalam variabel a
```bash
a=int(input("Masukan bilangan = "))
```
- Apabila max kurang dari a, maka variabel max = a (angka yang diinputkan)
```bash
if max < a:
        max = a
```
- Jika a = 0, maka perulangan (loop) akan dihentikan dengan fungsi break
```bash
if a==0:
        break
```
- Menampilkan hasil bilangan terbesar dari variabel max
```bash
print("Bilangan Terbesar Adalah", max)
```

## Program 1
- Program Menghitung Total Keuntungan

#### Program
![Gambar5](Screenshot/Ssprogram1(1).png)

#### Output
![Gambar6](Screenshot/Ssprogram1(2).png)

#### Penjelasan 
- Dari variabel Laba terdapat list modal dari bulan kesatu sampai terakhir
```bash
modal=100000000
laba=[modal*0, modal*0, modal*1/100, modal*1/100, modal*5/100, modal*5/100, modal*5/100, modal*3/100]
bulan=0
sum=0
```
Menampilkan modal pertama yang diambil dari variabel modal
```bash
print("Modal awal pengusaha : ",modal)
```
Untuk melakukan perulangan variabel i kedalam variabel laba. agar variabel i mendapat akses list yang ada didalam variabel laba
```bash
for i in laba:
```
Variabel sum ditambahkan dengan variabel i yang akan diulang hingga program selesai
```bash
sum = sum + i
```
 Variabel bulan, untuk menentukan bulan yang akan ditambahkan dengan nilai 1 terus menerus hingga program berakhir
```bash
bulan+=1
```
Menampilkan laba dari bulan pertama hingga bulan terakhir
```bash
print("Laba pada bulan ke-",bulan,"mendapat laba: ",i)
```
Menampilkan total laba/keuntungan yang di dapat selama 8 bulan
```bash
print("Total laba adalah: ", sum)
```


#### Selesai

## Terima kasih