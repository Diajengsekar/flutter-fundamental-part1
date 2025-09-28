
**Nama Lengkap: Diajeng Sekar Arum**
**Kelas : SIB 3F**
**NIM : 2341760070**
**JOBSHEET 4 : APLIKASI PERTAMA DAN WIDGET DASAR FLUTTER**
-------------------------------------------------------------------

Praktikum 1 : Membuat Project Flutter Baru

1.	Buka VS Code, lalu tekan tombol Ctrl + Shift + P maka akan tampil Command Palette, lalu ketik Flutter. Pilih New Application Project.
![Screenshot](images/prak1.1.png)

2.	Kemudian buat folder sesuai style laporan praktikum yang Anda pilih. Disarankan pada folder dokumen atau desktop atau alamat folder lain yang tidak terlalu dalam atau panjang. Lalu pilih Select a folder to create the project in.
![Screenshot](images/prak1.2.png)

3.	Buat nama project flutter hello_world seperti berikut, lalu tekan Enter. Tunggu hingga proses pembuatan project baru selesai.
![Screenshot](images/prak1.3.png)

4.	Jika sudah selesai proses pembuatan project baru, pastikan tampilan seperti berikut. Pesan akan tampil berupa "Your Flutter Project is ready!" artinya Anda telah berhasil membuat project Flutter baru.
![Screenshot](images/prak1.4.png)

===========================================================================

Praktikum 2: Menghubungkan Perangkat Android atau Emulator

Mengaktifkan proses debug USB
1.	Di perangkat Android, ketuk Settings > About phone.
![Screenshot](images/prak2.1.png)

2.	Ketuk Build number tujuh kali.

3.	Jika diminta, masukkan sandi atau PIN perangkat. Anda tahu Anda telah berhasil saat melihat pesan You are now a developer!.
![Screenshot](images/prak2.3.png)

4.	Kembali ke Settings, lalu ketuk System > Developer options.

5.	Jika Anda tidak melihat Developer options, ketuk Advanced options.
![Screenshot](images/prak2.5.png)

6.	Ketuk Opsi developer, lalu ketuk tombol Proses debug USB untuk mengaktifkannya
![Screenshot](images/prak2.6.png)
---------------------------------------------------------------------------
Menginstal Driver USB Google (khusus Windows)
1.	Di Android Studio, klik Tools > SDK Manager. Dialog Preferences > Appearance & Behavior > System Settings > Android SDK akan terbuka.

2.	Klik tab SDK Tools.

3.	Pilih Google USB Driver, lalu klik OK.
![Screenshot](images/prak2.2.3.png)
---------------------------------------------------------------------------
Menjalankan aplikasi di perangkat Android menggunakan kabel
1.	Sambungkan perangkat Android ke komputer menggunakan kabel USB. Dialog yang meminta Anda mengizinkan proses debug USB akan muncul di perangkat.
![Screenshot](images/prak2.3.1.png)

2.	Pilih kotak centang Always allow from this computer, lalu ketuk OK.

3.	Di Android Studio di komputer, pastikan perangkat Anda dipilih di menu dropdown. Klik run.
![Screenshot](images/prak2.3.3.png)

4.	Pilih perangkat lalu klik OK. Android Studio akan menginstal aplikasi di perangkat, lalu menjalankannya.

5.	Jika perangkat menjalankan platform Android yang tidak diinstal di Android Studio dan melihat pesan berisi pertanyaan apakah Anda ingin menginstal platform yang diperlukan, klik Install > Continue > Finish. Android Studio akan menginstal aplikasi di perangkat, lalu menjalankannya.
![Screenshot](images/prak2.3.hasil.png)

===========================================================================

Praktikum 3: Membuat Repository GitHub dan Laporan Praktikum

1.	Login ke akun GitHub Anda, lalu buat repository baru dengan nama "flutter-fundamental-part1"
![Screenshot](images/prak3.1.png)

2.	Lalu klik tombol "Create repository" lalu akan tampil seperti gambar berikut
![Screenshot](images/prak3.2.png)

3.	Kembali ke VS code, project flutter hello_world, buka terminal pada menu Terminal > New Terminal. Lalu ketik perintah berikut untuk inisialisasi git pada project Anda.
![Screenshot](images/prak3.3.png)

4.	Pilih menu Source Control di bagian kiri, lalu lakukan stages (+) pada file .gitignore untuk mengunggah file pertama ke repository GitHub.
![Screenshot](images/prak3.4.png)

5.	Beri pesan commit "tambah gitignore" lalu klik Commit (✔)
![Screenshot](images/prak3.5.png)

6.	Lakukan push dengan klik bagian menu titik tiga > Push
![Screenshot](images/prak3.6.png)

7.	Di pojok kanan bawah akan tampil seperti gambar berikut. Klik "Add Remote"
![Screenshot](images/prak3.7.png)

