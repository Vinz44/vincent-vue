<template>
  <div class="hello">
    <div class="container-fluid p-5 bg-primary text-white text-center">
  <h1>Nama : </h1>
  <p>Vincent (2024250011)</p> 
</div>

<div id="section1" class="container-fluid bg-success text-white" style="padding:100px 20px;">
  <h1>Pendidikan : </h1>
  <p>TK : KDB 1</p>
  <p>SD : KDB 1</p>
  <p>SMP : SMP Indriasana</p>
  <p>SMK : SMK Xaverius 1 Palembang</p>
  <p>Universitas : MDP Palembang</p>
</div>

<div id="section2" class="container-fluid bg-warning" style="padding:100px 20px;">
  <h1>Hobby : </h1>
  <p> Playing Games</p>
  <p> Drawing Character </p>
  <p> Swiming </p>
</div>

<div id="section3" class="container-fluid bg-secondary text-white" style="padding:100px 20px;">
  <h1> Pengalaman :  </h1>
  <p> Hanya pernah Magang Di Saat masih SMK di Tempat Komputer dan tempat Konsultasi Pajak</P>
  <p></P>
  <p></P>
</div>
<div class="container mt-3">
  <h2>Email : vinsenthuang004@gmail.com</h2>
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
