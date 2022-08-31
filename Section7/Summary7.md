## Summary
Pada Section 07, saya mempelejari tentang Branching, Looping, dan Function pada Bahasa Pemrograman Dart.

### Branching
>Branching atau pengambilan keputusan merupakan penentuan alur program pada kondisi tertentu.

Branching memiliki beberapa jenis :

#### IF
- Memerlukan nilai bool dari logical atau comparison
- Menjalankan bagian proses jika bernilai true

#### If-ELSE
- Berjalan dengan if
- Menambah alternatif jika bernilai false

#### Sisipan ELSE-IF
- Berjalan dengan if
- Menambah alternatif jika bernilai false
- Menambah pengujian nilai bool lain

### Looping
>Looping atau perulangan merupakan menjalankan proses berulang kali

Looping memiliki beberapa jenis :

#### For
- Diketahui berapa kali perulangan terjadi
- Memerlukan nilai awal
- Memerlukan nilai bool, jika true maka perualngan dilanjutkan
- Memerlukan pengubah nilai

#### While
- Tidak diketahui berapa kali perulangan terjadi
- Memerlukan nilai bool, jika true maka perulangnan dilanjutkan

#### Do-While
- Mengubah bentuk while
- Proses dijalankan minimum sekali, akan diteruskan jika nilai bool adalah true

### Break dan Continue
> Cara lain menghentikan perulangan

- Perulangan menggunakan nilai bool untuk lanjut atau berhenti
- Break dan continue dapat menghentikan perulangan dengan mengabaikan nilai bool
- Continue dapat menghentikan satu kali proses

#### Perbedaan Break dan Continue
>Break akan menghentikan seluruh proses perulangan, sedangkan Continue hanya menghentikan satu kali proses perulangan.

### Fungsi
> Fungsi merupakan kumpulan kode yang dapat digunakan berulang kali. Dengan menggunakan fungsi, cukup mengubah fungsi sekali maka penggunaan lainnya akan ikut berubah.

#### Membuat fungsi
```
tipe_data nama_fungsi () {
   // perintah yang dijalankan saat fungsi dipanggil
}
```

#### Memanggil Fungsi
```
nama_fungsi ();
```

#### Fungsi dengan Parameter
>Mengirim data saat menjalankan fungsi
```
tipe_data nama_fungsi(tipe_data nama_parameter) {
    // perintah yang dijalankan saat fungsi dipanggil
}
```

#### Fungsi dengan Return
>Memberi nilai pada fungsi saat dipanggil
```
tipe_data nama_fungsi(tipe_data nama_parameter) {
    // perintah yang dijalankan saat funhgsi dipanggil
    return nilai;
}
```
