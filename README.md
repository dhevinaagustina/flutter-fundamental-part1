# hello_world

A new Flutter project.

## Praktikum 1

### Langkah 1
Buka **VS Code**, lalu tekan tombol `Ctrl + Shift + P` maka akan tampil **Command Palette**, lalu ketik **Flutter**. Pilih **New Application Project**.

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ab2d995e-590a-4caf-95c6-03242c90a370" />

### Langkah 2
Kemudian buat folder sesuai style laporan praktikum yang Anda pilih. Disarankan pada folder dokumen atau desktop atau alamat folder lain yang tidak terlalu dalam atau panjang. Lalu pilih Select a folder to create the project in.

<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/2a8c07c9-d636-48c6-b34c-09ccf922020c" />

### Langkah 3
Buat nama project flutter hello_world seperti berikut, lalu tekan Enter. Tunggu hingga proses pembuatan project baru selesai.

<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/8cea863c-be0e-408d-8b48-593228b6293e" />

### Langkah 4
Jika sudah selesai proses pembuatan project baru, pastikan tampilan seperti berikut. Pesan akan tampil berupa "Your Flutter Project is ready!" artinya Anda telah berhasil membuat project Flutter baru.

<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/36301f35-25e2-43e3-80e8-9013760a6d65" />

## Praktikum 2

### Langkah 1
Melakukan setting Developer Mode di HP
![Screenshot hello_world](images/02.jpg)


### Langkah 2
Menjalankan aplikasi dari VSCode dan disesuaikan dengan HP yang sudah terhubung
![Screenshot hello_world](images/03.jpg)

### Langkah 3
Aplikasi dapat dijalankan di HP
![Screenshot hello_world](images/04.jpg)

## Praktikum 3

### Langkah 1
Login ke akun GitHub Anda, lalu buat repository baru dengan nama "flutter-fundamental-part1"
![Screenshot hello_world](images/05.png)

### Langkah 2
Lalu klik tombol "Create repository" lalu akan tampil seperti gambar berikut.
![Screenshot hello_world](images/06.png)

### Langkah 3
Kembali ke VS code, project flutter hello_world, buka terminal pada menu Terminal > New Terminal. Lalu ketik perintah berikut untuk inisialisasi git pada project Anda.
![Screenshot hello_world](images/07.png)

### Langkah 4
Pilih menu Source Control di bagian kiri, lalu lakukan stages (+) pada file .gitignore untuk mengunggah file pertama ke repository GitHub.
![Screenshot hello_world](images/08.png)

### Langkah 5
Beri pesan commit "tambah gitignore" lalu klik Commit (✔)
![Screenshot hello_world](images/09.png)

### Langkah 6
Lakukan push dengan klik bagian menu titik tiga > Push
![Screenshot hello_world](images/10.png)

### Langkah 7
Di pojok kanan bawah akan tampil seperti gambar berikut. Klik "Add Remote"
![Screenshot hello_world](images/11.png)

### Langkah 8
Salin tautan repository Anda dari browser ke bagian ini, lalu klik Add remote
![Screenshot hello_world](images/12.png)
Setelah berhasil, tulis remote name dengan "origin"
![Screenshot hello_world](images/13.png)

### Langkah 9
Lakukan hal yang sama pada file README.md mulai dari Langkah 4
![Screenshot hello_world](images/14.png)

### Langkah 10
Lakukan push juga untuk semua file lainnya dengan pilih Stage All Changes. Beri pesan commit "project hello_world". Maka akan tampil di repository GitHub Anda seperti berikut.
![Screenshot hello_world](images/15.png)

### Langkah 11
Kembali ke VS Code, ubah platform di pojok kanan bawah ke emulator atau device atau bisa juga menggunakan browser Chrome. Lalu coba running project hello_world dengan tekan F5 atau Run > Start Debugging. Tunggu proses kompilasi hingga selesai, maka aplikasi flutter pertama Anda akan tampil seperti berikut.
![Screenshot hello_world](images/16.png)

### Langkah 12
Silakan screenshot seperti pada Langkah 11, namun teks yang ditampilkan dalam aplikasi berupa nama lengkap Anda. Simpan file screenshot dengan nama 01.png pada folder images (buat folder baru jika belum ada) di project hello_world Anda. Lalu ubah isi README.md seperti berikut, sehingga tampil hasil screenshot pada file README.md. Kemudian push ke repository Anda.
![Screenshot hello_world](images/01.png.png)

## Praktikum 4

### Langkah 1: Text Widget
Buat folder baru basic_widgets di dalam folder lib. Kemudian buat file baru di dalam basic_widgets dengan nama text_widget.dart. Ketik atau salin kode program berikut ke project hello_world Anda pada file text_widget.dart.
![Screenshot hello_world](images/17.png)

Lakukan import file text_widget.dart ke main.dart, lalu ganti bagian text widget dengan kode di atas. Maka hasilnya seperti gambar berikut. Screenshot hasil milik Anda, lalu dibuat laporan pada file README.md.
![Screenshot hello_world](images/21.png)

### Langkah 2: Image Widget
Buat sebuah file image_widget.dart di dalam folder basic_widgets dengan isi kode berikut.
![Screenshot hello_world](images/19.png)
Lakukan penyesuaian asset pada file pubspec.yaml dan tambahkan file logo Anda di folder assets project hello_world.
![Screenshot hello_world](images/20.png)
Jangan lupa sesuaikan kode dan import di file main.dart kemudian akan tampil gambar seperti berikut.
![Screenshot hello_world](images/22.png)

## Praktikum 5

### Langkah 11: Cupertino Button dan Loading Bar
Buat file di basic_widgets > loading_cupertino.dart. Import stateless widget dari material dan cupertino. Lalu isi kode di dalam method Widget build adalah sebagai berikut.
![Screenshot hello_world](images/23.png)

### Langkah 2: Floating Action Button (FAB)
Button widget terdapat beberapa macam pada flutter yaitu ButtonBar, DropdownButton, TextButton, FloatingActionButton, IconButton, OutlineButton, PopupMenuButton, dan ElevatedButton.

Buat file di basic_widgets > fab_widget.dart. Import stateless widget dari material. Lalu isi kode di dalam method Widget build adalah sebagai berikut.
![Screenshot hello_world](images/24.png)

### Langkah 3: Scaffold Widget
Scaffold widget digunakan untuk mengatur tata letak sesuai dengan material design.

Ubah isi kode main.dart seperti berikut
![Screenshot hello_world](images/25.png)

### Langkah 4: Dialog Widget
Dialog widget pada flutter memiliki dua jenis dialog yaitu AlertDialog dan SimpleDialog.

Ubah isi kode main.dart seperti berikut.
![Screenshot hello_world](images/26.png)


### Langkah 5: Input dan Selection Widget
Flutter menyediakan widget yang dapat menerima input dari pengguna aplikasi yaitu antara lain Checkbox, Date and Time Pickers, Radio Button, Slider, Switch, TextField.

Contoh penggunaan TextField widget adalah sebagai berikut:
![Screenshot hello_world](images/27.png)

### Langkah 6: Date and Time Pickers
Date and Time Pickers termasuk pada kategori input dan selection widget, berikut adalah contoh penggunaan Date and Time Pickers.
![Screenshot hello_world](images/28.png)
![Screenshot hello_world](images/29.png)





