# Writing & Presentation Module 1 - 6

## 1. Module-1 Unix Command Line

### **Command Line**
*Command Line* yang dimaksud disini adalah Command Line Interface (CLI) yang kita kenal ketika membuka sebuah command prompt pada *Operating System* Windows

![Gambar CLI](./1%20Unix%20Command%20Line/Gambar%20CLI.png)
*Gambar 1. CLI di Command Prompt*

Ketika mengetikan sebuah perintah dalam CLI tersebut, ada yang namanya Shell yang berbasis teks. Shell inilah program yang menerima perintah tersebut ke *system* untuk dieksekusi

Selain CLI, terdapat juga tampilan yang sering kita lihat ketika membuka komputer yang dinamakan Graphical User Interface (GUI) 

![Gambar GUI](./1%20Unix%20Command%20Line/Gambar%20GUI.png)
*Gambar 2. GUI di Windows Folder*


### **Filesystem Structure**

Yang dimaksud dari struktur tersebut adalah bagaimana sistem kita dalam mengatur file yang ada dalam *folder* kita seperti file untuk *game*, video, gambar, dan sebagainya itu tersimpan dalam sebuah sistem kompleks ini. Dalam operasi sistem Windows kita dapat melihatnya menggunakan Command di terminal menggunakan `tree` untuk lebih jelasnya dapat dilihat pada gambar 3.

![Gambar Tree](./1%20Unix%20Command%20Line/Gambar%20Tree.png)
*Gambar 3. Struktur File*

Note: Warna **Merah** = *Root Folder*, Warna **Hijau** = *Directory* Tujuan Akhir


### **Command in Command Prompt**

**- pwd**

Perintah ini digunakan untuk melihat *directory path* yang sedang kita tempati

![Gambar pwd](./1%20Unix%20Command%20Line/Gambar%20PWD.png)
*Gambar 4. Command pwd*

**- ls**

Perintah ini digunakan untuk melihat isi dari file file apa saja yang ada pada direktori kita tempati

![Gambar ls](./1%20Unix%20Command%20Line/Gambar%20ls.png)
*Gambar 5. Command ls*

**- cd \<tujuan direktori>**

Perintah ini digunakan untuk masuk ke dalam *folder* lain atau sebuah file yang dituju

![Gambar cd](./1%20Unix%20Command%20Line/Gambar%20Cd.png)
*Gambar 6. Command cd*

**- cat \<Nama File>**

Perintah ini digunakan untuk melihat/membuka isi dari file yang dituju

![Gambar cat](./1%20Unix%20Command%20Line/Gambar%20Cat.png)
*Gambar 7. Command cat*

**- touch & mkdir**

Perintah dari touch digunakan untuk membuat file, sedangkan mkdir digunakan untuk membuat folder

![Gambar touch & mkdir](./1%20Unix%20Command%20Line/Gambar%20touch%20%26%20mkdir.png)
*Gambar 8. Command touch & mkdir*

**- cp \<Nama File> \<Direktori>**

Perintah ini digunakan untuk menyalin suatu file atau sebuah folder ke direktori lain

![Gambar cp](./1%20Unix%20Command%20Line/Gambar%20Cp.png)
*Gambar 9. Command cp*

**- mv \<Nama File> \<Direktori>**

Perintah ini digunakan untuk memindahkan file dan folder ke direktori lain, serta dapat digunakan untuk merubah nama dari file atau folder

![Gambar mv](./1%20Unix%20Command%20Line/Gambar%20Mv.png)
*Gambar 10. Command mv*

**-rm \<Nama File>**

Perintah ini digunakan untuk menghapus sebuah file ataupun folder

![Gambar rm](./1%20Unix%20Command%20Line/Gambar%20rm.png)
*Gambar 11. Command rm*


---

## 2. Module-2 Git & GitHub Dasar

### **Pengertian**