8.	Salin tautan repository Anda dari browser ke bagian ini, lalu klik Add remote
![Screenshot](images/prak3.8.png)

9.	Setelah berhasil, tulis remote name dengan "origin"
![Screenshot](images/prak3.9.png)

10.	Lakukan hal yang sama pada file README.md mulai dari Langkah 4. Setelah berhasil melakukan push, masukkan username GitHub Anda dan password berupa token yang telah dibuat (pengganti password konvensional ketika Anda login di browser GitHub). Reload halaman repository GitHub Anda, maka akan tampil hasil push kedua file tersebut seperti gambar berikut.
![Screenshot](images/prak3.10.png)

11.	Lakukan push juga untuk semua file lainnya dengan pilih Stage All Changes. Beri pesan commit "project hello_world". Maka akan tampil di repository GitHub Anda seperti berikut.
![Screenshot](images/prak3.11.png)

12.	Kembali ke VS Code, ubah platform di pojok kanan bawah ke emulator atau device atau bisa juga menggunakan browser Chrome. Lalu coba running project hello_world dengan tekan F5 atau Run > Start Debugging. Tunggu proses kompilasi hingga selesai, maka aplikasi flutter pertama Anda akan tampil seperti berikut.
![Screenshot](images/prak3.12.png)

13.	Silakan screenshot seperti pada Langkah 11, namun teks yang ditampilkan dalam aplikasi berupa nama lengkap Anda. Simpan file screenshot dengan nama 01.png pada folder images (buat folder baru jika belum ada) di project hello_world Anda. Lalu ubah isi README.md seperti berikut, sehingga tampil hasil screenshot pada file README.md. Kemudian push ke repository Anda.
![Screenshot](images/prak3.13.png)

===========================================================================

Praktikum 4: Menerapkan Widget Dasar
Langkah 1: Text Widget

1. Buat folder baru basic_widgets di dalam folder lib. Kemudian buat file baru di dalam basic_widgets dengan nama text_widget.dart. Ketik atau salin kode program berikut ke project hello_world Anda pada file text_widget.dart.
![Screenshot](images/prak4.1.1.png)
2. Lakukan import file text_widget.dart ke main.dart, lalu ganti bagian text widget dengan kode di atas. Maka hasilnya seperti gambar berikut. Screenshot hasil milik Anda, lalu dibuat laporan pada file README.md.
![Screenshot](images/prak4.1.2.png)
![Screenshot](images/prak4.1.3.png)
![Screenshot](images/prak4.1.4.png)
---------------------------------------------------------------------------
Langkah 2: Image Widget

1. Buat sebuah file image_widget.dart di dalam folder basic_widgets dengan isi kode berikut.
![Screenshot](images/prak4.2.1.png)
2. Lakukan penyesuaian asset pada file pubspec.yaml dan tambahkan file logo Anda di folder assets project hello_world.
![Screenshot](images/prak4.2.2.png)
3. Jangan lupa sesuaikan kode dan import di file main.dart kemudian akan tampil gambar seperti berikut.
![Screenshot](images/prak4.2.3.png)
===========================================================================

Praktikum 5: Menerapkan Widget Material Design dan iOS Cupertino
1.	Buat file di basic_widgets > loading_cupertino.dart. Import stateless widget dari material dan cupertino. Lalu isi kode di dalam method Widget build adalah sebagai berikut.
![Screenshot](images/prak5.1.1.png)
![Screenshot](images/prak5.1.2.png)

2.	Button widget terdapat beberapa macam pada flutter yaitu ButtonBar, DropdownButton, TextButton, FloatingActionButton, IconButton, OutlineButton, PopupMenuButton, dan ElevatedButton.
Buat file di basic_widgets > fab_widget.dart. Import stateless widget dari material. Lalu isi kode di dalam method Widget build adalah sebagai berikut.
![Screenshot](images/prak5.2.1.png)
![Screenshot](images/prak5.2.2.png)

3.	Scaffold widget digunakan untuk mengatur tata letak sesuai dengan material design.
Ubah isi kode main.dart seperti berikut.
![Screenshot](images/prak5.3.png)

4.	Dialog widget pada flutter memiliki dua jenis dialog yaitu AlertDialog dan SimpleDialog.
Ubah isi kode main.dart seperti berikut.
![Screenshot](images/prak5.4.png)

5.	Flutter menyediakan widget yang dapat menerima input dari pengguna aplikasi yaitu antara lain Checkbox, Date and Time Pickers, Radio Button, Slider, Switch, TextField.
Contoh penggunaan TextField widget adalah sebagai berikut:
![Screenshot](images/prak5.5.png)

6.	Date and Time Pickers termasuk pada kategori input dan selection widget, berikut adalah contoh penggunaan Date and Time Pickers.
![Screenshot](images/prak5.6.png)
![Screenshot](images/prak5.6.1.png)


