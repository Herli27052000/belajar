# Tugas Ini Untuk Melengkapi Pertemuan 6 <br>
## Dan Menjelaskan Project <br>

**NAMA : Muhammad Rizky Abdillah** <br>
**NIM : 312010049** <br>
**KELAS : TI.20.A.2** <br>
**TUGAS : BAHASA PEMOGRAMAN** <br>

## DAFTAR ISI <br>

| NO | Description | Link |
| ----- | ----- | ---- |
| 1. | Pertemuan 5 | [click here](#pertemuan-5---latihan) |
| 1. | Pertemuan 6 lab 1 | [click here](#pertemuan-6---lab-1) |
### Pertemuan 5 - Latihan

Pada pertemuan 5 bahasa pemograman, saya diberi soal untuk latihan oleh Dosen untuk membuat Aplikasi Biodata dengan python (Seperti gambar di bawah ini:)
![latihan pertemuan 5]

![foto 1](https://user-images.githubusercontent.com/66506609/97837657-3d002000-1d11-11eb-80d0-7332a6b8a92c.png)


Saat ini saya akan menjelaskan hasil dari tugas tersebut. <br>
Berikut *source code* nya atau klik berikut ([latihan 5](tugas5.py)): <br>

``` python
print "  ====================================" 
print "          Latihan 1 Biodata             "
print "  ===================================="

#variabel

nama= raw_input ("Masukan Nama Lengkap Anda: ")
panggilan= raw_input ("Masukan Nama Panggilan: ")
nim= raw_input ("Masukan Nim Anda: ")
ttl= raw_input ("Masukan Tempat Lahir Anda`: ")
tl= input ("Masukan Tanggal lahir  Anda: ")
alamat= raw_input ("Masukan Alamat Anda: ")
telpone= raw_input ("Masukan No Telpon Anda: ")

#hasil inputan dari variable
print "Assalamu'alaikum Wr.Wb"
print "Let me introduce my self My name is",nama,"but you can call me",panggilan,"my NPM is",nim,"I was born in",ttl,"and I am",tl,"years old. I am very glad if you want to invite my house in",alamat,".So, don't forget to call me before with the number",telpone,
```
source code fiatas berfungsi untuk mencetak hasil / output berupa " **please enter your full name :** ". <br>
 Untuk menampilkan output string, saya menggunakan *tanda petik dua* didalam fungsi print(), sedangkan jika saya ingin menampilkan output / hasil berupa angka / interger saya tidak perlu menggunakan *tanda petik dua*. Contohnya:
 
 print("nama saya adalah ...")
print(1801)
```
<br>(Seperti gambar berikut ini <br>)
![Output fungsi print](praktikum/namaot.png) <br>
* Untuk source code berikutnya adalah inputan atau membuat variable. Seperti syntax dibawah ini:

``` python
fullname=input()
```
Keterangan : <br>
1. Variable adalah sebuah wadah penyimpanan data pada program yang akan digunakan selama program itu berjalan. Yang berfungsi sebagai variable dalam source code diatas adalah **fullname** . <br>

2. Fungsi **input()** adalah untuk memasukan nilai dar layar console di command prompt, lalu kemudian mengembalikan nilai saat kita menekan tombol enter *(newline)* <br>
![input](praktikum/hslnma.png) <br>
Pada gambar diatas, hasil dari inputan tersebut berwarna *putih* <br>
* Untuk memasukan printah lain seperti *Nickname, NPM, Place of bircth, Date of bircth, Year of bircth, Phone number, and address* mengikuti perintah yang sama seperti memasukan *fullname* <br>

* Untuk menghitung rumus umur saya menggunakan variable *DOB* yaitu 2020 (Tahun sekarang) dikurangi dengan Year of bircth, pada source code berikut : <br>
``` python
dob=2020-year
```
Pada syntax / source code diatas, saya menggunakan variable *dob* dimana untuk menghitung umur (variable **age** pada output), yaitu dengan rumus pada variable *dob=2020-year* <br>

* Langkah kali ini saya akan menampilkan output yang diminta oleh Dosen. <br>
Output pertama yang di minta Dosen adalah menampilkan salam, yaitu dengan mengetikkan syntax / source code berikut : 
``` python
print("\n Asalammualaikum.")
```
Keterangan :
1. Fungsi **\n** pada source code diatas adalah untuk memberi baris baru / enter / *newline*
2. Fungsi print() seperti dijelaskan pada point **Output** diatas
Hasil source code diatas adalah seperti gambar dibawah ini : <br>

![Output salam](praktikum/nma3.png)
* Langkah terakhir menampilkan semua hasil dari inputan diatas. Dengan mengetikan source code berikut : <br>
``` python
print(f"Let me introduce my self. My name is {fullname}, but you can call me {nickname}. My NPM {npm}. I was born in {pob} and Iam {dob} years old. I am very glad if you want to invite my house in {address}. So don't forget to call me before with the number {phone}. \n Thank You ")
```
Keterangan : <br>
* Fungsi huruf **f** pada perintah *print(f"....")* adalah fungsi print atau bisa memudahkan program dalam mencetak statement dalam suatu baris dibandingkan dengan metode yang lama yaitu memisahkan string dan variable dengan symbol koma ( , ) atau plus ( + ) <br>
* Sedangkan fungsi {} pada output tersebut menampilkan hasil variable <br>
Hasil dari output tersebut seperti berikut : <br>
![alloutput](praktikum/alloutput.png)
<br>
<br>
<br>

### Pertemuan 6 - lab 1

Pada halaman ini (Tugas pertemuan 6 - lab 1) Saya di berikan tugas oleh Dosen yaitu mempelajari Operator Aritmatika menggunakan bahasa pemograman python. Berikut source yang di berikan oleh Dosen [source lab 1](lab1.py)
![Pertemmuan 6 - lab 1](praktikum/lab1.png)
``` python
#Penggunaan End
print("A", end="")
print("B", end="")
print("C", end="")

print()
print("X")
print("Y")
print("Z")

#Penggunaan Separator
w,x,y,z=10,15,20,25
print(w,x,y,z)
print(w,x,y,z,sep=",")
print(w,x,y,z,sep="")
print(w,x,y,z,sep=":")
print(w,x,y,z,sep="-----")
```
Oke, kali ini saya menjelaskan materi yang dijelaskan oleh Dosen. <br><br>

* Penggunaan END
Penggunaan end digunakan untuk menambahkan kata yang dicetak di akhir baris

``` python
print("A", end="")
print("B", end="")
print("C", end="")
```

> Penggunaan print() digunakan untuk mencetak output, seperti syntax dibawah ini : <br>
``` python 
print()
```
> Syntax dibawah ini digunakan untuk menampilkan output berupa string
``` python
print("X")
print("Y")
print("Z")
```
Hasil dari source code terseut seperti gambar di bawah ini: 
![Output END](praktikum/abcd.png)

* Pengertian separaktor
Sepaktor adalah pemisah yang berfungsi sebagai tanda pemisah antar objek yang dicetak. Defaultnya adalah tanda sepasi <br><br>
