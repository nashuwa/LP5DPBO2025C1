# TP4DPBO2025C1

## Janji
Saya Nashwa Nadria Futi dengan NIM 2306026 mengerjakan soal Tes Praktikum 5 dalam mata kuliah Desain Pemrograman Berbasis Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

## Desain
1. Class Mahasiswa
   Class mahasiswa memiliki 4 atribut yaitu NIM, Nama, Jenis Kelamin, dan Status. Atribut baru yang ditambahkan adalah atribut Status yang menyatakan status kemahasiswaan suatu mahasiswa, seperti aktif, cuti, atau dropout. Class ini berisi inisialisasi atribut, constructor Mahasiswa dengan parameter, dan getter setter seluruh atribut.
   
2. Menu form
   ![Screenshot 2025-03-16 202550](https://github.com/user-attachments/assets/8dc12585-e8dd-47f6-bd98-38d77088552b)
   Menambahkan statusLabel, jRadioButton aktifRadio, jRadioButton cutiRadio, dan jRadioButton dropOutRadio.

## Alur Program Main.java

1. Menambahkan string getSelectedStatus(). Akan digunakan untuk mendapatkan (get) nilai status mahasiswa dari pilihan radio button yang dipilih oleh pengguna. Fungsi ini memeriksa radio button mana yang sedang dipilih (isSelected()) antara aktifRadio, cutiRadio, atau dropOutRadio. Jika aktifRadio dipilih, fungsi akan mengembalikan string "Aktif". Jika cutiRadio dipilih, fungsi akan mengembalikan string "Cuti". Jika dropOutRadio dipilih, fungsi akan mengembalikan string "Dropout". Jika tidak ada radio button yang dipilih (meskipun seharusnya selalu ada satu yang dipilih dalam radio button group), fungsi ini mengembalikan "Aktif" sebagai nilai default.
   
2. Menambahkan string setSelectedStatus(). Fungsi ini digunakan untuk mengatur (set) radio button yang sesuai berdasarkan nilai status mahasiswa yang diberikan. Fungsi ini menerima parameter status berupa string.
Menggunakan struktur switch, fungsi ini memeriksa nilai string status yang diberikan: Jika "Aktif", maka radio button aktifRadio akan dipilih. Jika "Cuti", maka radio button cutiRadio akan dipilih. Jika "Dropout", maka radio button dropOutRadio akan dipilih. Jika nilai status tidak cocok dengan semua kasus di atas (default), maka aktifRadio akan dipilih.

3. Set default selection ke aktifRadio
   
4. Menambahkan tiap-tiap radio ke dalam ButtonGroup statusButtonGroup
   ![Screenshot 2025-03-16 203606](https://github.com/user-attachments/assets/a144657d-7b84-4c13-ac65-9e8b4e362f16)

5. Inisialisasi komponen Aktif, Cuti, Dropout di dalam fungsi initializeComponents()
   ![Screenshot 2025-03-16 203504](https://github.com/user-attachments/assets/544a303d-945c-4db2-b44a-a291e25d45d5)
 
6. Menambahkan row untuk status di fungsi DefaultTableModel
   ![Screenshot 2025-03-16 203725](https://github.com/user-attachments/assets/a53cebfe-550f-4de1-94cf-8dedf84b6f4d)

7. Menggunakan getSelectedStatus untuk insert dan update data.
8. Membuat pesan konfirmasi sebelum menghapus data.
   ![Screenshot 2025-03-16 203925](https://github.com/user-attachments/assets/49c71986-a037-4cb4-9348-83d28abb8f47)

9. Jika clear form, maka default dari atribut status yang akan ditampilkan adalah aktif.

## Screenshot Program Berjalan
![Screenshot 2025-03-16 201449](https://github.com/user-attachments/assets/3e21af56-0c13-4bb5-a439-1c1c653dabe6)
![Screenshot 2025-03-16 201502](https://github.com/user-attachments/assets/51f54b34-9606-4c0f-a04c-76c3de59d5d3)