Pertama tama, Git dan GitHub adalah dua hal yang berbeda. Git itu sendiri adalah *tools* yang dapat kita gunakan untuk memodifikasi file dan folder dari project kita. Sedangkan GitHub adalah tempat untuk menyimpan project kita secara online atau yang disebut *repository* online.

Kenapa penting menggunakan Git dan juga GitHub? karena pada dunia industri sekarang yang membuat suatu program perlu untuk **berkolaborasi** dengan tim pengembang itu sendiri dan juga tim lainnya yang menguji sistem yang sudah dibuat. Selain itu, keuntungan menggunakan kedua hal tersebut dapat membuat satu program secara bersamaan tanpa perlu menunggu satu dengan yang lainnya selesai terlebih dahulu


### **Cara Kerja**

Bagaimana penggunaan dari Git dan GitHub? Nah, untuk alur *simple* nya dapat dilihat pada gambar 12.

![Gambar Alur Git & GitHub](./2%20Git%20%26%20GitHub%20Dasar/Gambar%20Alur%20Git%20%26%20GitHub.png)
*Gambar 12. Alur Kerja Git & GitHub*

Dapat dilihat dari gambar, *project* yang kita buat diatur terlebih dahulu pada Git *Tools*. Kemudian, Git akan melacak berbagai modifikasi yang kita buat selama kita menambah atau menghapus dari file file *project* kita. Setelah, semua *project* sudah *complete development*, yang perlu dilakukan adalah *setup* di Git untuk mengupload project yang dibuat ke *repository* GitHub

### **Penggunaan Git**

Dalam menggunakan Git kita dapat menggunakan *tools* "Git Bash" untuk versi Windows

![Gambar Git Awal](./2%20Git%20%26%20GitHub%20Dasar/Gambar%20Git%20Interface.png)
*Gambar 13. Tampilan Git Bash*


Selanjutnya, pada *project* masing masing silahkan jalankan perintah `git init` apabila belum ada git yang terinisiasi pada *project*

![Gambar Git Init](./2%20Git%20%26%20GitHub%20Dasar/Gambar%20Git%20Init.png)
*Gambar 14. Git Init & Git Status*

Pada Gambar 14 bisa dilihat setelah kita melakukan inisialisasi, maka dapat terlihat beberapa file dan *folder* yang belum ditambahkan ke dalam *repository* lokal sementara

Untuk menambahkan project kita ke dalam *staging* sementara itu dapat menjalankan perintah `git add .` yang akan secara otomatis menambahkan file dan *folder* ke dalam tahapan *staging* untuk persiapan *repository* sementara

![Gambar Git Add](./2%20Git%20%26%20GitHub%20Dasar/Gambar%20Add.png)
*Gambar 15. Git Add*

Pada gambar 15 sudah ditambahkan berbagai file yang sudah dibuat menjadi *staged* . Langkah selanjutnya menjalankan `Git Commit -m "Deskripsi Versi"` untuk melabeli *stage* tersebut menjadi *repository* sementara ini dan siap untuk ditembak ke GitHub yang sudah tersedia

![Gambar Git Commit](./2%20Git%20%26%20GitHub%20Dasar/Gambar%20Git%20Commit.png)
*Gambar 16. Git Commit*

Nah, dengan ini penggunaan git sudah siap untuk diluncurkan secara online. Sebelum masuk ke dalam GitHub, berikut adalah gambaran besar dalam melakukan beberapa perintah sebelumnya

![Gambar Alur Git](./2%20Git%20%26%20GitHub%20Dasar/Gambar%20Alur%20Git.png)
*Gambar 17. Alur Git*


### **GitHub**

