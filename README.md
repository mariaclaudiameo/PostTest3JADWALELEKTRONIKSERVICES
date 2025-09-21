# PostTest3JADWALELEKTRONIKSERVICES
# SISTEM MANAJEMEN JADWAL SERVICES ALAT ELEKTRONIK
# Penjelasan Package
<img width="453" height="272" alt="image" src="https://github.com/user-attachments/assets/4a878aec-16b6-4d9e-a626-22ce843f95ca" />

dalam program ini terdapat beberapa class dengan fungsi masing-masing. class jadwal berperan sebagai superclass yang menyimpan atribut dasar berupa id, namaService, dan tanggal, lengkap dengan constructor, getter, dan setter untuk menerapkan konsep encapsulation. class ini juga memiliki method toString yang nantinya dioverride oleh subclass. selanjutnya, terdapat class jadwalelektronik dan jadwalKomputer yang menjadi subclass dari jadwal. keduanya menambahkan atribut khusus yaitu kategori dan melakukan overriding pada method tostring agar menampilkan informasi tambahan sesuai jenis service. kemudian, class jadwalservices berfungsi sebagai pengelola data jadwal dengan menerapkan operasi CRUD, yaitu menambah, menampilkan, memperbarui, menghapus, dan mencari jadwal. semua data jadwal disimpan dalam sebuah arrayList sehingga bisa menampung berbagai objek dari jadwal, baik induk maupun turunannya. terakhir, class mainApp bertugas sebagai titik masuk (entry point) program yang menampilkan menu interaktif untuk pengguna. Dari menu ini, pengguna bisa menambah jadwal service elektronik atau komputer, melihat daftar jadwal, menghapus, memperbarui, maupun mencari berdasarkan id.

# Encapsulation
encapsulation diterapkan di class jadwal dengan menjadikan atribut id, namaService, dan tanggal sebagai private. akses terhadap atribut dilakukan menggunakan getter dan setter. dengan cara ini, data lebih aman dan hanya bisa diubah melalui method yang disediakan.

<img width="916" height="354" alt="image" src="https://github.com/user-attachments/assets/95e1c977-0fdd-4654-b238-e80ae264d37a" />

# Inheritance
inheritance digunakan pada class jadwalElektronik dan jadwalKomputer yang mewarisi atribut serta method dari class jadwal dengan menggunakan keyword extends. hal ini memudahkan kode agar tidak perlu menulis ulang atribut dasar.

<img width="1034" height="396" alt="image" src="https://github.com/user-attachments/assets/4c11a458-e462-4efe-a817-170d4d9f81e5" />
<img width="962" height="399" alt="image" src="https://github.com/user-attachments/assets/acc47f66-d835-46fa-b5c3-dc131cdd718b" />

# Overriding
overriding dilakukan pada method tostring di subclass (jadwalElektronik dan jadwalKomputer). method ini menambahkan informasi baru seperti kategori, sehingga tampilan data lebih lengkap dibanding superclass.
<img width="784" height="133" alt="image" src="https://github.com/user-attachments/assets/baa14118-ac3d-4e12-8438-eb6d6087ddfe" />
<img width="744" height="130" alt="image" src="https://github.com/user-attachments/assets/33647ec8-5a6f-4a94-9329-4fc0760fd3bc" />

# CRUD
class jadwalservices mengelola daftar jadwal dengan ArrayList. operasi CRUD yang tersedia meliputi tambah jadwal, lihat semua jadwal, update jadwal, hapus jadwal, dan cari jadwal berdasarkan id.
<img width="806" height="729" alt="image" src="https://github.com/user-attachments/assets/f161eb1b-407c-4475-bab3-e71692073cff" />

# MainApp
class mainApp berfungsi sebagai titik masuk program. disini terdapat menu interaktif yang memungkinkan pengguna untuk memilih operasi CRUD terhadap data jadwal.
<img width="684" height="294" alt="image" src="https://github.com/user-attachments/assets/03ca4630-acb8-4845-a8e4-20fc2ce985e5" />
<img width="722" height="808" alt="image" src="https://github.com/user-attachments/assets/0a9418e9-7449-401e-80f9-c301c4edb084" />
<img width="710" height="816" alt="image" src="https://github.com/user-attachments/assets/8cfcb689-038b-48f3-b2ad-3de038a335d7" />
<img width="596" height="273" alt="image" src="https://github.com/user-attachments/assets/b7977900-6501-428b-ac1c-d5efbfe3df64" />

# Output
saat dijalankan, program menampilkan menu dan memungkinkan pengguna untuk menambah jadwal elektronik maupun komputer. data dapat dilihat, dihapus, diperbarui, serta dicari sesuai input id.
<img width="673" height="762" alt="image" src="https://github.com/user-attachments/assets/1c762727-aead-47d5-b8d0-642ab29b65f1" />
<img width="443" height="437" alt="image" src="https://github.com/user-attachments/assets/adf62c04-e515-4056-8e45-cf1cbbbc3d9b" />




