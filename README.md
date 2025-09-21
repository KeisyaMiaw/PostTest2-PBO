# PostTest2-PBO

# Deskripsi
Program ini menerapkan CRUD guna mengelola data kos. Data yang disimpan pada program ini berisi nomor kamar, nama penyewa, status kamar (kosong/terisi), nomor telepon, dan lantai kamar. Prorgram ini menggunakan ArrayList untuk menampung data-data kos. User bisa menambahkan data, melihat data-data, update data, dan juga menghapus data. Dan juga disini saya amenambahkan 1 menu baru yaitu menu search/cari yang guna untuk mencari data dari kos itu.

# Alur Program
1. Menu utama ditampilkan
   - user memilih salah satu menu dari 6 menu
2. Tambah kos
   - User dapat menginput nomor kamar, nama penyewa, status, no telp, dan lantai
   - data disimpan ke ArrayList

<img width="329" height="251" alt="1 tambah" src="https://github.com/user-attachments/assets/2209d649-3c8a-4d47-9999-47fe584fc803" />

3. Tampil Kos
   - JProgram akan mengecek apakah daftar kamar itu kosong
   - Jika ada data, maka program akan menampilkan semua kos dengan toString()

<img width="784" height="176" alt="2 tampilkan" src="https://github.com/user-attachments/assets/557b0f91-e2a5-45e5-913c-51e7bae69e65" />

4. Update Kos
   - User akan diminta untuk memasukkan nomor kamar yang ingin diupdate
   - Jika ada maka data dapat diubah, jika tidak ada maka akan ada ouput "Data kamar tidak valid"
  
<img width="446" height="252" alt="3 update" src="https://github.com/user-attachments/assets/95d09b8d-daed-462b-a8dc-f62dc0f488ba" />

5. Hapus Kos
   - User diminta memasukkan nomor kamar yang ingin dihapus
   - Jika nomor ada data akan dihapus, jika tidak ada akan ada output "Data kamar tidak valid"

<img width="337" height="184" alt="4 hapus" src="https://github.com/user-attachments/assets/22049046-ebcb-44f9-9237-4f5ef0b1afc6" />

6. Cari Kos
   - User diminta untuk memasukkan nama penyewa dan keyword
   - Program akan mencari data yang diinput

<img width="340" height="188" alt="5 cari" src="https://github.com/user-attachments/assets/883f29e2-5c77-443a-bfc9-b6a43180ee89" />

6. Keluar
   - User dikeluarkan dari program dengan output "Anda telah keluar dari program"

<img width="381" height="164" alt="0 keluar" src="https://github.com/user-attachments/assets/fd0a2f9b-44ba-416d-ba8d-a818aa907da4" />

# Package
1. Package model berisi class Kos guna sebagai tempat atribut & struktur dari data kos itu
2. Package KosService berisi class Service sebagai tempat logika CRUD pada data kos
3. Package Main berisi Main, ini merupakan titik awal pada program data kos ini, menampilkan menu& memanggil class Service

<img width="329" height="155" alt="image" src="https://github.com/user-attachments/assets/d2f5093b-d481-40aa-b15a-d0b13fdcb747" />




