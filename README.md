Nama: Rahmat Ibnu Zidane

NIM: 312210471

Kelas: TI.22.B2

##Praktikum 10 : String Phyton


##Apa itu string Phyton?

String adalah jenis yang paling populer di Python.


Untuk membuatnya hanya dengan kekerasan karakter dalam tanda kutip.


Python memperlakukan tanda kutip tunggal sama dengan tanda kutip ganda.


Membuat string yang rusak memberi nilai pada sebuah variabel.

##Latihan 1

![image](https://user-images.githubusercontent.com/115911489/212913349-28364a52-ec32-4832-9f54-aab22a9a87cd.png)


##Latihan 2

![image](https://user-images.githubusercontent.com/115911489/212913507-23131fb3-f76b-4939-b3ae-18ff77efd0b5.png)

Kode sumber

![image](https://user-images.githubusercontent.com/115911489/212920428-7e37ed28-0371-4ef4-9e50-387c11fb285e.png)


![ss63](https://user-images.githubusercontent.com/115911489/212924571-6eefb982-e8c5-4bd4-9769-4705577d356e.JPG)



##Penjelasan latihan 1

Untuk menghitung karakter pada string yaitu menggunakan Fungsi len().

Contoh:

print(len(txt))

Fungsi len() pada python di gunakan untuk menghitung karakter pada string.

Jika ingin mengambil karakter terakhir, gunakan index [-1].

Contoh

print(txt[-1])

Lanjut. Jika ingin mengambil karakter 2 s/d 4 menggunakan kurung siku yang di deklarasi nomor ARRAY.

Contoh:

print(txt[2:5])

Bila ingin menghilangkan spasi pada string yaitu menggunakan fungsi replace().

Contoh:

print(txt.replace(" ", ""))

Untuk mengubah huruf menjadi besar, gunakan fungsi upper().

Contoh:

print(txt.upper())

Sedangkan jika ingin mengubah huruf menjadi kecil, gunakan fungsi lower().

Contoh:

print(txt.lower())

Untuk mengganti karakter 'H' dengan karakter 'J', gunakan fungsi replace().

Contoh:

print(txt.replace("H", "J"))

##Penjalasan latihan 2

Untuk memasukkan variabel ke dalam string, tambahkan kurung kurung awal dan kurung akhir {}untuk menempatkan variabel sebelumnya.

Contoh:

    umur = 24
    
    txt = "Hello, nama saya jack, dan umur saya adalah {0} tahun"
    
    print(txt.format(umur))
    
##Keluaran
 
 Latihan 1
 
![ss61](https://user-images.githubusercontent.com/115911489/212922948-7a2c850c-4ea2-400b-9cdd-58f107dbc0e4.JPG)
    

Latihan 2

![ss62](https://user-images.githubusercontent.com/115911489/212922625-2a6f2a69-9e1b-430a-8058-1d571f2a6531.JPG)

