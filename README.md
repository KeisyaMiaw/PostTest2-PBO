# PostTest2-PBO

# Deskripsi
Program ini menerapkan CRUD guna mengelola data kos. Data yang disimpan pada program ini berisi nomor kamar, nama penyewa, status kamar (kosong/terisi), nomor telepon, dan lantai kamar. Prorgram ini menggunakan ArrayList untuk menampung data-data kos. User bisa menambahkan data, melihat data-data, update data, dan juga menghapus data. Dan juga disini say amenambahkan 1 menu baru yaitu menu search/cari yang guna untuk mencari data dari kos itu.

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
4. Update Kos
   - User akan diminta untuk memasukkan nomor kamar yang ingin diupdate
   - Jika ada maka data dapat diubah, jika tidak ada maka akan ada ouput "Data kamar tidak valid"
5. Hapus Kos
   - User diminta memasukkan nomor kamar yang ingin dihapus
   - Jika nomor ada data akan dihapus, jika tidak ada akan ada output "Data kamar tidak valid"
6. Cari Kos
   - User diminta untuk memasukkan nama penyewa dan keyword
   - Program akan mencari data yang diinput
6. Keluar
   - User dikeluarkan dari program dengan output "Anda telah keluar dari program"
7. Looping
   - Jika user tidak memilih menu 5,maka program akan terus kemali ke menu utama.



