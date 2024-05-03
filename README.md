# HTML
<b>HTML</b> atau kepanjangannya ialah <i>Hyper Text Markup Language</i> yang merupakan bahasa yang sering digunakan dalam membuat halaman website. HTML mendeskripsikan struktur dari web itu sendiri, apabila digambarkan seperti kita sedang 
membangun sebuah rumah maka HTML inilah yang akan menjadi desain dan pondasinya. HTML terdiri dari banyak elemen didalamnya dan elemen-elemen inilah yang nantinya akan menampilkan isi dari website yang kita buat. 
Setiap elemen memiliki labelnya tersendiri dan juga tag yang berbeda-beda, dan perlu diingat bahwa tag atau atribut pada HTML selalu di dalam tanda “< >” kemudian diakhiri dengan tanda “</ >” seperti yang ada di bawah ini :

<i>*gambar basic</i>
 
Diatas merupakan contoh dari sebuah pendeklarasian dari penggunaan HTML : 
<ul type="disc">
<li> <b>!DOCTYPE html</b> merupakan tag pendefinisian bahwa bahasa yang akan digunakan ialah HTML, sebenarnya hal ini tidak wajib dilakukan karena pada basic-nya file berjenis .html akan menggunakan html,
namun dengan tag ini maka HTML yang akan kita gunakan akan HTML versi yang paling baru saat ini, yakni versi 5. </li>
<li> <b>html lang=”en-US”</b> merupakan pendefinisian bahasa  dan negara yang digunakan, sebenarnya tidak terlalu berefek kepada web yang kita buat karena pada dasarnya web kita akan otomatis menggunakan bahasa Inggris. </li>
<li> <b>head</b> merupakan bagian kepala dari website, pada head ini, kita dapat memberikan berbagai macam tag di dalamnya seperti <head> seperti pada gambar diatas untuk memberi judul pada header website,
  selain itu kita juga dapat memasukkan style dari CSS dan script dari JavaScript nanti.</li>
<li> <b>body</b> merupakan bagian yang mencakup berbagai tag yang akan kita buat nanti pada website, dan juga seluruh isi website akan dimulai dari tag ini.</li>
</ul>

Di dalam body HTML, terdapat berbagai tag yang tersedia yang dapat membantu dalam pembuatan website, diantaranya ialah seperti yang akan disebutkan dibawah ini.

# Header dan Paragraf

Header dan paragraf dalam HTML merupakan elemen yang sangat sering dijumpai pada setiap web, pasalnya adalah karena elemen inilah yang menyusun suatu web, dalam membuat paragraf
atau header, terdapat beberapa tag yang berguna sebagai berikut :

<i>*gambar header</i>
	
<ul type="disc">
<li>tag <b>h1</b> biasa digunakan untuk membuat header atau judul pada website, tag ini dapat divariasikan dari h1 sampai dengan h6,
ukuran text akan semakin kecil ketika menggunakan angka yang lebih besar misalnya seperti tag h6 yang merupakan ukuran terkecil.</li>
<li>tag <b>p</b> merupakan tag yang menandakan bahwa elemen yang ada didalamnya merupakan sebuah paragraf.</li>
<li>tag <b>br</b> digunakan untuk membuat baris baru pada web.</li>
<li>tag <b>pre</b> merupakan tag yang digunakan untuk membuat paragraf atau kalimat yang nantinya akan secara otomatis ter-justify dan di-setting secara otomatis.</li>
</ul>

# Formatting pada HTML
	
Formatting pada HTML digunakan untuk menandai atau memberi tekanan lebih pada teks yang diinginkan. Alasan untuk ditekankan adalah agar pembaca atau pengguna web akan menaruh perhatian mereka kepada teks yang kita tekankan.
Berikut terdapat beberapa formatting yang ada pada HTML. Penggunaan formatting dapat dilakukan dengan mengapit kalimat atau kata yang ingin ditekankan dengan tag yang ingin digunakan.

<i>*gambar format</i>

