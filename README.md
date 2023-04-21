# TP2DPBO2023
Saya Nadhief Athallah Isya NIM 2106413 mengerjakan LP7 dalam mata kuliah Desain dan Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

## Deskripsi Tugas
Modifikasi kode yang ada. Ketika pencet WASD, skor masih jadi 1 2 3 4 secara hardcode. Nahh, modifikasi skor nya sehingga ketika ganti tombol yang dipencet, skornya selalu bertambah. Misal, posisi sekarang 0. Pencet W, tambah 1. Jadi satu, berhenti. Pencet D, tambah satu. Jadi 2, berhenti. Pencet apapun lagi asal WASD, tambah satu. Jadi 3. dst. ditambah kayak yang kotak-kotak kujelasin kemaren

## Run Program
Jalankan program jar atau run file main.java didalam project

## Design Program
Program ini memiliki beberapa kelas diantaranya:

kelas Controller, kelas ini memiliki dua atribut game dan handler. method yang terdapat dalam kelas ini adalah keyPressed() dan keyReleased(). fungsinya untuk mengontrol objek.

kelas Display, kelas ini ga punya atribut tapi punya dua method yaitu open dan close. fungsinya untuk menampilkan objek kedalam frame.

kelas Game, kelas ini ga punya atribut tapi punya beberapa method yaitu start(), stop(), render(), loop(), dan juga ada get set buat running sama skor serta fungsi clamp() biar objek bola nya ga tembus frame. fungsinya buat jalanin gamenya.

kelas GameObject, kelas ini punya banyak objek yaitu x dan y buat ngatur posisi, width dan height buat ngatur dimensi, velx dan vely buat velocity, sama type buat tipe objeknya. tiap objek punya getter dan setter nya dan juga render() dan lopp().

kelas  Handler, kelas ini ada dua atribut yaitu object yang bertipe ArrayList GambeObject dan rand bertipe random. fungsinya buat mengatur atau mengelola objek yang ada dalam game. jadi objek yang udah di bikin di taro di ArrayList object.

kelas Player, kelas ini ga punya atribut apa tapi punya method yang sama kaya GameObject yaitu render() dan loop().

kelas Synchronization, kelas ini fungsiya untuk menjalankan gamenya.

interface GameInterface, interface ini punya dua methode yaitu render() dan loop(). fungsinya buat render objek dan looping objek sampai gamenya berhenti.

## Alur Program
User dapat menekan tombol WASD/panah key pada keyboard untuk menggerakkan object, setiap kali user menekan tombol WASD/panah maka skor akan bertambah 1, skor akan bertambah jika tombol dilepaskan. jika tombol hanya ditekan skor belum bertambah, tapi ketika di lepas skor akan bertambah 1.

## dokumentasi program
![Alt text](Screenshot%202023-04-21%20194217.png)

![Alt text](Screenshot%202023-04-21%20194424.png)

