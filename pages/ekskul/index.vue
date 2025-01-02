<template>
  <div class="container">
    <h1>Daftar Ekstrakurikuler Sekolah</h1>
    
    <!-- Ekstrakurikuler Section -->
    <div class="extracurricular-section">
      <!-- Ekstrakurikuler 1 -->
      <div class="extracurricular-item">
        <h2>Paskibra</h2>
        <p>Deskripsi: Paskibra, singkatan dari Pasukan Pengibar Bendera, adalah kelompok atau tim khusus yang bertugas untuk mengibarkan atau menurunkan bendera nasional dalam upacara resmi, terutama pada Hari Kemerdekaan dan upacara kenegaraan.</p>
        <img src="~/assets/img/paskib.jpg" alt="gambar" class="extracurricular-img" />
      </div>

      <!-- Ekstrakurikuler 2 -->
      <div class="extracurricular-item">
        <h2>Pramuka</h2>
        <p>Deskripsi: Pramuka adalah singkatan dari Praja Muda Karana, yang berarti "Generasi Muda yang Suka Bekerja." Pramuka adalah organisasi kepanduan yang bertujuan membentuk karakter, keterampilan, dan kepemimpinan bagi generasi muda.</p>
        <img src="~/assets/img/pramuka.jpg" alt="gambar" class="extracurricular-img" />
      </div>

      <!-- Ekstrakurikuler 3 -->
      <div class="extracurricular-item">
        <h2>Futsal</h2>
        <p>Deskripsi: Futsal adalah bentuk permainan sepak bola yang dimainkan di lapangan lebih kecil dan sering kali dilakukan di dalam ruangan. Futsal terkenal dengan permainan cepat, keterampilan teknis, dan pengendalian bola yang lebih intensif dibandingkan sepak bola tradisional.</p>
        <img src="~/assets/img/futsal.jpg" alt="gambar" class="extracurricular-img" />
      </div>

      <!-- Ekstrakurikuler 4 -->
      <div class="extracurricular-item">
        <h2>Seni</h2>
        <p>Deskripsi:  kegiatan ekstrakurikuler yang berfokus pada pengembangan bakat dan kreativitas siswa dalam bidang seni. Kegiatan ini mencakup berbagai disiplin seni, seperti seni rupa, seni musik, seni tari, seni teater, dan seni lainnya.</p>
        <img src="~/assets/img/seni.jpg" alt="gambar" class="extracurricular-img" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
};
</script>

<style scoped>
.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
}

h1 {
  text-align: center;
  margin-bottom: 40px;
}

.extracurricular-section {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  justify-content: space-between;
}

.extracurricular-item {
  flex: 1;
  border: 1px solid #ddd;
  padding: 15px;
  border-radius: 8px;
  text-align: center;
  background-color: #f9f9f9;
  min-width: 250px;
}

.extracurricular-item h2 {
  color: #2c3e50;
}

.extracurricular-item p {
  color: #34495e;
  font-size: 14px;
}

.extracurricular-img {
  width: 100%;
  height: 200px;
  object-fit: cover;
  border-radius: 8px;
}
</style>