<ul type="disc">
<li>tag <b>b</b> dan <b>strong</b> berguna untuk membuat teks seperti menjadi lebih tebal seperti yang ada pada gambar diatas.</li>
<li>tag <b>i</b> dan <b>em</b> atau <b>emphasized</b> akan membuat teks menjadi ditampilkan miring.</li>
<li>tag <b>small</b> akan membuat ukuran teks diperkecil.</li>
<li>tag <b>mark</b> akan membuat kata atau kalimat yang diapit menjadi ditandai.</li>
<li>tag <b>delete</b> atau <b>del</b> untuk membuat teks seakan tercoreng.</li>
<li>tag <b>insert</b> atau <b>ins</b> akan memberi garis dibawah teks.</li>
<li>tag <b>sub</b> akan mengangkat sedikit teks dan tag <b>sup</b> melakukan sebaliknya.</li>
</ul>

# Quotation dan Citation pada HTML

Didalam HTML, terdapat juga tag untuk membuat quote dan sitasi atau juga yang biasa disebut dengan kutipan. Kutipan dapat digunakan untuk memberitahukan bahwa suatu tulisan
diambil dari sumber lain.

<i>*gambar citation</i>

<ul type="disc">
  <li> tag <b>bockquote</b> memnbuat teks yang kita apit terdefinisikan bahwa itu dikutip dari sumber lain.</li>
  <li> tag <b>q</b> akan membuat teks yang diapit akan berada didalam tanda " ".</li>
  <li> tag <b>abbr</b> dapat digunakan untuk menyatakan singkatan.</li> 
  <li> tag <b>address</b> dapat digunakan untuk menandakan sebuah alamat, teks yang berada di dalam tag ini
	biasanya akan ditampilkan secara miring.</li>
 <li> tag <b>cite</b> dapat digunakan untuk mendefinisikan judul dari sebuah karya misalnya adalah buku, puisi dan lain
 sebagainya.</li>
</ul>

# Link dan Image pada HTML

Ketika kita membuat website, pastinya website kita akan terasa monoton apabila tidak menyertakan gambar atau
komponen lain, dan juga komponen-komponen tersebut mempunyai fungsi-fungsi yang berbeda.
<ol type="square">
<li>Link pada HTML dapat digunakan untuk menghubungkan antara halaman web yang kita buat dengan halaman web yang lain, web tersebut dapat web kita yang lain atau web milik orang lain.</li>
<ul type="a">
<li>Menggunakan link untuk menyambungkan website kita dengan yang lain, dapat dilakukan dengan menggunakan tag <b>a href</b>, dengan menempatkan link yang kita tuju
pada tag tersebut, maka ketika pada output, value yang kita masukkan akan dapat ditekan dan akan menuju ke web yang kita inginkan. </li>
<i>*gambar link</i>
<li>Ketika menggunakan link untuk pergi menuju ke web lain, terdapat pula modifikasi yang dpaat dilakukan seperti target, yang terdiri dari : </li>
<ol>
	<li><b>_blank</b> akan membuat halaman web yang dituju setelah kita menekan link a href ditampilkan pada tab baru.</li>
	<li><b>_self</b> merupakan setelan default dari target, dimana akan menampilkan halaman pada tab yang sama.</li>
	<li><b>_parent</b> yang nantinya akan membuka halaman di frame parent.</li>
	<li><b>_blank</b> mirip seperti self, hanya saja ini akan membuka halaman dengan ukuran penuh dari tab.</li>
</ol>
<li>Link juga tidak hanya dapat ditampilkan dalam bentuk teks value polos, namun juga dapat menggunakan gambar atau tombol.</li>
<ol> 
	<li>apabila ingin menggunakan gambar, maka akan mirip dengan ketika kita menggunakan teks, namun value dari link tersebut kita ganti menjadi menggunakan img,
		penjelasan bagaimana memasukkan gambar ke html akan ada dibawah ini.</li>
	<i>*gambar link img</i>
  	<li>apabila ingin menggunakan tombol, kita dapat menggunakan <b>event</b> (bagian dari JavaScript) yang bisa digunakan pada button, misalnya ialah <b>onclick</b></li>
	<i>*gambar link button</i>
</ol></ul>
<li>Image pada HTML </li>
</ol>
