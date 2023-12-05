# Pertemuan 11

## Profil
| Variable | Isi |
| -------- | --- |
| **Nama** |Faiz Maulana |
| **NIM** | 312310469 |
| **Kelas** | TI.23.A.5 |
| **Mata Kuliah** | Bahasa Pemrograman |

### Latihan
## Ubah kode dibawah ini menjadi fungsi lambda
![Alt text](Gambar/image.png)

## setelah di ubah
![Alt text](Gambar/image-1.png)

## Outputnya
![Alt text](Gambar/image-2.png)

## Tugas Praktikum
_Buat program sederhana dengan mengaplikasikan penggunaan fungsi yang akan menampilkan daftar nilai mahasiswa, dengan ketentuan:_
- Fungsi tambah() untuk menambah data
- Fungsi tapilkan() untuk menampilkan data
- Fungsi hapus(nama) untuk menghapus data berdasarkan nama
- Fungsi ubah(nama) untuk mengubah data berdasarkan nama
- Buat flowchart dan penjelasan programnya pada README.md

# Input program 
![Alt text](Gambar/image-3.png)

### Penjelasan
- _Pada dasar nya program ini sama seperti di Pertemuan-10, bedanya di program ini di tambahkan `Function` / Sub rutin. 
Seperti program ada di atas `def` yg berati definision, & contoh `def garis()` Untuk membuat fungsi garis yg di panggil dari `print("~"*80)`._

- _Kalau `def tambah()`, `def ubah()`, `def hapus()`, `def cari()`, `def lihat()` di panggil dari program berikut :_

```python
while True: 
    print()
    menu = input("[(T)ambah, (U)bah, (H)apus, (C)ari, (L)ihat, (K)eluar] : ")
    garis("~"*80)
    print()

    if menu.lower() == 't':
        tambah()

    elif menu.lower() == 'u':
        ubah()       

    elif menu.lower() == "h":
        hapus() 

    elif menu.lower() == "c":
        cari()

    elif menu.lower() == "l":
        lihat() 

    elif menu.lower() == "k":
        print("Program telah selesai, Terima Kasih :) ")
        break

    else:
        print("\n INPUT {} Tidak valid ! , Silakan pilih [T/U/H/C/L] untuk menjalankan program!".format(menu))
```

## Outputnya 

### Tambah data
![Alt text](Gambar/image-4.png)

### Ubah data 
![Alt text](Gambar/image-5.png)

### Cari data
![Alt text](Gambar/image-6.png)

### Lihat data
![Alt text](Gambar/image-7.png)

### Hapus data
![Alt text](Gambar/image-8.png)

### Keluar
![Alt text](Gambar/image-9.png)

### Flowchart
![Alt text](Gambar/image-10.png)

# Terima Kasih
