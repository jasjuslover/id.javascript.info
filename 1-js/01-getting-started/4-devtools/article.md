# Konsol pengembang

Yang namanya kode selalu rentan error. Mudah sekali bagimu bikin error... Benar kan? Kamu *tidak akan pernah* luput dari error, itu karena kamu manusia, bukan [robot](https://en.wikipedia.org/wiki/Bender_(Futurama)).

Tapi di dalam peramban, error tidak terlihat ke pengguna secara default. Jadi, kalau ada yang salah di script, itu tidak kelihatan mata kita dan kita sudah memperbaiki itu.

Supaya bisa melihat error dan memperoleh informasi berfaedah lainnya dari script, "tools pengembang" ditanamkan di dalam peramban.

Kebanyakan pengembang memakai Chrome atau Firefox untuk pengembangan karena tools pengembangan yang mereka punya paling mantap. Peramban lain juga memilikinya, ada yang memiliki fitur spesial, biasanya menyamai Chrome atau Firefox. Jadi, kebanyakan pengembang memiliki browser "favorit"-nya sendiri dan berpindah ke yang lainnya, ketika ada masalah yang spesifik dengan browser-nya.

Tools pengembang mengandung banyak manfaat; mereka punya banyak fitur. Untuk memulainya, kita akan belajar cara membuka mereka, mencari error, dan menjalankan perintah JavaScript.

## Google Chrome

Buka laman [bug.html](bug.html).

Ada satu error di dalam kode JavaScript di situ. Ia tersembunyi dari mata pengunjung biasa, mari kita buka tools pengembang untuk melihatnya.

Tekan `key:F12` atau, kalau kamu pakai Mac, tekan `key:Cmd+Opt+J`.

Tools pengembang akan terbuka pada Console tab secara default.

Nanti tampilannya seperti ini:

![chrome](chrome.png)

Tampilan persisnya tools pengembang tergantung versi Chrome kamu. Ia berubah dari masa ke masa tapi tetap serupa.

- Di sini kita bisa melihat pesan error berwarna merah. Di sini, scriptnya mengandung perintah asing "lalala".
- Di kanan, ada link yang bisa diklik ke sumber `bug.html:12` dengan nomor baris di mana error itu muncul.

Di bawah pesan error, ada simbol `>` berwarna biru. Ia menandakan "command line" di mana kita bisa mengetik perintah JavaScript. Tekan `key:Enter` untuk menjalankannya.

Sekarang kita bisa melihat error, dan itu sudah cukup untuk permulaan. Kita nanti akan kembali ke tools pengembang dan mengcover debugging lebih dalam di bab <info:debugging-chrome>.

```smart header="Multi-line input"
Biasanya, ketika kita memasukan baris code ke dalam console, dan menekan `key:Enter`, console akan mengeksekusinya.

Untuk memasukan baris baru, tekan `key:Shift+Enter`. Cara ini akan memasukan bagian-bagian panjang dari code JavaScript.
```

## Firefox, Edge, dan lainnya

Banyak peramban lain memakai `key:F12` untuk membuka tools pengembang.

Look & feel mereka hampir mirip. Sekali kamu tahu cara memakainya (kamu bisa mulai dengan Chrome), kamu bisa dengan mudah ganti dari satu ke yang lain.

## Safari

Safari (peramban Mac, tidak didukung Windows/Linux) agak sedikit spesial di sini. Kita harus mengaktifkan "Develop menu" terlebih dulu.

Buka Preferences dan pergi ke "Advanced" pane. Di sana ada checkbox di sebelah bawah:

![safari](safari.png)

Sekarang `key:Cmd+Opt+C` bisa mentoggle konsol. Lalu, menu "Develop" muncul pada menu item di atas. Ia punya banyak perintah dan opsi.

## Kesimpulan

- Tools pengembang memungkinkan kita melihat error, menjalankan perintah, memeriksa variabel, dan sebagainya.
- Mereka bisa dibuka dengan `key:F12` untuk kebanyakan peramban di Windows. Chrome di Mac dengan `key:Cmd+Opt+J`, Safari `key:Cmd+Opt+C` (harus diaktifkan terlebih dulu).

Kini kita sudah menyiapkan lingkungannya. Di seksi berikutnya, kita akan terjun ke JavaScript.
