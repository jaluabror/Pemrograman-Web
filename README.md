# Pemrograman-Web 
Tugas Pemrograman Web 01 (20 september 2024)
By Jalu Muhammad Abror/Informatika 3-A/231730009

## Here is the list  that is neeeded
```
fontawesome.com
https://getbootstrap.com/docs/5.0/components/according/
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css"
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css"
```
## Head Syntax
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Company Profile</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css"
    rel="stylesheet"
    integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" 
    crossorigin="anonymous">
    <link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css"
    integrity="sha384-AYmEC3Yw5cVb3ZcuHt0A93w35dYTsvhLPVnYs9eStHfGJv0vKxVfELGroGkvsg+p"
    crossorigin="anonymous"/>
    <link rel="stylesheet" href="style.css" />
    <script src="https://kit.fontawesome.com/eb0a858d7d.js" crossorigin="anonymous"></script>
    
</head>
<body>
<!-- navigasi -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark shadow-lg fixed-top">
    <div class="container">
      <a class="navbar-brand" href="#">BE YOURSELF WEB J</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarText" aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse text-right" id="navbarText">
        <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
          
          <li class="nav-item">
            <a class="nav-link" href="#Layanan">Layanan</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#Portofolio">Portofolio</a>
          </li>
          <li class="nav-item"></li>
            <a class="nav-link" href="#Tentang">Tentang</a>
          </li>
          <li class="nav-item"></li>
            <a class="nav-link" href="#Staff">Staff</a>
          </li>
          <li class="nav-item"></li>
            <a class="nav-link" href="#Kontak">Kontak</a>
          </li>
        </ul>
        
      </div>
    </div>
  </nav> 
  <!-- banner -->
  <div class="container-fluid. banner">
    <div class="container. text-center">
      <h4 class="display-6">Selamat Datang Di WEBSITE kami</h4>
      <h3 class="display-1">HOLAAA!!</h3>
      <a href="#Layanan">
        <button type="button" class="btn btn-dark btn-lg">
          Cek Layanan
        </button>
      </a>
    </div>
  </div>
  <!-- Layanan -->
  <div class="container-fuild. Layanan pt-5 pb-5">
    <div class="container. text-center">
      <h2 class="display-3" id="Layanan">Layanan</h2>
      <p>Berikut Layanan yang Bisa kami berikan kepada Anda wahai Generasi milenial</p>
      <div class="row pt-4">
        <div class="col-md-4">
          <span class="lingkaran"><i class="fas fa-code fa-5x"></i></span>
       
          <h3 class="mt-3">
           Programing</h3>
            <p>Bagaimana cara untuk menjadi seorang programer</p>
        </div>

        <div class="col-md-4">
          <span class="lingkaran"><i class="fas fa-dice-d20 fa-5x"></i></span>
       
          <h3 class="mt-3">
           Design</h3>
            <p>Bagaimana cara untuk menjadi seorang designer</p>
        </div>

        <div class="col-md-4">
          <span class="lingkaran"><i class="fas fa-heart fa-5x"></i></i></span>
       
          <h3 class="mt-3">
           Networking</h3>
            <p>Bagaimana cara memperluas networking</p>
        </div>
      </div>
    </div>
  </div>  
  <!-- Portofolio -->
  <div class="container-fluid. Portofolio pt-5 pb-5 bg-light">
    <div class="container text-center">
      <h2>
        <h2 class="display-3" id="Portofolio">Portofolio</h2>
      </h2>
      <div class="row pt-4 gx-4 gy-4">
        <div class="col-md-4">
          <div class="card">
            <img src="https://i.pinimg.com/236x/bd/83/2a/bd832a84a7fb698104e2b1d45114ff40.jpg" 
                 class="card-img-top"
                 width="200"
                 height="200">  
                 
            <div class="card-body">
              <h5 class="card-title">The Vibranium</h5>
              <p class="card-text">Vibranium adalah logam fiksi yang muncul dalam buku komik dan film Marvel Comics,
                 yang memiliki kemampuan menyerap, menyimpan, dan melepaskan energi kinetik</p>     
            </div>
          </div>
        </div>
         <div class="col-md-4">
          <div class="card">
            <img src="https://i.pinimg.com/236x/d8/ff/fe/d8fffe03ffd5b81f3280107a50de8ab5.jpg" 
                 class="card-img-top"
                 width="200"
                 height="200">

            <div class="card-body">
              <h5 class="card-title">The Custom</h5>
              <p class="card-text">kostum ini terbuat dari bahan cetak 3D yang memadukan desain modern dengan motif tradisional Afrika.
                 Dibuat oleh Andy Park dan dirancang oleh Judianna Makovsky</p>     
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <img src="https://i.pinimg.com/236x/2f/44/ac/2f44ac0890ade1dc5f882685d4f75187.jpg" 
                 class="card-img-top"
                 width="200"
                 height="200"  
                 >
            <div class="card-body">
              <h5 class="card-title">The Achivement</h5>
              <p class="card-text">Black Panther membawa pulang tiga Oscar,
                 kalah dalam kategori film terbaik dari Green Book ini adalah pecapaian yang sangat berharga</p>
     
            </div >
          </div>
        </div>       
        <div class="col-md-4">
          <div class="card">
            <img src="https://i.pinimg.com/564x/ea/98/d9/ea98d9b1caa83d3761723b0231db4849.jpg" 
                 class="card-img-top"
                 width="200"
                 height="200">  
                 
            <div class="card-body">
              <h5 class="card-title">The Story</h5>
              <p class="card-text">Black Panther, T'Challa dinobatkan sebagai raja Wakanda setelah kematian ayahnya,
                 tetapi ia ditantang oleh Killmonger (Jordan), yang berencana untuk meninggalkan kebijakan isolasionis negara itu dan memulai revolusi global. </p>     
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <img src="https://i.pinimg.com/564x/dc/7b/37/dc7b37282ef891a95aba6957b39d3415.jpg" 
                 class="card-img-top"
                 width="200"
                 height="200">  
                 
            <div class="card-body">
              <h5 class="card-title">Action Place</h5>
              <p class="card-text">Black Panther dibawa ke suatu tempat bernama Ancestral Plane.
                 Erik kemudian membunuh Klaw dan menggunakan vibranium sebagai sesuatu untuk menjaganya tetap aman saat memasuki Wakanda. negeri wakanda adalah negeri fiksi</p>     
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <img src="https://i.pinimg.com/236x/4f/10/2c/4f102c20397fbb7f976c35a212b4a345.jpg" 
                 class="card-img-top"
                 width="200"
                 height="200">  
                 
            <div class="card-body">
              <h5 class="card-title">The Actor</h5>
              <p class="card-text">Chadwick Boseman
                T’Challa
                
                Letitia Wright
                Shuri
                
                Michael Bakari Jordan
                Erik Killmonger
                
                Danai Gurira
                Okoye
                
                Lupita Nyong'o
                Nakia
                
                Winston Duke
                M'Baku
                
                Angela Bassett
                Ramonda
                
                Daniel Kaluuya
                W'Kabi
                
                Jalu Abror 
                sturadara
              </p>     
            </div>
          </div>
        </div>

      </div>
    </div>
  </div>
  <!-- Tentang -->
   <div class="container-fluid. Tentang pt-5 pb-5">
    <div class="container">
      <h2 class="display-3 text-center" id="Tentang">Tentang</h2>
      <p class="text-center">
        
      </p>
      <div class="clearfix pt-5">
      <img 
        src="https://i.pinimg.com/564x/ee/72/de/ee72de97038a333920ab2fc0d4561687.jpg"
        class="col-md-6 float-md-end mb-3 crop-img" 
        width="300" 
        height="300">
      </div>
        
        <p>
          Black Panther pertama kali ditayangkan di Los Angeles pada 29 Januari 2018, dan dirilis di Amerika Serikat pada 16 Februari 2018, dalam 2D, 3D, IMAX, dan format premium lainnya. Film ini mendapatkan pujian dari para kritikus atas pengarahan, skenario, akting (terutama Boseman, Jordan, dan Wright), desain kostum, nilai produksi, dan soundtrack-nya, walaupun efek pencitraan hasil komputernya (CGI) mendapat beberapa kritikan. Banyak kritikus menganggap bahwa film yang dikenal karena signifikasi budayanya ini merupakan salah satu film-film terbaik dari MCU. Film ini pun dinobatkan sebagai salah satu dari 10 Film Terbaik tahun 2018 oleh lembaga-lembaga perfilman seperti Lembaga Film Amerika dan National Board of Review. Selama masa penayangannya, film ini menjadi film dengan penghasilan tertinggi ke-9 dengan penghasilan kotor lebih dari $1,35 miliar di seluruh dunia dan film dengan penghasilan tertinggi ke-3 di Amerika Utara dengan penghasilan kotor sebesar $700 juta, serta memecahkan berbagai rekor box office, diantaranya film dengan penghasilan tertinggi di Amerika Serikat dan Kanada pada tahun 2018, dan film dengan penghasilan tertinggi kedua di dunia pada tahun 2018.
        </p>
        <p>
          Film ini juga mendapatkan berbagai penghargaan dan nominasi, memperoleh tujuh nominasi dalam penghargaan Academy Awards ke-91, diantaranya Film Terbaik, serta memenangkan kategori Desain Kostum Terbaik, Musik Orisinal Terbaik, dan Tata Artistik Terbaik. Black Panther adalah film superhero pertama yang mendapatkan nominasi Film Terbaik, serta film pertama MCU yang memenangkan Academy Award. Film ini juga mendapatkan tiga nominasi dari Golden Globe Awards ke-76, dua kemenangan di Screen Actors Guild Awards ke-25, dan dua belas nominasi dari Critics' Choice Awards ke-24 (memenangkan tiga dari dua belas). Sekuel film ini sedang berada dalam tahap pengembangan, dan Coogler akan kembali sebagai sutradara dan penulis skenarionya.
        </p>
        
    </div>
   </div>
   <!-- Staff and Team -->
    <div class="container-fluid pt-5 pb-5 bg-light">
      <div class="container text-center">
        <h2 class="display-3" id="Staff">Staff</h2>
        <p>
            Berikut adalah Tim kreatif dari Black Panther
        </p>
        <div class="row pt-4 gx-4 gy-4">
          <div class="col-md-4 text-center staff">
            <img src="https://i.pinimg.com/236x/3b/8b/bc/3b8bbcb2940bde9a0f51313dcffb3db7.jpg"
                class="rounded-circle mb-4"
            />
            <h4> Ryan Coogler </h4>
            <p>As Sutradara</p>
            <p>
              <a href="" class="social"><i class="fa-brands fa-x-twitter"></i></a>
              <a href="" class="social"><i class="fa-brands fa-square-instagram"></i></a>
              <a href="" class="social"><i class="fa-brands fa-linkedin"></i></a>
            </p>
          </div>

          <div class="col-md-4 text-center staff">
            <img src="https://i.pinimg.com/236x/ae/08/85/ae08850265a3671d5a22e6eca418e29e.jpg"
                class="rounded-circle mb-3"
            />
            <h4> Michel D.Jordan </h4>
            <p>As Content Kreator</p>
            <p>
              <a href="" class="social"><i class="fa-brands fa-x-twitter"></i></a>
              <a href="" class="social"><i class="fa-brands fa-square-instagram"></i></a>
              <a href="" class="social"><i class="fa-brands fa-linkedin"></i></a>
            </p>
          </div>

          <div class="col-md-4 text-center staff">
            <img src="https://i.pinimg.com/236x/db/be/42/dbbe428ab10096003bc73fa509344543.jpg"
                class="rounded-circle mb-3"
            />
            <h4>Tenoch Huerta</h4>
            <p>As Web Branding</p>
            <p>
              <a href="" class="social"><i class="fa-brands fa-x-twitter"></i></a>
              <a href="" class="social"><i class="fa-brands fa-square-instagram"></i></a>
              <a href="" class="social"><i class="fa-brands fa-linkedin"></i></a>
            </p>
          </div>
          

           
        </div>
      </div>
    </div>
    <!-- client -->
     <div class="container-fluid client pt-5 pb-5">
      <div class="container text-center">
        <div class="row pt-4 gx-4 gy-4">
          <div class="col">
            <img src="https://i.pinimg.com/236x/b0/0a/11/b00a11998b537c5d4c02b2f5e0340aec.jpg"/>
          </div>

          <div class="col">
            <img src="https://i.pinimg.com/236x/b7/63/69/b763699fd1fa3bfb374442593ae642e1.jpg"/>
          </div>

          <div class="col">
            <img src="https://i.pinimg.com/236x/06/63/09/066309aaa7b67ba1e9c495b0667ceb57.jpg"/>
          </div>

          <div class="col">
            <img src="https://i.pinimg.com/236x/f6/68/90/f66890653a1275aa5b742387233f4243.jpg"/>
          </div>
          <div class="col">
            <img src="https://i.pinimg.com/564x/cf/11/eb/cf11ebcc0a874e3ad3830431f7b0ab58.jpg"/>
          </div>

        </div>
      </div>
     </div>
     <!-- Kontak -->
     <div class="container-fluid pt-5pb-5 Kontak">
      <div class="container">
        <h2 class="display-3 text-center" id="Kontak">Kontak kami</h2>
        <p class="text-center">Silahkan Hubungi kami</p>
           <div class="row pb-3">
            <div class="col-md-6">
              <input class="form-control form-control-lg mb-3" 
                     type="text" 
                     placeholder="Nama"/>
              <input class="form-control form-control-lg mb-3" 
                     type="text" 
                     placeholder="E-mail"/>
              <input class="form-control form-control-lg mb-3" 
                     type="text"   
                     placeholder="NO. Phone"/>
            </div>
            <div class="col-md-6">
              <textarea class="form-control form-control-lg" rows="5"></textarea>
            </div>
           </div>
            <div class="col-md-3 mx-auto text-center">
              <button type="button" class="btn btn-dark btn-lg">Kirim Pesan</button>
            </div>
      </div>
     </div>
     <div class="container text-center pt-5 pb-5">
      All Rights Reserved&Copy@1999
     </div>


    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" 
    integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM"
    crossorigin="anonymous"></script>

    </script>
</body>
</html>

```
