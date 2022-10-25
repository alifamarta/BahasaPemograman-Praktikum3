Nama: Alif Nur Fathlii Amarta

Kelas: TI 22 A3

NIM: 312210326

----
# Latihan Bahasa Pemograman menggunakan Python

## Latihan 1
Pada Latihan kita akan mempelajari Parameter ```end``` dan ```sep``` dan juga ```string formatting```

Pertama penggunaan ```end```

    print('A', end=' ')
    print('B', end=' ')
    print('C', end=' ')
    print('D', end=' ')

Parameter ```end``` berfungsi untuk mengganti karakter terakhir bawaan yang dicetak di layar. maka output nya menghasilkan

![image](https://user-images.githubusercontent.com/115516820/197835045-d1088b4f-024a-4146-b7e5-dae4dd9ae454.png)


lalu parameter ```sep``` 
```
w, x, y, z, = 10, 15, 20, 25
print(w, x, y, z,)
print(w, x, y, z, sep=',')
print(w, x, y, z, sep=':')
print(w, x, y, z, sep='-')
```

parameter ```end``` berfungsi untuk pemisah(separator) yang berfungsi sebagai tanda pemisah antar objek yang dicetak. Output nya akan menghasilkan

![image](https://user-images.githubusercontent.com/115516820/197836773-0873ddaa-f425-46c0-b232-4f8bed3d9c44.png)


Penggunaan ```String Formatting```

```
print('{0:>3} {1:>16}'.format(0, 10**0))
print('{0:>3} {1:>16}'.format(1, 10**1))
print('{0:>3} {1:>16}'.format(2, 10**2))
print('{0:>3} {1:>16}'.format(3, 10**3))
print('{0:>3} {1:>16}'.format(4, 10**4))
print('{0:>3} {1:>16}'.format(5, 10**5))
print('{0:>3} {1:>16}'.format(6, 10**6))
```

String Formatting atau Pemformatan string memungkinkan kita menyuntikkan item ke dalam string. Outputnya menghasilkan

![image](https://user-images.githubusercontent.com/115516820/197838846-e5a2389d-cbde-4b05-9cad-e0c13a78fedd.png)

---

## Latihan 2

penggunaan funngsi ```input``` pada Python

```
a=input("masukkan nilai a: ")
b=input("masukkan nilai b: ")
```

```print``` hasil kedua operasi dengan ```string formatting``` menggunakan ```%s``` (Menggunakan ```%s``` karena angka yang diinputkan terhitung variable)

```
print("hasil penggabungan {1}&{0}=%s".format(a,b) %(a+b))
```

Konversi kan menjadi angka integer 

```
a=int(a)
b=int(b)
```

lalu ```print``` hasil kedua operasi dengan menggunakan ```string formatting``` menggunakan ```%d``` (Setelah dikonversikan kita bisa memanggilnya dengan ```%d```)

```
print("hasil penjumlahanm {1}+{0}=%d".format(a,b) %(a+b))
print("hasil pembagian {1}/{0}=%d".format (a,b) %(a/b))
```
---

## Latihan 3

---

## Menghitung Luas dan Keliling Lingkaran

### Diagram Flowchart Menghitung Luas dan Keliling Lingkaran 

![Flowchart Luas dan Keliling Lingkaran](https://user-images.githubusercontent.com/115516820/197842648-adb119da-56c3-41ed-96c7-f4add1bc7c38.png)

### Kode Program Menghitung Luas dan Keliling Lingkaran

pertama masukkan phi nya dan jari jari nya 

```
pi = 3.14
jari = float(input("Masukkan Jari-Jari: "))
```

Lalu masukkan rumusnya untuk menghitung luas dan keliling lingkaran

```
luas = pi*(jari * jari)
keliling = 2 * pi * jari
```

Cetakkan hasil nya dengan ```string formatting``` 

```
print("Luas Lingkaran =","{:.1f}".format(luas))
print("Keliling Lingkaran =","{:.1f}".format(keliling))
```

Cetak memakai "{:.1f}".format(luas) karena penambahan "{:.1f}".format(), membatasi 1 karakter dibelakang koma.

maka outputnya

![image](https://user-images.githubusercontent.com/115516820/197843920-34a2ed2a-9704-40eb-8927-42c3b8584085.png)
