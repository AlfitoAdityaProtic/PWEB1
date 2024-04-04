# Laporan Penjelasan Tugas 1 Praktikum WEB 1
## semua output di bawah ini ada semua kodenya di folder html, css, js sesuai judul yang sudah saya berikan
1. HTML <br>
HTML adalah bahasa markup standar untuk membuat halaman Web.<br>
disini saya akan menampilkan beberapa contoh dari penggunaan HTML yang sering di gunakan dalam dunia pemrograman. silahkan disimak baik-baik.<br>

   a. Headings<br>
     Judul HTML ditentukan dengan tag dari h1 sampai ke h6.
     h1: mendefinisikan judul yang paling penting. h6 : mendefinisikan judul yang paling tidak penting.
     semakin banyak angkanya semakin kecil juga ukuran hurufnya, artinya h1 memiliki tulisan karakter terbesar sedangkan h6 memiliki ukuran karakter terkecil.
     h1 sebaiknya digunakan untuk judul utama, diikuti h2, lalu judul yang kurang penting h3, dan seterusnya.
   ![alt text](https://github.com/AlfitoAdityaProtic/PWEB1/blob/main/image/1.%20headings.png?raw=true)<br>
   <br><br>
   b. Paragraphs<br>
      saat menulis sebuah paragraf yang panjang, di html menyediakan tag khusus untuk paragraf yaitu dengan menggunakan tag p lalu teks bisa di tuliskan dalam tag           tersebut.
      kita tidak dapat memastikan bagaimana HTML akan ditampilkan.
      Layar besar atau kecil, dan jendela yang diubah ukurannya akan memberikan hasil yang berbeda.
      Dengan HTML, Anda tidak dapat mengubah tampilan dengan menambahkan spasi atau baris tambahan pada kode HTML Anda.
      Browser akan secara otomatis menghapus spasi dan baris tambahan saat halaman ditampilkan.
      lalu di bagian paling bawah, saya menggunakan tag pre pada html sehingga teks yang berada di dalam tag pre menjadi menjorok ke dalam seperti pada gambar di            paling bawah ini.<br>
      ![alt text](https://github.com/AlfitoAdityaProtic/PWEB1/blob/main/image/2.%20paragraphs.png?raw=true)<br><br>
   c. Text Formatting<br>
      dalam menulis teks tentu kita terkadang ingin membuatnya menjadi tebal, miring atau ada garis bawahnya, nah di html  pun menyediakan fitur tersebut juga, bisa         dilihat dengan hasil dibawah ini yang dituliskan menggunakan code html :<br>
      ![alt text](https://github.com/AlfitoAdityaProtic/PWEB1/blob/main/image/3.%20teks%20formatting.png?raw=true)<br>
      teks formatting ada banyak, contoh disini sangat lengkap untuk bisa diketahui oleh teman-teman sekalian, diatas menggunakan tag bold, italic, strong (sama             seperti bold hanya bedanya strong itu untuk menekankan bahwa tulisan itu penting), small, mark (menandai sebuah kata dengan memberikan background berwarna       
      kuning), insert, delete, subscripted (membuat tulisan menjadi kecil di bawah), superscripted (membuat tulisan kecil menjadi kecil di atas seperti bilangan             berpangkat).<br><br>
   d. Quotation<br>
      Dalam bab ini kita akan membahas elemen blockquote, q, abbr, address, cite, dan bdo pada HTML.<br>
      - blockquote mendefinisikan bagian yang dikutip dari sumber lain. Browser biasanya membuat indentasi blockquote elemen.
      - q sendiri mendefinisikan kutipan singkat. Browser biasanya menyisipkan tanda kutip di sekitar kata yang ingin di kutip.
      - abbr mendefinisikan singkatan atau akronim, seperti "HTML", "CSS", "Mr.", "Dr.", "ASAP", "ATM".
      - address mendefinisikan informasi kontak penulis/pemilik dokumen atau artikel. biasanya browser akan otomatis menampilkan teks dalam <i>huruf miring</i>.
      - cite mendefinisikan judul suatu karya kreatif (misalnya buku, puisi, lagu, film, lukisan, patung, dll.). Teks dalam cite elemen biasanya ditampilkan dalam             huruf miring.
      - bdo adalah singkatan dari Bi-Directional Override. Tag HTML bdo digunakan untuk mengganti arah teks.<br>
         ![alt text](https://github.com/AlfitoAdityaProtic/PWEB1/blob/main/image/4.%20quotation.png?raw=true)<br><br>
   e. Table <br>
      <b>Sel Tabel</b><br>
      Tabel dalam HTML terdiri dari sel-sel tabel di dalam baris dan kolom.
      Tabel HTML memungkinkan pengembang web untuk mengatur data ke dalam baris dan kolom.
      Setiap sel tabel ditentukan oleh tag td.
      Segala sesuatu di antara tag td merupakan konten sel tabel.<br>
      <b>Baris Tabel</b><br>
      Setiap baris tabel dimulai dengan tag tr.
      <b>Header Tabel</b><br>
      Terkadang Anda ingin sel Anda menjadi sel header tabel. Dalam kasus tersebut, gunakan tag th alih-alih tag td.<br>
      ![alt text](https://github.com/AlfitoAdityaProtic/PWEB1/blob/main/image/5.%20Table.png?raw=true).<br><br>
   f. List<br>
      Daftar HTML memungkinkan pengembang web mengelompokkan sekumpulan item terkait dalam daftar.
      <b>Unorder list</b><br>
      Daftar tidak berurutan dimulai dengan tag ul. Setiap item daftar dimulai dengan tag li.
      Item daftar akan ditandai dengan poin (lingkaran hitam kecil) secara default.
      <b>Order List</b><br>
      Daftar yang diurutkan dimulai dengan tag ol. Setiap item daftar dimulai dengan tag li.
      Item daftar akan ditandai dengan angka secara default.
      di order list sendiri tidak hanya angka, melainkan bisa bentuk A, a, I atau i. semuanya bisa di setting menggunakan type lalu masukan tipe yang ingin kita             gunakan. untuk penerapannya bisa dilihat di code HTML saya di folder HTML dengan nama list.html<br>
      ![alt text](https://github.com/AlfitoAdityaProtic/PWEB1/blob/main/image/6.%20list.png?raw=true)<br><br>
   g. Link <br>
      Tautan HTML adalah hyperlink. Anda dapat mengeklik tautan dan melompat ke dokumen lain. Saat Anda menggerakkan mouse ke atas link, panah mouse akan berubah            menjadi tangan kecil. Atribut yang paling penting dari suatu tag a adalah href atribut, yang menunjukkan tujuan tautan. Teks tautan adalah bagian yang akan            terlihat oleh pembaca. Mengklik teks tautan, akan mengirim pembaca ke alamat URL yang ditentukan.<br>
      ![alt text](https://github.com/AlfitoAdityaProtic/PWEB1/blob/main/image/7.%20link.png?raw=true)<br><br><hr>
2. CSS<br>
   CSS adalah bahasa yang kami gunakan untuk menata gaya dokumen HTML. CSS menjelaskan bagaimana elemen HTML harus ditampilkan.<br>
   a. Table Hover<br>
      Gunakan :hover pemilih pada tr untuk menyorot baris tabel dengan mengarahkan mouse, jadi saat kita mengarahkan mouse ke salah 1 baris di tabel maka baris              tersebut akan memberikan efek yang sudah diberikan, contohnya pada gambar dibawah ini baris akan menyala berwarna chocolate jika di sorot oleh mouse.<br>
      ![alt text](https://github.com/AlfitoAdityaProtic/PWEB1/blob/main/image/8.%20CSS-TAble%20Hover.png?raw=true)<br>
   b. Box Model<br>
      Dalam CSS, istilah "Box Model" digunakan ketika berbicara tentang desain dan tata letak. Box Model CSS pada dasarnya adalah sebuah kotak yang membungkus               setiap elemen HTML. Terdiri dari: konten, padding, batas dan margin.<br>
      ![alt text](https://github.com/AlfitoAdityaProtic/PWEB1/blob/main/image/9.%20CSS-%20Box%20Model.png?raw=true)<br>
   c. Borders<br>
      Properti borders CSS memungkinkan Anda menentukan gaya, lebar, dan warna batas elemen.
      Properti border-style menentukan jenis batas yang akan ditampilkan.
      Nilai-nilai berikut diperbolehkan:
      - dotted Mendefinisikan batas titik-titik
      - dashed Mendefinisikan batas putus-putus
      - solid Mendefinisikan batas yang solid
      - double Mendefinisikan perbatasan ganda
      - groove Mendefinisikan batas beralur 3D. Efeknya bergantung pada nilai warna batas
      - ridge Mendefinisikan batas bergerigi 3D. Efeknya bergantung pada nilai warna batas
      - inset Mendefinisikan batas sisipan 3D. Efeknya bergantung pada nilai warna batas
      - outset Mendefinisikan batas awal 3D. Efeknya bergantung pada nilai warna batas
      - none Tidak mendefinisikan batas
      - hidden Mendefinisikan perbatasan tersembunyi<br>
      Properti border-style dapat memiliki satu hingga empat nilai (untuk batas atas, batas kanan, batas bawah, dan batas kiri).<br>
      ![alt text](https://github.com/AlfitoAdityaProtic/PWEB1/blob/main/image/10.%20CSS-Borders.png?raw=true)<br><br>
   d. Transition<br>
      Transisi CSS memungkinkan Anda mengubah nilai properti dengan lancar, selama durasi tertentu.
      Arahkan mouse ke elemen di bawah ini untuk melihat efek transisi CSS.<br>
      ![alt text](https://github.com/AlfitoAdityaProtic/PWEB1/blob/main/image/11.%20Transition.png?raw=true)<br><br>
   e. Text Transform<br>
      Properti ini text-transform digunakan untuk menentukan huruf besar dan kecil dalam sebuah teks.
      Ini dapat digunakan untuk mengubah semuanya menjadi huruf besar atau kecil, atau menggunakan huruf besar pada huruf pertama setiap kata.<br>
      ![alt text](https://github.com/AlfitoAdityaProtic/PWEB1/blob/main/image/12.%20CSS-%20Text%20transform.png?raw=true)<br><br>
   f. Text-Indent<br>
      Properti text-indent menentukan indentasi baris pertama dalam blok teks.
      Catatan: Nilai negatif diperbolehkan. Baris pertama akan menjorok ke kiri jika nilainya negatif.<br>
      ![alt text](https://github.com/AlfitoAdityaProtic/PWEB1/blob/main/image/13.%20Text-Indent.png?raw=true)<br><br><hr>
3. JavaScript<br>
   a. Function <br>
      Ketika JavaScript mencapai sebuah returnpernyataan, fungsi tersebut akan berhenti dijalankan.
      Jika fungsi dipanggil dari sebuah pernyataan, JavaScript akan "kembali" untuk mengeksekusi kode setelah pernyataan yang dipanggil.
      Fungsi sering kali menghitung nilai kembalian . Nilai yang dikembalikan "dikembalikan" ke "pemanggil".
      contoh dibawah ini menggunakan function yang bernama myfunction() dan melakukan penghitungan di dalam function tersebut sehingga menghasilkan output bernilai         12. untuk lebih detailnya disarankan membuka modul bernama js-function.html pada folder Javascript.<br>
      ![alt text](https://github.com/AlfitoAdityaProtic/PWEB1/blob/main/image/14.%20JS-%20Function.png?raw=true)<br><br>
   b. Aritmatika <br>
      Operator aritmatika melakukan aritmatika pada bilangan (literal atau variabel). disini saya hanya mengambil contoh dari w3schools.com yang mana dalam contoh          aritmatika nya bertuliskan (100+50)*3 pada tag script javascript yang nanti disambungkan ke id dari html sehingga menghasilkan output sebesar 450 di layar            browser.<br>
      ![alt text](https://github.com/AlfitoAdityaProtic/PWEB1/blob/main/image/15.%20JS-Aritmatika.png?raw=true)<br><br>
   c. Alert<br>
      Metode alert() menampilkan kotak peringatan dengan pesan dan tombol OK.
      Metode alert() digunakan ketika kita ingin informasi sampai ke pengguna.
      Kotak peringatan mengalihkan fokus dari jendela saat ini, dan memaksa pengguna untuk membaca pesan.
      Jangan terlalu sering menggunakan metode ini. Ini mencegah pengguna mengakses bagian lain halaman hingga kotak peringatan ditutup.<br>
      ![alt text](https://github.com/AlfitoAdityaProtic/PWEB1/blob/main/image/16.%20JS-Alert.png?raw=true)<br><br>
   d. Add Event Listener<br>
      Metode addEventListener() melampirkan event handler ke dokumen. dimana saat kita meng klik sebuah button atau elemen yang sudah dihubungkan ke sebuah function        maka akan menghasilkan sesuatu yang sesuai dengan isi dari function yang sudah kita hubungkan. untuk detailnya disarankan membuka code yang sudah saya buka           berjudul js-EventListener.html pada folder Javascript.<br>
      ![alt text](https://github.com/AlfitoAdityaProtic/PWEB1/blob/main/image/17.%20JS-EventListener.png?raw=true)<br>
      untuk contoh di atas menggunakan addeventlistener dimana jika kita meng klik button try it maka akan menjalankan function bernama displayDate() yang berisikan        tanggal pada hari ini beserta jamnya.<br><br>

untuk penggunaan dom sendiri hampir semua contoh js yang saya cantumkan menggunakan dom sebagai penyelesaian masalahnya, jika ingin tau lebih detail mengenai dom di halaman github saya, disarankan membuka folder bernama Javascript atau bisa juga membuka file challange yang sudah saya lampirkan di atas.<br><br><hr>

   
      -----Demikian Laporan Tugas 1 Praktikum WEB 1 yang di ampu oleh Bapak Abdau, Terima Kasih dan Semoga Repositori ini bisa bermanfaat untuk para pembaca. Terima Kasih-----
   
