# kupasrahkansemuanyakepadamuyaallah
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lib is My Lab</title>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <link rel="stylesheet" href="Percobaan.css">
</head>
<body>
  <nav class="navbar navbar-inverse">
    <div class="container-fluid">
      <div class="navbar-header">
        <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
        </button>
        <a class="navbar-brand" href="#">Lib is My Lab</a>
      </div>
      <div class="collapse navbar-collapse" id="myNavbar">
        <ul class="nav navbar-nav">
          <li class="active"><a href="#">Beranda</a></li>
          <li class="dropdown">
          <li class="active"><a href="#">About Us</a></li>
          <li class="dropdown">
            <a class="dropdown-toggle" data-toggle="dropdown" href="#">Menu <span class="caret"></span></a>
            <ul class="dropdown-menu">
            <li><a href="Modul 1/Modul 1. index.html">Modul 1</a></li>
            <li><a href="Modul 2/Modul 2.html">Modul 2</a></li>
            <li><a href="Modul 3/Modul 3 Gabungan Inline, Internal, Eksternal.html">Modul 3</a></li>
            <li><a href="Modul 3/Modul 3 Variasi CSS.html">Modul 3</a></li>
            </ul>
          <li class="active"><a href="#">Service</a></li>
          <li class="dropdown">
          <li class="active"><a href="#">Contact</a></li>
          <li class="dropdown"></li>
          <li><a href="#">Form Keanggotaan</a></li>
        </ul>
      </div>
    </div>
  </nav>
  
  <div class="container-fluid">
    <div class="row">
      <div class="col-md-4">
        <h2>SELAMAT DATANG DI LIB IS MY LAB</h2>
      </div>
      <div class="col-md-4">
        <h2>Daftar Koleksi</h2>
        <table class="table table-bordered">
          <thead>
            <tr>
              <th>No</th>
              <th>Judul Buku</th>
              <th>Penulis</th>
              <th>Tahun Terbit</th>
              <th>Nomor Panggil</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>1</td>
              <td>Game Over</td>
              <td>Valerie Patkar</td>
              <td>2020</td>
              <td>823 Pat g</td>
            </tr>
            <tr>
                <td>2</td>
                <td>Claires</td>
                <td>Valeri Patkar</td>
                <td>2018</td>
                <td>823 Pat c</td>
            </tr>
            <tr>
                <td>3</td>
                <td>Nonversation</td>
                <td>Valerie Patkar</td>
                <td>2019</td>
                <td>823 Pat n</td>
            </tr>
          </tbody>
        </table>
      </div>
      <div class="col-md-4">
        <section id="Formulir Keanggotaan">
          <h1>Formulir Keanggotaan</h1>
          <form action="Formulir Keanggotaan metode="POST">
              <label fore="Nama">Nama</label><br>
              <input type="Text" id="Nama" Name="Nama"><br>
              <label for="NIM">NIM:</label><br>
              <input type="Text" id="NIM" Name="NIM"><br>
              <label for="Alamat">Alamat:</label><br>
              <input type="Text" id="Alamat" Name="Alamat"><br>
              <input type="submit" value="submit">
          </form>
        </section>
      </div>
    </div>
  </div>

  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
</body>
</html>
