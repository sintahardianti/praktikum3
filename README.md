### Nama : Sinta Hardianti Wijaya

### NIM : 312210342

### Kelas : TI.22.A3

## Praktikum 3

# Latihan 1

### - Penggunaan End

Fungsi cetak secara default diakhiri dengan garis baru atau enter.

```
print('A', end='')
print('B', end='')
print('C', end='')
print()
print('X')
print('Y')
print('Z')
```

![Screenshot (214)](https://user-images.githubusercontent.com/115516473/198214941-183b5170-6d00-494d-9478-bf0c3cf17f82.png)

Hasilnya :

![Screenshot (216)](https://user-images.githubusercontent.com/115516473/198222716-372034cb-883f-42b6-a58f-a0ee5067051d.png)

### - Penggunaan Seperator

Bisa untuk memberikan perintah koma, spasi, non spasi, titik dua, dan strip.

```
w, x, y, z = 10, 15, 20, 25
print(w, x, y, z)
print(w, x, y, z, sep=',')
print(w, x, y, z, sep='')
print(w, x, y, z, sep=':')
print(w, x, y, z, sep='-----')
```

![Screenshot (217)](https://user-images.githubusercontent.com/115516473/198223076-b3d47355-e61f-44a6-afe8-f7793b98a240.png)

Hasilnya sebagai berikut :

![Screenshot (218)](https://user-images.githubusercontent.com/115516473/198223760-2ee849f8-9297-4c2d-a02c-8db2bda426f3.png)

### - String Format

Format pertama:

```
print(0, 10**0)
print(1, 10**1)
print(2, 10**2)
print(3, 10**3)
print(4, 10**4)
print(5, 10**5)
print(6, 10**6)
print(7, 10**7)
print(8, 10**8)
print(9, 10**9)
print(10, 10**10)
```

![Screenshot (220)](https://user-images.githubusercontent.com/115516473/198226246-5173e6cb-f642-4187-b34b-99c43918b6aa.png)

Hasilnya:

![Screenshot (221)](https://user-images.githubusercontent.com/115516473/198227847-2c13c334-3a10-4ff0-956f-16becf08d23f.png)

Format kedua:

```
print('{0:>3} {1:>16}'. format(0, 10**0))
print('{0:>3} {1:>16}'. format(1, 10**1))
print('{0:>3} {1:>16}'. format(2, 10**2))
print('{0:>3} {1:>16}'. format(3, 10**3))
print('{0:>3} {1:>16}'. format(4, 10**4))
print('{0:>3} {1:>16}'. format(5, 10**5))
print('{0:>3} {1:>16}'. format(6, 10**6))
print('{0:>3} {1:>16}'. format(7, 10**7))
print('{0:>3} {1:>16}'. format(8, 10**8))
print('{0:>3} {1:>16}'. format(9, 10**9))
print('{0:>3} {1:>16}'. format(10, 10**10))
```

![Screenshot (223)](https://user-images.githubusercontent.com/115516473/198230010-b2968b08-a9c5-45e1-9a18-ece850a246fd.png)

Hasilnya sebagai berikut:

![Screenshot (224)](https://user-images.githubusercontent.com/115516473/198230810-b37f70e1-a767-4975-b73b-ae4d20a75989.png)

# Latihan 2

Perintah untuk menginput variabel:

```
a=input("masukkan nilai a:")
b=input("masukkan nilai b:")
```

Perintah untuk mencetak variabel:

```
print("variable a=", a)
print("variable b=", b)
```

Menggabungkan variabel:

```
print("hasil penggabungan {1}&{0}=%s".format(a,b) %(a+b))
```

![Screenshot (226)](https://user-images.githubusercontent.com/115516473/198233753-7293303d-7f1d-4f1f-80b6-660e01ae3235.png)

Konversi nilai variabel:

```
a=int(a)
b=int(b)
print("hasil penjumlahan {1}&{0}=%d".format(a,b) %(a+b))
print("hasil pembagian {1}+{0}=%d".format(a,b) %(a/b))
```

Hasilnya:

![Screenshot (228)](https://user-images.githubusercontent.com/115516473/198234838-6e719c53-ce0f-445f-a6d9-1495daf40c7d.png)

# Latihan 3

## String format membuat belah ketupat





