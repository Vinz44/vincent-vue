<template>
  <div class="hello">
    <div class="container-fluid p-5 bg-primary text-white text-center">
  <h1>HTML</h1>
  <p>Vincent (2024250011)</p> 
</div>

<div id="section1" class="container-fluid bg-success text-white" style="padding:100px 20px;">
  <h1>Apa Itu HTML</h1>
  <p>HTML adalah bahasa standar pemrogaman yang digunakan untuk membuat halaman website, yang diakses melalui internet. Singkatan dari "Hypertext Markup Language" atau "bahasa markup".</p>
</div>

<div id="section2" class="container-fluid bg-warning" style="padding:100px 20px;">
  <h1>Fungsi HTML</h1>
  <p> HTML digunakan untuk membuat dokumen elektronik (disebut halaman) yang ditampilkan di World Wide Web (www). Setiap halaman berisi serangkaian koneksi ke halaman lain yang disebut hyperlink. Setiap halaman web yang Anda lihat di Internet ditulis menggunakan satu versi kode HTML atau yang lain.</p>
  <p>1. Fungsi utama HTML, untuk membuat suatu halaman website yang bisa dibaca dan dipahami dengan lebih mudah. Seluruh laman website yang ada di internet, dibuat dengan HTML dan tak ada pengecualian.</p>
  <p>2. Menandai teks pada suatu laman. HTML ditulis pada suatu halaman dokumen dengan tag atau simbol tertentu. Simbol dan tag tersebut akan membuat tampilan teks menjadi tebal, miring, bergaris tebal dan sebagainya. Semisal jika membuat suatu teks menjadi teks miring atau italic, di laman HTML harus ditulis kode    ,   untuk teks tebal dan - - untuk teks bergaris bawah.</p>
</div>

<div id="section3" class="container-fluid bg-secondary text-white" style="padding:100px 20px;">
  <h1>Sejarah HTML</h1>
  <p>HTML pertama kali dikembangkan oleh Tim Berners-Lee dari organisasi European Organization for Nuclear Research (CERN) tahun 1990. Markup language atau HTML ini diciptakan oleh suatu perusahaan penjual perangkat keras dan lunak yakni IBM atau International Bussiness Machines.</P>
  <p>Sekitar era 1980an, IBM menciptakan sebuah bahasa yang menggabungkan tag atau simbol dengan teks dalam sebuah dokumen. Bahasa yang diciptakan oleh IBM ini dikenal dengan sebutan markup language atau Generalized markup language (GML).</P>
  <p>Kemudian rilis versi pertama HTML ditulis oleh Tim Berners-Lee pada 1993. Dikutip dari Washington.edu, sejak itu, mulai banyak versi HTML yang berbeda. Versi yang paling banyak digunakan sepanjang tahun 2000-an adalah HTML 4.01, yang menjadi standar resmi sejak bulan Desember 1999.</P>
</div>
<div class="container mt-3">
  <h2>Sumber : "https://www.merdeka.com/trending/pengertian-html-lengkap-dengan-fungsi-dan-sejarah-kemunculannya-kln.html"</h2>
  <p></p> 
  <span class="border border-primary"></span>
  <span class="border border-secondary"></span>
  <span class="border border-success"></span>
  <span class="border border-danger"></span>
  <span class="border border-warning"></span>
  <span class="border border-info"></span>
  <span class="border border-light"></span>
  <span class="border border-dark"></span>
  <span class="border border-white"></span>

  <div class="container mt-3">
  <h2></h2>
  <p></p>                  
  <ul class="pagination">
    <li class="page-item"><a class="page-link" href="#">Previous</a></li>
    <li class="page-item"><a class="page-link" href="#">1</a></li>
    <li class="page-item"><a class="page-link" href="#">2</a></li>
    <li class="page-item"><a class="page-link" href="#">3</a></li>
    <li class="page-item"><a class="page-link" href="#">Next</a></li>
  </ul>
</div>

</div>
    <h1></h1> 
</div>
</template>



<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>
