<template>
  <div class="container">
    <h1>Daftar Ekstrakurikuler Sekolah</h1>
    
    <!-- Ekstrakurikuler 1 -->
    <div class="extracurricular-item">
      <h2>Paskibra</h2>
      <p>Deskripsi: Paskibra, singkatan dari Pasukan Pengibar Bendera, adalah kelompok atau tim khusus yang bertugas untuk mengibarkan atau menurunkan bendera nasional dalam upacara resmi, terutama pada Hari Kemerdekaan dan upacara kenegaraan..</p>
      <img src="~/assets/img/paskib.jpg" alt="gambar" style="width: 50%; height: 300px;" />
    </div>

    <!-- Ekstrakurikuler 2 -->
    <div class="extracurricular-item">
      <h2>Pramuka</h2>
      <p>Deskripsi: Pramuka adalah singkatan dari Praja Muda Karana, yang berarti "Generasi Muda yang Suka Bekerja." Pramuka adalah organisasi kepanduan yang bertujuan membentuk karakter, keterampilan, dan kepemimpinan bagi generasi mudam.</p>
      <img src="~/assets/img/pramuka.jpg" alt="gambar" style="width: 50%; height: 300px;" />
    </div>

    <!-- Ekstrakurikuler 3 -->
    <div class="extracurricular-item">
      <h2>Futsal</h2>
      <p>Deskripsi:Futsal adalah bentuk permainan sepak bola yang dimainkan di lapangan lebih kecil dan sering kali dilakukan di dalam ruangan. Futsal terkenal dengan permainan cepat, keterampilan teknis, dan pengendalian bola yang lebih intensif dibandingkan sepak bola tradisional..</p>
      <img src="~/assets/img/futsal.jpg" alt="gambar" style="width: 50%; height: 300px;" />
    </div>

    <!-- Ekstrakurikuler 4 -->
    <div class="extracurricular-item">
      <h2>Seni</h2>
      <p>Deskripsi: Ekstrakurikuler musik, mulai dari vokal hingga alat musik.</p>
      <img src="~/assets/img/logo.png" alt="gambar" style="width: 50%; height: 300px;" />
    </div>

    <!-- Ekstrakurikuler 4 -->
    <div class="extracurricular-item">
      <h2>Cinematografi</h2>
      <p>Deskripsi: Sinematografi adalah seni dan teknik merekam visual dalam bentuk gambar bergerak, baik untuk film, televisi, video, maupun media lainnya. Dalam sinematografi, aspek teknis dan artistik digabungkan untuk menciptakan gambar yang mendukung narasi, emosi, dan pengalaman penonton.</p>
      <img src="~/assets/img/cj.jpg" alt="gambar" style="width: 50%; height: 300px;" />
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
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
}

h1 {
  text-align: center;
  margin-bottom: 20px;
}

.extracurricular-item {
  border: 1px solid #ddd;
  margin-bottom: 20px;
  padding: 15px;
  border-radius: 8px;
}

.extracurricular-item h2 {
  color: #2c3e50;
}

.extracurricular-item p {
  color: #34495e;
  font-size: 14px;
}
</style>