Pada website [github.com](https://www.github.com) disinilah kita akan menyimpan *repository* secara online. Yang diperlukan adalah membuat akun atau masuk untuk dapat membuat *repository* baru

![Gambar Membuat Repository GitHub](./2%20Git%20%26%20GitHub%20Dasar/Gambar%20GitHub%20Create%20Repository.png)
*Gambar 18. Create Repository in GitHub*

Untuk Gambar 18 adalah repository yang akan dibuat

![Gambar Tampilan Repository GitHub](./2%20Git%20%26%20GitHub%20Dasar/Gambar%20GitHub%20Tampilan%20Repository.png)
*Gambar 19. Tampilan Repository GitHub*

Karena pada gambar 19 merupakan *repository* kosong kita dapat mengisinya dengan *project* yang sebelumnya sudah di *commit*, dengan menghubungkan terlebih dahulu link yang ada pada *repository*. Pada kasus ini menggunakan link https://github.com/Erikherl/skilvulWriting.git 

![Gambar Koneksi ke Repository](./2%20Git%20%26%20GitHub%20Dasar/Gambar%20Git%20Remote.png)
*Gambar 20. Git Remote*

Pada gambar 20 kita sudah berhasil membuat jembatan untuk menyambungkan dari komputer lokal ke *repository* GitHub. Selanjutnya kita dapat langsung *upload* dengan perintah `git push -u origin`

![Gambar GitHub Complete](./2%20Git%20%26%20GitHub%20Dasar/Gambar%20Github%20Complete.png)
*Gambar 21. Git berhasil terupload*


Terakhir, apabila kita ingin mengambil project pada *repository* tersebut, cukup jalankan perintah `git clone ` pada komputer lokal kita


---
## 3. Module-3 HTML

### **Pengertian**

HTML HpyerText Markup Language yang berfungsi untuk menampilkan dari sebuah *plain* teks menjadi tampilan *website*. Sehingga terkadang kita dapat melihat banyak orang yang dapat menuliskan website melalui notepad, tapi tidak dengan microsoft word karena aplikasi tersebut merupakan *rich* teks bukan untuk pembuatan HTML

HTML memiliki sifat statis yang artinya apa yang dituliskan dari diri kita akan muncul sebagaimana mestinya, tidak akan berubah dengan sendirinya seperti AI (Artifical Intelligence)

### **Persiapan**

Yang perlu dipersiapkan dapat menggunakan *tools* Visual Studio code sebagai teks *editor* dan Google Chrome untuk implementasi dari yang sudah dibuat

![Gambar Tools HTML](./3%20HTML/Gambar%20Tools%20HTML.png)
*Gambar 22. Google Chrome & Visual Studio Code*

Selanjutnya, di visual studio code dapat membuka sebuah folder kosongan dan membuat satu file "nama.html" selanjutnya dibuat menjadi seperti gambar 23

![Gambar Dasar HTML](./3%20HTML/Gambar%20Dasar%20Struktur%20HTML.png)
*Gambar 23. Struktur Dasar HTML*

Pada Gambar 23 adalah sebuah dasar untuk membuat file berupa html. Di visual studio code sudah disediakan dengan cara ketik "htm" dan akan muncul beberapa pilihan seperti pada gambar 23. Kemudian, pilih yang "html:5" dan akan terbentuk seperti pada baris 1-15

![Gambar Jadi HTML](./3%20HTML/Gambar%20Tampilan%20Jadi%20HTML.png)
*Gambar 24. Tampilan HTML jadi*

Jika dilihat gambar 24 adalah hasil jadi yang sudah kita buat. Nah, untuk melihatnya cukup mudah tinggal buka saja file yang sudah dibuat dan akan muncul pada browser. Sebenarnya ada cara lain untuk memunculkan HTML yang sudah dibuat.

Kita dapat memanfaatkan ekstension dari Visual Studio Code, nama ekstension untuk shortcut dari yang sebelumnya adalah "Live Server". Ekstension ini dapat memudahkan kita tanpa perlu membuka folder dan menjalankan file html

![Gambar Ekstension Live Server](./3%20HTML/Gambar%20Ekstension%20Live%20Server.png)
*Gambar 25. Ekstension Live Server*

Keuntungan dari Gambar 25 adalah dapat menampilkan secara langsung HTML yang sudah kita modifikasi tanpa perlu refresh pada website


### **Penggunaan tag HTML**

**- \<div>**

Tag ini sangat sering digunakan untuk memisahkan konten secara besar (contoh: pemisah isi bagian promo, isi bagian partner, dll) ataupun konten kecil (contoh: pemisah untuk konten khusus judul, konten khusus paragraf)

![Gambar tag \<div>](./3%20HTML/Gambar%20Tag%20Div.png)
*Gambar 26. \<div> tag*

**- \<a>**

Tag ini digunakan ketika membuat sebuah teks yang isinya sebuah link ke arah halaman lain, link ke arah luar halaman, ataupun mengarah ke salah satu tag lainnya. Tag ini sangat berguna dalam penggunaan HTML dan DOM

![Gambar tag \<a>](./3%20HTML/Gambar%20Tag%20a.png)
*Gambar 27. \<a> tag*

**- \<h1> & \<p>**

Tag ini digunakan untuk membuat sebuah teks dalam website. Untuk \<h1> merupakan judul dan beberapa tag sampai dengan \<h6> merupakan sub judul. Sedangkan \<p> adalah paragraf biasa

![Gambar tag \<p>](./3%20HTML/Gambar%20tag%20h1%20%26%20p.png)
*Gambar 28. \<h1> & \<p> tag*

**- \<ul> atau \<ol>**

Tag ini merupakan untuk sebuah list seperti bullet, strip, ataupun sebuah icon untuk tag \<ul>, sedangkan \<ol> untuk sebuah list yang bisa terurut menggunakan angka, romawi

![Gambar tag \<ul>](./3%20HTML/Gambar%20Tag%20ul%20%26%20ol.png)
*Gambar 29. \<ul> atau \<ol> tag*

**- \<img>**

Tag ini digunakan khusus untuk memunculkan gambar dari komputer kita ataupun dari browser, dengan menggunakan atribut `src`

![Gambar tag \<img>](./3%20HTML/Gambar%20Tag%20image.png)
*Gambar 30. \<img> tag*

### Semantic HTML

Semantic HTML adalah menggunakan setiap tag-nya sesuai dengan posisi dan kegunaanya. Contohnya pada bagian paling atas website biasanya kita sebut navbar. Nah, apabil kita menerapkan tag sebelumnya menggunakan `<div class="navbar">` daripada seperti itu lebih baik menggunakan `<nav>` secara langsung

![Gambar sebelum semantic](./3%20HTML/Gambar%20Sebelum%20Semantic.png)
*Gambar 31. Sebelum Semantic HTML*

![Gambar setelah semantic](./3%20HTML/Gambar%20Sesudah%20Semantic%20HTML.png)
*Gambar 32. Sesudah Semantic HTML*


### Deploying Netlify

Sesudah memodifikasi file HTML, kita perlu juga untuk menaruh website kita untuk dapat dipajang juga. Nah, pada kelas ini akan menggunakan Netlify sebagai wadah tersebut

![Gambar Netlify Import](./3%20HTML/Gambar%20Netlify%20Import%20Git.png)
*Gambar 33. Netlify Import*

Pada gambar 33 kita perlu import terlebih dahulu *project* yang ada pada *repository* bisa dari GitHub ataupun *repository* lainnya. Untuk saat ini karena sudah ada *project* yang sudah di-*push* dalam *repository* GitHub 

![Gambar Netlify Install](./3%20HTML/Gambar%20Netlify%20Install.png)
*Gambar 34. Netlify Install*

Setelah itu pada gambar 34, HTML kita sudah terinstall dan dapat langsung deploy saja seperti pada gambar 35

![Gambar Nelify Deploy Setup](./3%20HTML/Gambar%20Netlify%20Deploy%20Setup.png)
*Gambar 35. Netlify Deploy Setup*

Dan hasilnya dari deploy pada gambar 35 dapat dilihat di gambar 36

![Gambar Netlify Deploy Live](./3%20HTML/Gambar%20Netlify%20Deploy%20Live.png)
*Gambar 36. Netlify Deploy Live*


---
## 4. Module-4 CSS

### **Pengertian**

Cascading Style Sheets (CSS) merupakan plain teks sama seperti HTML, namun CSS berperan untuk mendesain halaman website menjadi lebih menarik, teratur dan bervariasi

Dalam penggunaannya, CSS seringkali digunakan untuk tata letak dalam sebuah website, penggunaan warna, dan juga kustomisasi beberapa *element* HTML. Oleh karena itu, disini kita akan mempelajari bagaimana CSS dapat diterapkan dari HTML yang sudah dibuat

### **Penerapan CSS ke dalam HTML**

Dalam penggunaan CSS dapat diterapkan menjadi 3 cara

1. Inline Style

    ![Gambar Inline Style](./4%20CSS/Gambar%20CSS%20Inline%20STyle.png)
*Gambar 37. Inline Style*

    Penggunaan ini adalah penggunaan *styling* langsung pada atribut HTML, *Styling* dengan cara ini sangat dihindarkan karena akan membuat HTML penuh

2. Tag Style

    ![Gambar Tag STyle](./4%20CSS/Gambar%20CSS%20Tag%20Style.png)
*Gambar 38. Tag Style*

    Penggunaan *styling* ini diletakkan pada tag \<head> dan dituliskan pada bagian tersebut

3. Eksternal Style

    ![Gambar External Style](./4%20CSS/Gambar%20CSS%20Eksternal%20Style.png)
*Gambar 39. External Style*

    Penggunaan ini adalah yang paling direkomendasikan ketika membuat *styling* pada HTML, karena akan lebih memudahkan dari sisi pembacaan dan juga *maintance* kodingan


### **Penggunaan**

Dalam *styling* ada beberapa cara juga untuk diaplikasikan ke HTML dengan atributnya ataupun *element*-nya

- Tag

    ![Gambar External Style](./4%20CSS/Gambar%20CSS%20Eksternal%20Style.png)
*Gambar 40. Tag Styling*

    Dengan tag dapat dituliskan langsung pada tag HTML-nya atau *element* contohnya tag \<div> menjadi `div {}`

- ID

    ![Gambar ID Styling](./4%20CSS/Gambar%20CSS%20ID%20Styling.png)
    *Gambar 41. ID Styling*

    Dengan menggunakan ID pada atribut HTML, dapat dituliskan seperti pada gambar, menggunakan ".namaID" dan dilanjutkan dengan *styling*

- Class

    ![Gambar Class Styling](./4%20CSS/Gambar%20CSS%20Class%20Styling.png)
    *Gambar 42. Class Styling*

    Menggunakan Class sama seperti ID, bedanya kalau Class menggunakan "#" sebagai awalan untuk *styling*

- Combination

    ![Gambar Combination Styling](./4%20CSS/Gambar%20CSS%20Combination%20Styling.png)
    *Gambar 43. Combination Styling*

    *Styling* gambar 43 merupakan *styling* yang menerapkan *parent* dan *child*. Jadi, *styling* bekerja seperti berikut, pada *parent* ID Content yang memiliki child dengan Class Container akan memiliki *styling* seperti yang ada pada gambar

    Nah, untuk yang Combination ini tidak serta merta hanya dapat digunakan untuk Class dan ID. Namun, untuk semua bentuk yang ada pada *styling* dapat diterapkan


Penerapan *styling* umumnya seputar pada warna, tata letak, ukuran, dan jarak. Berikut beberapa syntax yang sering digunakan ketika *styling*

<br>

**Margin**

![Gambar Styling Margin](./4%20CSS/Gambar%20CSS%20Margin%20Styling.png)
*Gambar 44. Styling Margin*

Penggunaan margin sering digunakan untuk mengatur jarak antara konten atau dengan pinggiran halaman


**Color**

![Gambar Styling Color](./4%20CSS/Gambar%20CSS%20Color%20Styling.png)
*Gambar 45. Styling Color*

Penggunaan warna sangat sering digunakan untuk mewarnai sebuah background ataupun sebuah tulisan. Dapat terlihat pada gambar 45 warna \<h1> berganti warna


**Position**

![Gambar Styling Position](./4%20CSS/Gambar%20CSS%20Position%20Styling.png)
*Gambar 46. Styling Position*

Penggunaan *position* sebenarnya adalah penggunaan flex untuk dapat membuat dalam satu baris dapat dimuat 2 element HTML

<br>

### **Responsive Web**
Ini biasanya digunakan untuk mendevelop sebuah tampilan untuk *mobile version*. Pada *styling* kita dapat menggunakan yang namanya media query

![Gambar Responsive Styling](./4%20CSS/Gambar%20CSS%20Responsive.png)
*Gambar 47. Responsive Styling*

Ini adalah sebuah trik apabila kita membuka website, dan mengecilkan ukurannya sampai ukuran tertentu (untuk styling ini apabila ukuran lebarnya 600px atau lebih kecil) akan memunculkan background berwarna biru muda seperti pada gambar 47

![Gambar not Responsive](./4%20CSS/Gambar%20CSS%20not%20Responsive.png)
*Gambar 48. No Longer Responsive*

Apabila dia diperbesar lebarnya, akan muncul seperti pada gambar 48, dimana akan kembali lagi warna background menjadi putih

Nah, inilah yang disebutkan sebagai responsive website, dimana ketika pengguna menggunakan Handphone mereka akan memunculkan tampilan yang berbeda

<br>

### **Flexbox**

Dalam *styling* terdapat letak posisi yang diinginkan. Nah, untuk memposisikannya dapat menggunakan yang namanya Flexbox

Pada sebelumnya juga pernah disebutkan pada gambar 46, dimana kita dapat mengatur flexbox dengan menggunakan styling dengan `display: flex` sebagai awalan

![Gambar Styling Flexbox](./4%20CSS/Gambar%20CSS%20Flexbox.png)
*Gambar 49. Styling Flexbox*

<br>

---


## 5. Module-5 Algorithm 

### **Pengertian**

Algoritma adalah suatu hal yang sering kita lakukan setiap hari. Mengenai urutan langkah yang masuk akal atau logis dan terurut

Contohnya ketika berangkat ke sekolah kita perlu untuk mandi terlebih dahulu, kemudian bersiap siap, pamit orang tua, dan berangkat

![Gambar Berangkat Sekolah](./5%20Algorithm/Gambar%20Algoritma%20Berangkat%20Sekolah.png)
*Gambar 50. Langkah-langkah berangkat sekolah*

Kenapa perlu kita mengetahui dari algoritma ini? Apabila dikaitkan dengan pemrograman, pasti kita pernah membuat suatu alur membuat program sederhana seperti membuat program yang dapat menghitung bangun luas. Pertama kali yang kita lakukan adalah membuat alur struktur bagaimana bangun luas dapat dihitung menggunakan beberapa *function*

Nah, inilah kenapa algoritma sangat penting, selain dapat membantu untuk menentukan alur, algoritma juga dapat sebagai pendamping untuk seluruh bahasa pemrograman


### **Penerapan**

Penerapan algoritma ada berbagai cara, salah satunya menggunakan bahasa pemrograman yang mudah kita pahami, yaitu pseudocode

Ambil contoh ada algoritma yang ingin buat berupa sebuah program yang dapat mencetak angka dari 1 sampai dengan 10

**Algoritma**
``` 
Program Looping 1 - 10

step 1: Memulai Looping
step 2: Dimulai dari angka 1
step 3: Cetak Angka
step 4: Lanjut ke angka selanjutnya
step 5: ulangi step 3 hingga angka mencapai 10
```

**Pseudocode**
```
Pseudocode Looping angka 1 - 10

SET i <- 1
WHILE i <= 10
    DISPLAY i
    SET i = 1 + 1
END
```

**Javascript**

![Gambar Javascript](./5%20Algorithm/Gambar%20Algoritma%20Javascript.png)
*Gambar 51. Kodingan Looping*

Jadi, begitu caranya menerapkan algoritma ke pseudocode dan dijadikan ke bahasa pemrograman yang ingin kita aplikasikan. Mungkin apabila algoritma kurang jelas atau masih sulit untuk dipahami dapat menggunakan beberapa alternatif seperti *flow chart*

![Gambar Looping Flowchart](./5%20Algorithm/Gambar%20Algoritma%20Looping.png)
*Gambar 52. Flowchart Looping*

<br>

---

## 6. Module-6 Javascript

### **Pengertian**

Javascript adalah bahasa satu satunya yang menggunakan bahasa pemrograman dari pembuatan website sebelumnya. Pada HTML dan CSS hanya berupa untuk tampilan, tidak adanya *syntax* yang menunjukkan sebuah perintah. Nah, pada Javascript inilah yang menjadi kunci utama dalam membuat sebuah website memiliki fungsi yang bervariasi

### **Penerapan**

Javascript dapat dilakukan pada browser kita, saat ini akan digunakan Google Chrome. Nah, beberapa *syntax* yang dapat digunakan ketika menggunakan Javascript adalah sebagai berikut

- alert

    ![Gambar Syntax Alert](./6%20Javascript/Gambar%20Javascript%20Syntax.png)
    *Gambar 53. Syntax Alert*

    Alert digunakan untuk memunculkan sebuah pesan atau sebuah *pop-up* untuk memberitahu sebuah pesan

- prompt

    ![Gambar Syntax Prompt](./6%20Javascript/Gambar%20Javascript%20Syntax2.png)
    *Gamber 54. Syntax Prompt*

    Prompt digunakan untuk memasukkan sebuah input yang nantinya dapat disimpan sebagi sebuah value

- confirm

    ![Gambar Syntax Confirm](./6%20Javascript/Gambar%20Javascript%20Syntax3.png)
    *Gambar 55. Syntax Confirm*

    Confirm digunakan untuk mengkonfirmasi sebuah pesan yang ingin dimunculkan


Tipe - tipe data Javascript

![Gambar Tipe Data Javascript](./6%20Javascript/Gambar%20Javascript%20Tipe%20Data.png)
*Gambar 56. Tipe Data Javascript*

Jadi, terdapat berbagai tipe data yang disediakan javascript, seperti number yang mencakup angka, dan desimal. Kemudian, string mencakup semua huruf yang diapit dengan tanda petik (""), ada juga object yang menampung berbagai tipe data. Selain itu, ada data yang sifatnya null yang artinya kosong atau tidak ada isinya. Ada boolean yang isi nilainya hanya true atau false. Sisanya adalah tipe data undefined, yang artinya nilai itu tidak terdefenisikan atau belum dideklarasikan


Terdapat juga bentuk operator dalam Javascript

![Gambar Operator](./6%20Javascript/Gambar%20Javascript%20Operator.png)
*Gambar 57. Operator*

Dapat dilihat dari gambar 57, operator ada banyak. 
- Untuk variabel Nama menggunakan operator *Assignment* yaitu "="
- Variabel Matematika menggunakan operator perhitungan atau *Mathematical Assignment*, yaitu "+" dan "%" 
- Hasil console log berupa boolean, dari operator tersebut menggunakan *Comparison*, yaitu "=="
- Pada Conditional terakhir menggunakan operator *Logical* operator, yaitu "&&"


### **Conditional**

*Conditional* merupakan suatu kondisi yang menyatakan sesuatu, biasanya ini adalah *statement* percabangan. Contohnya dapat kita lihat pada hasil dari sebuah nilai boolean, untuk pengecekan nilai tersebut maka diperlukan sebuah kondisi

Beberapa tipe dalam menentukan kondisi, sebagai berikut:

- If... Else...

    ![Gambar Statement If](./6%20Javascript/Gambar%20Javascript%20Conditional%20If.png)
    *Gambar 58. Conditional If*

    Contoh biasa dalam penerapan if akan dijalankan bila kondisi pertama benar, dan else akan dijalankan apabila kondisi yang pertama salah

    Alternatif lain dapat menggunakan else if... untuk kasus yang dapat dipastikan kondisinya

- Truthy and Falsy

    ![Gambar Statement Truthy](./6%20Javascript/Gambar%20Javascript%20Conditional%20Truthy.png)
    *Gambar 59. Conditional Truthy dan falsy*

    Gambar 59 menunjukkan Truthy yang artinya apapun variabel jika dia memiliki nilai, maka otomtasi dia akan bernilai true. Disini kata kuncinya adalah variabel memiliki sebuah nilai

- Switch Case

    ![Gambar Statement Switch](./6%20Javascript/Gambar%20Javascript%20Conditional%20Switch.png)
    *Gambar 60. Conditional Switch Case*

    Gambar 60 adalah switch, dimana setiap case yang diberikan perlu diberikan `break` dengan tujuan setelah kondisi tersebut berjalan, dia berhenti dari kondisi tersebut. Kemudian, terdapat `default` yang artinya apabila semua kondisi tidak terjalankan, maka default akan mengambil alih

- Ternary

    ![Gambar Statement Ternary](./6%20Javascript/Gambar%20Javascript%20Conditional%20Ternary.png)
    *Gambar 61. Ternary Condition*

    Gambar 61 menunjukkan sebuah *conditional* singkat dibandingkan menggunakan if... else..., disini pada kondisi setelah "?" yang artinya menanyakan apabila benar maka jalankan kondisi pertama, dan jika salah akan menjalankan kondisi selanjutnya yang dipisah dengan *syntax* ":"


### **Looping**

*Looping* digunakan untuk mengulang suatu kondisi hingga tercapai tujuannya. Ada beberapa cara untuk penggunaan *looping* pada Javascript.

- Manual Looping

    ![Gambar Looping Manual](./6%20Javascript/Gambar%20Javascript%20Looping%20Manual.png)
    *Gambar 62. Looping Manual*

    Sangat tidak disarankan karena membutuhkan banyak baris dan tidak efisien dalam penerapan secara langsung

- For Loop

    ![Gambar Looping For](./6%20Javascript/Gambar%20Javascript%20Looping%20For.png)
    *Gambar 63. Looping For*

    Untuk looping ini disarankan untuk yang diketahui berapa kali harus mengulang

- While Loop

    ![Gambar Looping While](./6%20Javascript/Gambar%20Javascript%20Looping%20While.png)
    *Gambar 64. Looping While*

    Looping ini digunakan untuk apabila kita tidak mengetahui berapa jumlah yang perlu diulang, anggap saja kita ingin menampilkan jumlah tamu yang mendaftar. Pastinya kita tidak tahu jumlah yang pasti berapa

- Do While

    Sama seperti gambar 64, namun dia lebih pada melakukan terlebih dahulu perintahnya, baru melakukan pengecekan apakah kondisi tersebut sudah memenuhi atau belum

- Nested Loop

    ![Gambar Nest Looping by Skilvul](./6%20Javascript/Gambar%20Javascript%20Looping%20Pinjem%20Nested.png)
    *Gambar 65. Nested Looping*

    Looping ini digunakan seminimal mungkin, karena looping seperti ini akan menimbulkan beberapa konflik apabila datanya terlalu banyak. Apalagi looping ini berjalan dalam satu kesatuan sehingga apabila ada satu data error, maka akan menimbulkan masalah seterusnya

