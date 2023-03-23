# [ LATIHAN 5 PRAKTIKUM DPBO ]

## Identitas:
- NIM   : 2102313
- Nama  : Muhammad Kamal Robbani
- Kelas : C1'21

## Janji:
Saya [Muhammad Kamal Robbani] dengan nim 2102313 mengerjakan Latihan 5 DPBO dalam mata kuliah 
[Desain Pemrograman Berorientasi Objek] untuk keberkahan-Nya maka saya tidak melakukan 
kecurangan seperti yang telah dispesifikasikan. Aamiin.

## Requirements Soal:
- Add more property (component type: any, except text field)
- Add method to reset form
- Refresh table after update and delete
- Add confirmation prompt before delete
- Build project (generate .jar file)

## Desain Program:
![image](https://user-images.githubusercontent.com/101335350/227204258-82dbd615-4414-4a78-9840-3daa0ba3016e.png)

## Alur Program:
- Insert Data:
  - Isi data pada field dan pilih salah satu radio button, lalu klik button 'Add'.
  - Memasukkan value dari field dan radio button yang diisi dan dipilih user.
  - Buat objek Mahasiswa menggunakan konstruktor kelas Mahasiswa.
  - Masukkan objek Mahasiswa ke dalam list of object 'listMhs'.
  - Reset form.
  - Update isi tabel.
  - Mengeluarkan output yang memberikan informasi bahwa insert data berhasil di console.
  - Mengeluarkan dialog box yang memberikan informasi bahwa insert data berhasil dilakukan.
  - END.
- Update Data:
  - Pilih row yang datanya ingin di-update.
  - Mencari index dari data pada row yang dipilih user.
  - Mengisi field dan radio button sesuai dengan data dari row yang dipilih oleh user.
  - Ubah data pada field atau radio button, lalu klik button 'Update'.
  - Memasukkan value dari form ke dalam variable.
  - Ubah value attribute pada list of object sesuai dengan index yang didapat sebelumnya dengan menggunakan setter.
  - Reset form.
  - Update tabel.
  - Mengeluarkan output yang memberikan informasi bahwa update data berhasil di console.
  - Mengeluarkan dialog box yang memberikan informasi bahwa update data berhasil dilakukan.
  - END.
- Delete Data:
  - Pilih row yang datanya ingin di-update.
  - Mencari index dari data pada row yang dipilih user.
  - Mengisi field dan radio button sesuai dengan data dari row yang dipilih oleh user.
  - Klik button 'Delete'.
  - Menampilkan dialog validation.
  - Klik option 'Yes'.
  - Remove objek dengan index yang didapatkan sebelumnya dari list of object.
  - Update tabel.
  - Mengeluarkan output yang memberikan informasi bahwa delete data berhasil di console.
  - Mengeluarkan dialog box yang memberikan informasi bahwa delete data berhasil dilakukan.
  - Reset form.
  - END.
  
## Dokumentasi:
- Add Data:<br>
![image](https://user-images.githubusercontent.com/101335350/227212999-635b4be1-52f0-4589-9450-b7a7087fba01.png)
- Update Data:<br>
![image](https://user-images.githubusercontent.com/101335350/227213152-22a3195c-fd89-47f1-83b9-089d7206927e.png)
- Delete Data:<br>
![image](https://user-images.githubusercontent.com/101335350/227213264-cdf88869-cafe-4f31-a74b-18571bdb9822.png)
![image](https://user-images.githubusercontent.com/101335350/227213366-8294408e-c1af-4994-b99e-2e5642a5b58c.png)
