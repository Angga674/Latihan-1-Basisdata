
# Praktikum 1



## Profil

|  Variabel |   isi    |
| :-------- | :------- | 
|   `Nama`  | `Dafa Alfiana E`|
|   `NIM`   | `312210446`    |
|   `Kelas` | `TI.22.A4`     |
|   `Matkul`| `Basisdata`    |





## Latihan membuat database, MySQL menggunakan cli

### Tugas Praktikum 1

#### 1. Buat sebuah database dengan nama Tugas_Praktikum1


## Screenshots

![App Screenshot](https://github.com/Angga674/Latihan-1-Basisdata/blob/master/Foto%20praktikum%201/Gambar%201.png?raw=true)


#### Penjelasan:

Gunakan perintah `CREATE DATABASE nama_database;` untuk membuat database baru.

Dan gunakan `SHOW DATABASE;` untuk melihat database yang dibuat.


#### 2. Buat sebuah tabel dengan nama biodata(Nama, Alamat) didalam database Tugas_Praktikum1.
#### 3. Tambahkan sebuah kolom keterangan (varchar 15), sebagai kolom terakhir!
## Screenshots

![App Screenshot](https://github.com/Angga674/Latihan-1-Basisdata/blob/master/Foto%20praktikum%201/Gambar%202.png?raw=true)

#### Penjelasan:

- `USE Tugas_Praktikum1;` , untuk menggunakan database.  
- `CREATE TABLE;` , untuk membuat sebuah tabel.
- `SHOW TABLE;` , melihat sebuah tabel.
- `DESC Biodata;` untuk melihat sebuah tabel

Catatan: Untuk VARCHAR(50), berfungsi seperti string untuk memberikan 50 kata dalam tabel.

#### 4. Menambahkan kolom untuk id(Int 11) di bagian kolom pertama.

![App Screenshot](https://github.com/Angga674/Latihan-1-Basisdata/blob/master/Foto%20praktikum%201/Gambar%203.png?raw=true)

#### Penjelasan:
- `ALTER TABLE biodata ADD COLUMN id INT(11)FIRST;` Add field id dengan interger maks 11 angka, di atas Kolom Nama.

 #### 5. Buatlah kolom dengan nama Phone (VARCHAR(50)), dan sisipkan diatas kolom Alamat!

![App Screenshot](https://github.com/Angga674/Latihan-1-Basisdata/blob/master/Foto%20praktikum%201/Gambar%204.png?raw=true)

#### Penjelasan:
- `ALTER TABLE biodata ADD COLUMN Phone Varchar(50) AFTER Alamat;` Add field Phone dengan VARCHAR maks 50 angka, di atas Kolom Alamat.

#### 6. Mengubah Tipe Data id yang sebelumnya int(11) menjadi CHAR(11)

![App Screenshot](https://github.com/Angga674/Latihan-1-Basisdata/blob/master/Foto%20praktikum%201/Gambar%205.png?raw=true)

#### Penjelasan: 
- `ALTER TABLE biodata MODIFY id CHAR(11);` Mengubah tipe data id int menjadi char. 

#### 7.  Ubah nama field Phone Menjadi Hp dengan VARCHAR(20)

#### 8. Menambahkan kolom Email 

#### 9. Menghapus field keterangan dari kolom 

#### 10. Ganti nama tabel biodata menjadi data_mahasiswa

#### 11. Ganti field id menjadi NIM

![App Screenshot](https://github.com/Angga674/Latihan-1-Basisdata/blob/master/Foto%20praktikum%201/Gambar%206.png?raw=true)

![App Screenshot](https://github.com/Angga674/Latihan-1-Basisdata/blob/master/Foto%20praktikum%201/Gambar%207.png?raw=true)


#### Penjelasan: 
- `ALTER TABLE biodata CHANGE Phone Hp VARCHAR(20);` Mengubah field phone VARCHAR(50) menjadi hp VARCHAR(20).
- `ALTER TABLE biodata ADD COLUMN Email VARCHAR(50);` Menambahkan kolom email
- `ALTER TABLE biodata DROP Keterangan;` Menghapus field keterangan pada kolom 
- `ALTER TABLE biodata RENAME data_mahasiswa;` Mengubah nama tabel biodata menjadi data_mahasiswa 
- `ALTER TABLE data_mahasiswa CHANGE id NIM char(11);` Mengubah field id menjadi NIM

#### 12. Jadikan NIM menjadi PRIMARY KEY

#### 13. Jadikan Email menjadi UNIQUE KEY

![App Screenshot](https://github.com/Angga674/Latihan-1-Basisdata/blob/master/Foto%20praktikum%201/Gambar%208.png?raw=true)

#### Penjelasan:
- `ALTER TABLE data_mahasiswa ADD PRIMARY KEY (NIM);` Menjadikan NIM sebagai PRIMARY KEY
- `ALTER TABLE data_mahasiswa ADD UNIQUE KEY (Email);` Menjadikan Email sebagai UNIQUE KEY








## Screenshots

![App Screenshot](https://github.com/Angga674/Latihan-1-Basisdata/blob/master/Foto%20praktikum%201/Gambar%202.png?raw=true)
