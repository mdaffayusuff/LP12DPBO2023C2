# **DPBO Latihan Praktikum 12**

##### **Nama : Muhammad Daffa Yusuf Fadhilah**

##### **NIM : 2100543**

### **Penjelasan**

Saya menggunakan struktur MVVM karena View dan Model tidak saling mengetahui, keduanya hanya dihubungkan oleh ViewModel.

View pada program ini adalah `Synchronization.java` yang memanggil `Game.java` yang merupakan ViewModel. View tidak mengakses model secara langsung.

ViewModel pada progam ini adalah `Game.java dan Controller.java` yang bertugas untuk mengolah data dari model yang nantinya akan ditampilkan melalui view.

Model pada program ini hanya berisi attribut yang mana nantinya akan diolah oleh para ViewModel
