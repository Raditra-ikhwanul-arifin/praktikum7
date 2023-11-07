# Praktikum 7

## Latihan 1

* Buat program sederhada dengan input 2 buah bilangan, kemudian
tentukan bilangan terbesar dari kedua bilangan tersebut
menggunakan statement if.

``````
bilangan1 = float(input("Masukan bilangan pertama : "))
bilangan2 = float(input("Masukan bilangan kedua : "))


bilangan1 = float(input("Masukan bilangan pertama : "))
bilangan2 = float(input("Masukan bilangan kedua : "))


if bilangan1 > bilangan2:
   bilangan_terbesar = bilangan1
else:
   bilangan_terbesar = bilangan2

   print("Bilangan terbesar adalah :", bilangan_terbesar )
``````

 ### Maka outputnya
 
![alt text](https://github.com/Raditraikh/praktikum7/blob/master/tugas7/p7lathn1.JPG?raw=true)

## Latihan 2

* Buat program untuk mengurutkan data berdasarkan input sejumlah
data (minimal 3 variable input atau lebih), kemudian tampilkan
hasilnya secara berurutan mulai dari data terkecil.

``````
# Masukan inputan
bil1 = int(input("Bilangan ke-1: "))
bil2 = int(input("Bilangan ke-2: "))
bil3 = int(input("Bilangan ke-3: "))

# Buat variable data
data = [bil1, bil2, bil3]

# Menampilkan data
print("Data sebelum di urutkan :", data)
list.sort(data)
print("Data setelah di urutkan :", data)
``````

### Maka outputnya
![alt text](https://github.com/Raditraikh/praktikum7/blob/master/tugas7/p7lthn2.JPG?raw=true)


## kode programnya
``````
baris = 10
kolom = baris

for bar in range(baris):
    for col in range(kolom):
        tab = bar+col
        print("{0:>5}".format(tab), end='')
    print()
``````

## maka outputnya

![alt text](https://github.com/Raditraikh/praktikum7/blob/master/tugas7/p7lthn1lop.JPG?raw=true)


## Latihan 2

* Tampilkan n bilangan acak yang lebih kecil dari 0.5.
* nilai n diisi pada saat runtime
* anda bisa menggunakan kombinasi while dan for untuk
menyelesaikannya

## kode programnya

``````
from random import random

n = int(input("Masukan jumlah perulangan: "))
while n == n:
    break
for i in range(n):
    num = random() % 0.5
    print(num)

``````

## maka outputnya
![alt text](https://github.com/Raditraikh/praktikum7/blob/master/tugas7/p7lthn2lop.JPG?raw=true)
