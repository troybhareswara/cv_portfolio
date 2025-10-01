Pemrograman Web

Laporan Praktikum Portfolio menggunakan HTML dan CSS

Gede Troy Wiswama Bhareswara

NIM : 42430052

FAKULTAS TEKNIK DAN INFORMATIKA PROGRAM STUDI TEKNOLOGI INFORMASI

1. PENDAHULUAN
   
CV Portfolio ini dibuat sebagai media untuk memperkenalkan diri, latar belakang pendidikan, pengalaman, serta keterampilan yang saya miliki. Dengan adanya CV ini, saya berharap dapat memberikan gambaran singkat mengenai potensi dan kompetensi saya, baik di bidang akademik, olahraga, maupun pengembangan teknologi.

2. PEMBAHASAN

<img width="1229" height="776" alt="Screenshot 2025-10-01 223547" src="https://github.com/user-attachments/assets/b585a99c-d672-46a2-b00a-50d582b516ab" />


Kode HTML pada gambar tersebut merupakan bagian awal dari sebuah halaman CV Portfolio. Pada bagian <head>, terdapat deklarasi meta charset="UTF-8" untuk mendukung karakter Unicode, meta name="viewport"... agar tampilan responsif di berbagai perangkat, title untuk judul halaman di browser, serta link yang menghubungkan file eksternal style.css untuk mengatur tampilan. Di dalam body, struktur dimulai dengan elemen header yang berisi nama lengkap "Gede Troy Wiswama Bhareswara" dalam tag h1 dan deskripsi singkat "Student | Athlete | Programmer" menggunakan tag p dengan class subtitle. Selanjutnya terdapat nav yang berisi beberapa tautan a menuju bagian-bagian tertentu di halaman dengan memanfaatkan atribut href yang mengarah ke id masing-masing section seperti #about, #skills, #experience, #education, #projects, dan #contact.

Masuk ke bagian konten utama main, terdapat section pertama dengan id="about" yang berfungsi menampilkan deskripsi diri, ditulis dalam tag p. Section berikutnya dengan id="skills" menampilkan daftar keterampilan menggunakan tag ul (unordered list) dan li (list item), yang diisi dengan skill seperti HTML, CSS, dan UI/UX Design. Struktur ini dibuat dengan rapi menggunakan kombinasi tag section, id, dan class agar mudah distyling dengan CSS serta memudahkan navigasi ke tiap bagian portofolio.


<img width="1033" height="853" alt="Screenshot 2025-10-01 223613" src="https://github.com/user-attachments/assets/9816d565-ec74-4e67-b6bd-509a1375e042" />

Struktur utama dibagi menggunakan tag section yang berfungsi untuk memisahkan tiap bagian seperti Experience, Education, Projects, dan Contact. Di dalam setiap section, judul ditandai dengan tag h2 sebagai heading utama, sementara h3 digunakan untuk subjudul seperti nama sekolah atau posisi pekerjaan. Informasi tambahan, misalnya tahun atau keterangan, dituliskan dalam tag p (paragraf), dengan class period untuk memudahkan pengaturan gaya tulisan melalui CSS. Pada bagian prestasi atau daftar pencapaian, digunakan kombinasi tag ul (unordered list) dan li (list item) agar isi tampil dalam bentuk poin. Untuk menambahkan tautan ke sumber eksternal seperti GitHub atau Instagram, digunakan tag a (anchor) dengan atribut href yang menentukan alamat link dan target="_blank" agar link terbuka di tab baru. Selain itu, atribut id dipakai untuk memberikan identitas unik pada suatu section sehingga bisa dijadikan target navigasi, sedangkan class berfungsi untuk mengelompokkan elemen agar bisa diberi style yang sama melalui CSS. Keseluruhan konten utama ditempatkan dalam tag main, sementara bagian paling bawah menggunakan <footer> untuk menampilkan informasi hak cipta. Dengan kombinasi syntax tersebut, halaman CV menjadi terstruktur, rapi, dan mudah dinavigasi.


TAMPILAN WEBSITE
<img width="1916" height="810" alt="Screenshot 2025-10-01 225317" src="https://github.com/user-attachments/assets/7618a094-3135-4c1c-9450-7f90f7c3edb1" />
<img width="1901" height="914" alt="Screenshot 2025-10-01 225324" src="https://github.com/user-attachments/assets/d4428930-8f68-4b61-9b3e-c842f84c5682" />
<img width="1909" height="712" alt="Screenshot 2025-10-01 225330" src="https://github.com/user-attachments/assets/c506b805-4737-4ae8-84b6-a05d067656c2" />


3. KESIMPULAN

Menurut saya kode HTML tersebut menyusun sebuah halaman CV Portfolio yang terstruktur dengan baik menggunakan elemen header, nav, main, dan footer. Setiap bagian penting seperti About Me, Skills, Experience, Education, Projects, dan Contact dipisahkan dengan tag section sehingga mudah dinavigasi dan diatur tampilannya menggunakan CSS. Struktur ini membuat CV lebih rapi, interaktif, serta mudah dipahami baik oleh pengguna maupun pengembang.


