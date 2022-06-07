## Tentang CEK-LULUS

Web cek kelulusan dibuat dengan laravel, vuejs 2 cdn, Axios, dengan template STACK ADMIN 3.

-   Terdapat Fitur upload siswa Excel dengan format template yang sudah disediakan tanpa ribet harus input 1 per 1 siswa
-   Terdapat juga Fitur Edit web seperti setting slide gambar , logo, nama web, title web
-   Terdapat juga Fitur Cetak dan setting surat keterangan lulus (skl)

## CARA INSTALL

Untuk Menginstall Secara Lokal Pastikan PHP anda diatas > 7.3

-   Clone Repository ini Diterminal kesayangan anda `git clone https://github.com/zifaucode/cek-lulus.git`
-   Ketikan `composer install`
-   Rename .env-lokal menjadi .env dan edit sesuai konfigurasi database anda
-   migrate databasenya : `php artisan migrate`

opsi selain migrate database :

-   File SQL terletak pada foldel DBNYA-INI , import ke dalam mysql anda

Dan Jalankan

-   `php artisan optimize` dan `php artisan serve`


## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
