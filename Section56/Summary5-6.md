## Summary

Pada Section 05, saya mempelejari tentang Basic Dart Programming.

### Apa itu Dart?

>Dart merupakan bahasa pemrograman yang dirancang untuk membuat aplikasi. Aplikasi yang dibuat dengan Dart adalah aplikasi yang berjalan pada *FrontEnd* seperti Web, Desktop, dan Mobile.

Dart memiliki fitur seperti:

- *Type Safe* yaitu fitur yang dapat menjamin konsistensi tipe data
- *Null Safety* yaitu fitur yang memberi keamanan dari data yang bernilai *null*
- *Rich standard library* yaitu fitur yang memberikan banyak dukungan library internal
- *Multiplatform* yaitu fitur yang mampu berjalan pada berbagai jenis perangkat

### Dasar pemrograman Dart

Pada pemrograman Dart terdapat *Fungsi Main* yaitu bagian yang dijalankan pertama kali. *Fungsi Main* dapat memiliki tipe data *void* atau *int*.

### Komentar

>Komentar merupakan baris kode yang tidak dijalankan. Komentar dapat diaplikasikan seperti memberi catatan pada kode atau mencegah perintah dijalankan.

Untuk mendeklarasikan perintah *Komentar, dapat menuliskan program menggunakan 2 garing *""//"* diawal baris kode atau menggunakan tanda garing bintang *"/"* diawal baris kode dan tanda bintang garing *"/"** di akhir baris kode.

### Variable

>Variable digunakan untuk menyimpan sebuah data. Setiap Variable memiliki nama dan tipe data.

Untuk mendeklarasikan sebuah variable, dapat menuliskan *tipe data* terlebih dahulu, kemudian dilanjut dengan menuliskan *nama* variable. Jika ingin memberikan nilai pada variable, dapat menggunakan tanda *=* kemudian ditutup dengan tanda *;*.

### Konstanta

>Konstanta digunakan untuk menyimpan data. Setiap Variable memiliki nama dan tipe data. Nilai pada konstanta bersifat tetap(tidak dapat dirubah).

Untuk mendeklarasikan sebuah konstanta sama seperti mendeklarasikan variable.

### Tipe Data

>Tipe data merupakan jenis data yang dikelola. Tipe data sederhana disebut dengan primitive data type.

Jenis - jenis tipe data antara lain:

- int

int merupakan bilangan bulat.

- double

double merupakan bilangan pecahan.

- bool

bool atau boolean merupakan variable pengindikasian true or false.

- String

string merupakan variable dengan isi data berupa teks.

### Operator

>Operator digunakan untuk operasi pengolahan data. Data yang dikelola disebut operand.

- Arithmetic

Digunakan untuk perhitungan sistematis seperti +, -, *, /, %

- Assigment

Digunakan untuk memberikan nilai pada variable seperti =, +=, -=, *=, /=, %=

- Comparison

Digunakan untuk membandingkan kesetaraan nilai seperti ==, <, <=, >, >=

- Logical

Digunakan untuk menggabungkan beberapa kondisi seperti &&, ||, !

### Fungsi(lanjutan)

- Anonymous Function

>Anonymous Function tidak memiliki nama dan fungsinya sebagai data.

- Arrow Function

>Arrow Function dapat memiliki nama atau tidak. Berisi 1 data dari proses maupun data statis. 

### Async – Await

>menjalankan beberapa proses tanpa perlu menunggu. Proses ditulis dalam bentuk fungsi. Fungsi Await akan menunggu hingga proses async selesai.

### Tipe Data Future

>Tipe data Future merupakan data yang dapat ditunggu. Tipe data ini membawa data return dari fungsi async.

### Collection

>Collection merupakan kumpulan data pada suatu tempat

Ada beberapa jenis collection yaitu:

- List

Digunakan untuk menyimpan data secara berbaris. Tiap data memiliki index.

- Map

Digunakan untuk menyimpan key-value. Key berguna selayaknya index pada list.