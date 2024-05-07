# Tutorial 10
Nama : Ryandhika Al Afzal
NPM : 2206081502
Kelas : Adpro A

### Refleksi
![image](https://github.com/RyanAfzal/tutorial10_timer/assets/137851158/a12c5026-05c2-4146-afc4-3f8177139dd5)
Dapat diketahui dari mempelajari hasil run kode tersebut fungsi async dijalankan tidak bergantung kepada fungsi utama atau independen. Oleh karena itu bisa saja "hey hey" muncul sebelum "howdy!" dan "done!". Hal ini disebabkan kode ```println!("hey hey");``` berada di luar fungsi *async*, sehingga dapat dieksekusi secara independen dari eksekusi fungsi *async*.