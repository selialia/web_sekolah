<template>
  <div class="row">
    <div class="col">
      <div class="kompetensi-section">
        <!-- Teks Tengah dengan Background -->
        <div class="kompetensi-header">
          <i class="icon bi-mortarboard-fill"></i>
          <h1>Kompetensi Keahlian</h1>
        </div>
      </div>
    </div>
  </div>

  <div class="row">
    <div class="col">
      <!-- Cards Section (Flexbox for horizontal layout) -->
      <div class="cards-section" style="display: flex; flex-wrap: wrap; gap: 20px; justify-content: space-around;">
        <!-- Card 1 -->
        <div class="card" style="width: 18rem;">
          <div class="card-image">
            <img src="~/assets/img/rpl.jpg" alt="Pengembangan Perangkat Lunak dan Gim" style="width: 100%; height: 200px; object-fit: cover;"/>
          </div>
          <div class="card-text">
            <h2>Pengembangan Perangkat Lunak & Gim</h2>
            <p>Jurusan PPLG difokuskan pada:
              <br>Pemrograman dan Pengembangan software, Pengembangan aplikasi web dan mobile, Pembuatan Game, Basis Data, Desain antarmuka pengguna (UI/UX) dan Algoritma & Logika Pemrograman.</br>
            </p>
          </div>
        </div>
        
        <!-- Card 2 -->
        <div class="card" style="width: 18rem;">
          <div class="card-image">
            <img src="~/assets/img/tjkt.jpg" alt="Teknik Komputer dan Jaringan Komputer" style="width: 100%; height: 200px; object-fit: cover;"/>
          </div>
          <div class="card-text">
            <h2>Teknik Komputer & Jaringan Komputer</h2>
            <p>Jurusan TKJK difokuskan pada:
              <br>Jaringan Komputer (Instalasi dan Konfigurasi Jaringan, Administrasi Server), Keamanan Siber (Cybersecurity), dan Perangkat Keras (Perakitan dan Pemeliharaan Komputer).</br>
            </p>
          </div>
        </div>

        <!-- Card 3 -->
        <div class="card" style="width: 18rem;">
          <div class="card-image">
            <img src="~/assets/img/otomotif.jpg" alt="Teknik dan Bisnis Sepeda Motor" style="width: 100%; height: 200px; object-fit: cover;"/>
          </div>
          <div class="card-text">
            <h2>Teknik & Bisnis Sepeda Motor</h2>
            <p>Jurusan TBSM difokuskan pada:
              <br>Teknik Servis Sepeda Motor (Memahami sistem mekanik dan elektrikal sepeda motor, Praktik perbaikan dan pemeliharaan mesin), dan Bisnis dan Manajemen Otomotif (Pemasaran dan Distribusi Sepeda Motor, Manajemen Pelayanan Pelanggan).</br>
            </p>
          </div>
        </div>

        <!-- Card 4 -->
        <div class="card" style="width: 18rem;">
          <div class="card-image">
            <img src="~/assets/img/desain.jpg" alt="Desain Komunikasi Visual" style="width: 100%; height: 200px; object-fit: cover;"/>
          </div>
          <div class="card-text">
            <h2>Desain Komunikasi Visual</h2>
            <p>Jurusan DKV difokuskan pada:
              <br>Desain Grafis, Multimedia dan Animasi, Fotografi dan Videografi, Branding dan Identitas Visual, serta Desain Interaksi (UI/UX).</br>
            </p>
          </div>
        </div>

        <!-- Card 5 -->
        <div class="card" style="width: 18rem;">
          <div class="card-image">
            <img src="~/assets/img/otomasi.jpg" alt="Teknik Otomotif Industri" style="width: 100%; height: 200px; object-fit: cover;"/>
          </div>
          <div class="card-text">
            <h2>Teknik Otomotif Industri</h2>
            <p>Jurusan TOI difokuskan pada:
              <br>Sistem Otomasi dan Kontrol, Elektronik dan Sistem Kendali, IoT dalam Industri, Pemrograman untuk Otomasi, serta Pemeliharaan dan Perbaikan Sistem.</br>
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
