
## Nama : Rahmawati
## Nim  : 220220077
## Universitas Muhammadiyah Banten 



# 📱 Aplikasi Login & Register Android dengan SQLite

Sebuah aplikasi Android sederhana yang memungkinkan pengguna untuk melakukan register dan login menggunakan database lokal SQLite. Dibangun menggunakan Java, XML, dan SQLite dengan Android Studio.



---

## 🚀 Fitur


---

* **Register dengan Nama, Email, Kata Sandi, dan Konfirmasi Kata Sandi**
* **Login menggunakan Email dan Kata Sandi yang sudah didaftarkan**
* **Validasi input:**

  * Format email harus valid
  * Kata sandi minimal 6 karakter
  * Kata sandi dan konfirmasi harus sama
* **Simpan data pengguna secara lokal menggunakan SQLite**
* **Tampilkan pesan sambutan dengan nama pengguna setelah login**

---

## 🧭 Alur Aplikasi

1. **Aplikasi Dibuka**
   - Langsung menampilkan halaman Login.

2. **Login**
   - User mengisi Email dan Password
   - Validasi:
     - Format email harus valid
     - Password minimal 6 karakter
   - Jika login sukses:
     - Arahkan ke halaman MainActivity
     - Tampilkan: `Selamat Datang, [Nama User]`
   - Jika gagal:
     - Tampilkan pesan error
   - Tersedia tombol untuk berpindah ke halaman Register

3. **Register**
   - User mengisi:
     - Nama
     - Email
     - Password
     - Konfirmasi Password
   - Validasi:
     - Semua input harus diisi
     - Email harus valid
     - Password dan konfirmasi minimal 6 karakter dan harus cocok
     - Email belum pernah digunakan
   - Jika valid:
     - Simpan data ke SQLite
     - Arahkan ke halaman Login

4. **MainActivity**
   - Menampilkan pesan: `Selamat Datang, [Nama User]`

---
## Tampilan Login 
![alt text](https://github.com/1rahmawati234/Pemrograman4-UMB/blob/master/gambar/login.png?raw=true)
## Tampilan Register
![alt text](https://github.com/1rahmawati234/Pemrograman4-UMB/blob/master/gambar/register..png?raw=true)
## Login tidak berhasil
![alt text](https://github.com/1rahmawati234/Pemrograman4-UMB/blob/master/gambar/login%20gagal..png?raw=true)
## Password kurang dari 6 karakter
![alt text](https://github.com/1rahmawati234/Pemrograman4-UMB/blob/master/gambar/password%20kurang..png?raw=true)
## Login Berhasil
![alt text](https://github.com/1rahmawati234/Pemrograman4-UMB/blob/master/gambar/login%20berhasil..png?raw=true)




