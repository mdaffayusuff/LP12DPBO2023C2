# **DPBO Latihan Praktikum 12**

##### **Nama : Muhammad Daffa Yusuf Fadhilah**

##### **NIM : 2100543**

### **Penjelasan**

Saya menggunakan struktur MVVM karena View dan Model tidak saling mengetahui, keduanya hanya dihubungkan oleh ViewModel.

View pada program ini adalah `Synchronization.java` yang memanggil `Game.java` yang merupakan ViewModel. View tidak mengakses model secara langsung.

ViewModel pada progam ini adalah `Game.java dan Controller.java` yang bertugas untuk mengolah data dari model yang nantinya akan ditampilkan melalui view.

Model pada program ini hanya berisi attribut yang mana nantinya akan diolah oleh para ViewModel

### **Perubahan pada TMD**
(*_Update 21 Juni 2023_*)
Untuk TMD masih menggunakan struktur MVVM dengan perubahan dimana View dan View Model lebih jelas terpisah. Sebelumnya, file `Game.java` mengurusi logika utama game serta menampilkannya dengan windows yang disediakan dari file yang sama. Pada TMD, `Game.java` hanya mengurusi logika dalam update berbagai komponen seperti player serta obstacle. Sedangakn Untuk menampilkan windows dalam game, dibuatkan file terpisah yang diletakan pada bagian View.

Perubahan lainnya tentu penambahan model untuk obstacle, database, dan tambilan tabel score. LAlu terdapat penambahan View Model yang mengurus player, input, obstacle dan point secara terpisah dan tidak disatukan dalam satu file
