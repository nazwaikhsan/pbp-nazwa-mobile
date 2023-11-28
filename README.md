*Purrfect Pages*
<hr>

### **Pertanyaan:***
**Apa perbedaan utama antara stateless dan stateful widget dalam konteks pengembangan aplikasi Flutter?**
Stateless widget tidak memiliki state, mereka tidak bisa diubah melalui internal action/behaviour. Stateless widget cenderung lebih efisien secara performa karena tidak perlu mempertahankan keadaan internal. Sedangkan, Stateful widget memiliki keadaan internal yang dapat berubah. Hal ini memungkinkan widget untuk merespons perubahan dan memperbarui antarmuka pengguna secara dinamis. Stateful widget cenderung lebih kompleks daripada stateless widget karena mereka harus mengelola keadaan mereka sendiri. 
**Sebutkan seluruh widget yang kamu gunakan untuk menyelesaikan tugas ini dan jelaskan fungsinya masing-masing. **
MyApp yaitu root aplikasi yang berfungsi untuk mengatur tampilan UI utama, MyHomePage sebagai struktur dasar page, mengatur tata letak icon dan membuat icon bar, ShopItem untuk merepresentasikan objek item, dan ShopCard untuk menampilkan item.  
**Jelaskan bagaimana cara kamu mengimplementasikan checklist di atas secara step-by-step (bukan hanya sekadar mengikuti tutorial)**
Melakukan inisiasi proyek flutter pada terminal, selanjutnya membuat file baru yaitu menu.dart untuk merapikan struktur proyek agar lebih manageable, setelahnya mengimport package flutter pada file menu.dart, lalu memindahkan widget MyHomePage dari main.dart ke menu.dart dan mengubah sifatnya dari stateful menjadi stateless. lalu dibuat class ShopItem untuk memperlihatkan daftar item sekaligus membuat button Lihat Produk, Tambah Produk, dan Logout. Lalu, dilakukan pula set up proyek dengan mengatur padding, spacing, dsb di Widget Build. Terakhir, membuat class baru yaitu ShopCard untuk menampilkan card yang nantinya juga akan menampilkan snackbar untuk setiap button yang telah dibuat. 
<hr>
