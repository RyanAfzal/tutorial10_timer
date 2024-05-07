# Tutorial 10
Nama : Ryandhika Al Afzal
NPM : 2206081502
Kelas : Adpro A

### Refleksi
![image](https://github.com/RyanAfzal/tutorial10_timer/assets/137851158/a12c5026-05c2-4146-afc4-3f8177139dd5)
Dapat diketahui dari mempelajari hasil run kode tersebut fungsi async dijalankan tidak bergantung kepada fungsi utama atau independen. Oleh karena itu bisa saja "hey hey" muncul sebelum "howdy!" dan "done!". Hal ini disebabkan kode ```println!("hey hey");``` berada di luar fungsi *async*, sehingga dapat dieksekusi secara independen dari eksekusi fungsi *async*.

![image](https://github.com/RyanAfzal/tutorial10_timer/assets/137851158/2bd2dabe-a5b6-4330-bcbb-8caef87bbf13)
- Dari output diketahui bahwa semakin banyak spawner menyebabkan lebih banyak tugas yang harus dijalankan karena penambahan tugas yang di queue oleh pengirim tugas 
- Tidak drop spawner membuat program tidak pernah berhenti karena sistem akan menganggap masih ada transmisi yang akan dikirimkan. ```drop spawner``` berfungsi untuk memberi tahu program bahwa interaksi selesai dan spawner akan ditutup.
- Eksekutor akan mengambil satu tugas dari pengirim tugas dan menjalankannya, kemudian mengambil tugas lainnya sampai semua tugas selesai.

