Pemrograman Web

Laporan Praktikum Portfolio menggunakan HTML dan CSS

Gede Troy Wiswama Bhareswara

NIM : 42430052

FAKULTAS TEKNIK DAN INFORMATIKA PROGRAM STUDI TEKNOLOGI INFORMASI

1. PENDAHULUAN
   
CV Portfolio ini dibuat sebagai media untuk memperkenalkan diri, latar belakang pendidikan, pengalaman, serta keterampilan yang saya miliki. Dengan adanya CV ini, saya berharap dapat memberikan gambaran singkat mengenai potensi dan kompetensi saya, baik di bidang akademik, olahraga, maupun pengembangan teknologi.

2. PEMBAHASAN

<img width="1229" height="776" alt="Screenshot 2025-10-01 223547" src="https://github.com/user-attachments/assets/b585a99c-d672-46a2-b00a-50d582b516ab" />


Kode HTML di atas adalah sebuah CV Portfolio yang disusun menggunakan struktur HTML5 dengan elemen semantik agar lebih rapi dan mudah dibaca. Bagian awal menggunakan <!DOCTYPE html> untuk mendefinisikan dokumen sebagai HTML5, <html lang="en"> untuk bahasa halaman, serta <meta charset="UTF-8"> dan <meta name="viewport"> agar halaman tampil baik di berbagai perangkat. Di dalam <head> juga ada <title> untuk judul tab browser dan <link rel="stylesheet" href="style.css"> yang memisahkan tampilan dengan file CSS eksternal.

Pada <body>, terdapat <header> yang berisi nama lengkap dan peran utama, lalu <nav> dengan link <a> menuju tiap bagian menggunakan id sehingga memudahkan navigasi antar section. Bagian konten utama diletakkan dalam <main> dengan beberapa <section> seperti About, Skills, Experience, Education, Projects, dan Contact. Di dalamnya digunakan heading <h2> sebagai judul bagian, <p> untuk deskripsi, serta <ul> dan <li> untuk menampilkan daftar keterampilan maupun pengalaman. Pada bagian Projects terdapat <a> dengan atribut target="_blank" agar link GitHub terbuka di tab baru. Terakhir, <footer> digunakan untuk menampilkan informasi hak cipta sebagai penutup halaman.

Penggunaan elemen semantik (<header>, <nav>, <main>, <section>, <footer>) sangat penting karena membuat struktur lebih jelas, mudah dipahami manusia maupun mesin pencari, serta meningkatkan aksesibilitas dan SEO.
