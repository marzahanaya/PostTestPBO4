# PostTestPBO4

## Sistem Manajemen Kursus Online
Nama: Marza Hanaya Melodya Goga

NIM: 2409116103

### Deskripsi Program
Program Sistem Manajemen Kursus Online ini dibuat untuk membantu pengguna dalam mengelola informasi kursus secara lebih terstruktur. Pengguna dapat menambahkan data kursus baru, melihat daftar kursus yang tersedia, memperbarui detail kursus, serta menghapus kursus yang sudah tidak digunakan. Program ini ditulis menggunakan bahasa pemrograman Java dan menerapkan konsep pemrograman berorientasi objek dengan beberapa kelas utama, yaitu MainKursus sebagai main class, KursusOnline dan KursusOffline untuk menyimpan data kursus sesuai jenisnya, serta ModelKursus sebagai abstract class dasar. Selain itu, program ini juga menggunakan interface Evaluasi untuk memberikan nilai dan laporan hasil, sehingga konsep abstraction dan polymorphism dapat diterapkan secara nyata.

### Struktur Program

<img width="298" height="271" alt="Screenshot 2025-09-30 093551" src="https://github.com/user-attachments/assets/8f6d68fe-bf39-4979-8f4a-c932c9e8ec7a" />

### Penerapan Abstraction

Penerapan Abstraction dalam program ini terdapat pada abstract class ModelKursus yang memiliki method abstract getTipe() dan diimplementasikan secara berbeda pada class KursusOnline dan KursusOffline. Selain itu, program juga menggunakan interface Evaluasi yang diimplementasikan oleh class KursusOnline untuk memberikan nilai serta membuat laporan hasil.

### Penerapan Polymorphism

Penerapan Polymorphism ditunjukkan melalui Overriding, yaitu method getTipe() pada KursusOnline dan KursusOffline yang menyesuaikan output sesuai jenis kursusnya, serta implementasi method dari interface Evaluasi. Sedangkan Overloading diterapkan pada class Siswa dengan adanya method setter setNama() yang dapat digunakan untuk memperbarui nilai atribut dengan fleksibilitas parameter.

### Output Program
<img width="654" height="214" alt="Screenshot 2025-09-30 131514" src="https://github.com/user-attachments/assets/8eb61296-78b7-4066-9e35-9eeb6532c4a7" />

<img width="794" height="360" alt="Screenshot 2025-09-30 153832" src="https://github.com/user-attachments/assets/659784d9-b464-4fe8-b20e-4fb4fe002be9" />

<img width="990" height="333" alt="Screenshot 2025-09-30 131601" src="https://github.com/user-attachments/assets/4cb67c9e-c525-4af2-a1d4-a0daed9fa2a2" />

<img width="814" height="351" alt="Screenshot 2025-09-30 154002" src="https://github.com/user-attachments/assets/4a3431b8-0c86-4df0-8cb6-3015f4ed895e" />

<img width="619" height="280" alt="Screenshot 2025-09-30 154042" src="https://github.com/user-attachments/assets/591bfb08-24ca-45eb-a50d-50b1b1783266" />

<img width="733" height="310" alt="Screenshot 2025-09-30 154054" src="https://github.com/user-attachments/assets/c32358c5-a2fe-4ba2-b62f-a358db9cf56b" />

<img width="1128" height="564" alt="Screenshot 2025-09-30 154239" src="https://github.com/user-attachments/assets/ca540c1d-7853-4cb3-a1d2-3122b452f213" />
