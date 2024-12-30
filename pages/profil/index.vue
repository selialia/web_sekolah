<template>
    <div class="profil-container">
      <div class="profil-header">
        <h1>Profil Sekolah</h1>
        <h2>{{ profil.namaSekolah }}</h2>
      </div>
      <div class="profil-body">
        <div class="profil-left">
          <h3>Informasi Umum</h3>
          <p><strong>Alamat:</strong> {{ profil.alamat }}</p>
          <p><strong>Kepala Sekolah:</strong> {{ profil.kepalaSekolah }}</p>
          <p><strong>Jenis Pendidikan:</strong> {{ profil.jenisPendidikan }}</p>
          <p><strong>Sejarah Sekolah:</strong> {{ profil.SejarahSekolah }}</p>
        </div>
        <div class="profil-right">
          <h3>Visi</h3>
          <p>{{ profil.visi }}</p>
          <h3>Misi</h3>
          <ul>
            <li v-for="(misi, index) in profil.misi" :key="index">{{ misi }}</li>
          </ul>
          <h3>Fasilitas</h3>
          <ul>
            <li v-for="(fasilitas, index) in profil.fasilitas" :key="index">{{ fasilitas }}</li>
          </ul>
        </div>
      </div>
      <div class="col">
        <section class="section" id="identitas">
      <h2 class="section-title">Identitas Sekolah</h2>
      <div class="identitas-content">
        <div class="identitas-item">
          <h3>Nama Sekolah</h3>
          <p>SMK Negeri 4 Tasikmalaya</p>
        </div>
        <div class="identitas-item">
          <h3>NPSN</h3>
          <p>20276063</p>
        </div>
        <div class="identitas-item">
          <h3>Nomor Statistik Sekolah</h3>
          <p>401327810004</p>
        </div>
        <div class="identitas-item">
          <h3>Alamat</h3>
          <p>Jalan Depok RT 02 RW 05</p>
        </div>
        <div class="identitas-item">
          <h3>Telepon</h3>
          <p>+(62)265312059</p>
        </div>
        <div class="identitas-item">
          <h3>Email</h3>
          <p>info@smkn4tsm.sch.id</p>
        </div>
      </div>
    </section>
  </div>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        profil: {
          namaSekolah: "SMKN 4 TASIKMALAYA",
          kepalaSekolah: "Kurniawan, S.Pd, M.Pd.",
          visi: "Dengan Berlandaskan Iman dan Taqwa Menghasilkan Tamatan yang Cerdas,Akhlak mulia, Kreatif, Aktif, Produktif (CAKAP).",
          misi: [
            "Menyiapkan Sumber Daya Manusia yang cerdas dan kompeten baik hardskill maupun softskill.",
            "Meningkatkan dan mengembangkan aktifitas serta kreatifitas seluruh warga sekolah dalam berbagai kegiatan positif.",
            "Mewujudkan manajemen pengelolaan yang efektif, efesien, transparan, akuntabel dan layanan prima.",
            "Menumbuhkan dan mengembangkan potensi dan kemampuan Sumber Daya Manusia yang berdaya saing tinggi melalui berbagai kegiatan akademik maupun non akademik.",
            "Menyelenggarakan berbagai program kegiatan dalam upaya meningkatkan Sumber Daya Manusia yang mampu menyesuaikan dengan perkembangan.",
            "Mengembangkan sarana prasarana dan lingkungan sekolah yang menyenangkan sebagai wadah menumbuhkembangkan daya kreasi dan inovasi untuk menghasilkan produk teknologi tepat guna.",
            "Membangun jiwa wirausaha yang handal melalui pembelajaran Teaching Factory (TEFA) dan Kelas Industri.",
            "Menjalin dan mengembangkan kemitraan dengan Industri dan Dunia Kerja (IDUKA) serta lembaga lainnya yang relevan.",
            "Menanamkan dan membudayakan sikap dan perilaku yang baik pada aktivitas di sekolah maupun dalam kehidupan sehari-hari.",
          ],
          alamat: "Jl Depok Kel. Sukamenak Kec. Purbaratu Kota Tasikmalaya 46196.",
          jenisPendidikan: "Sekolah Menengah Kejuruan (SMK)",
          SejarahSekolah: "Sejalan dengan Program Pemerintah dibidang pendidikan Menengah Kejuruan pada saat itu yakni pemerataan akses ditambah pula dengan banyaknya keinginan masyarakat yang mengharapkan adanya SMK Negeri di daerah Kecamatan Purbaratu Kota Tasikmalaya, terutama untuk menampung tamatan dari SLTP yang ingin melanjutkan ke SMK maka beberapa tokoh masyarakat, unsur pejabat pemerintah di Kecamatan Purbaratu Kota Tasikmalaya mengusulkan kepada pemerintah Kota Tasikmalaya dan Pemerintah Provinsi Jawa Barat, agar berdirinya SMK Negeri di Kecamatan Purbaratu Kota Tasikmalaya. Setelah melalui perjuangan yang sangat panjang dari berbagai pihak khususnya Disdik Kota Tasikmalaya dan pihak-pihak terkait lainnya sesuai prosedur dan ketentuan yang berlaku pada waktu itu dengan mengucapkan syukur Alhamdulillah akhirnya pada tahun pelajaran 2010/2011 SMK Negeri 4 Tasikmalaya mulai berdiri, pada awalnya membuka Kompetensi Keahlian Teknik Komputer dan Jaringan dengan pendaftar peserta Didik Baru pada waktu itu berjumlah 44 orang. Pada awalnya tempat belajar menumpang di SMP Negeri 17 Kota Tasikmalaya, dan sekolah induknya adalah SMK Negeri 2 Kota Tasikmalaya, Untuk Tenaga pendidik dan Tenaga Kependidikan masih dibantu sepenuhnya oleh kedua sekolah tersebut. Pada tahun 2012 keluarlah surat Izin Pendirian berdasarkan keputusan kepala Badan Pelayanan Perizinan Terpadu Kota Tasikmalaya No. 420/9/SK-BPPT/2012 Tanggal 06 Februari 2012.", 
         fasilitas: [
            "Perpustakaan",
            "Laboratorium Komputer",
            "Lapangan Olahraga",
            "Kantin Sehat",
          ],
        }
      };
    }
  };
  </script>
  
  <style scoped>
  .profil-container {
    font-family: Arial, sans-serif;
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
    border: 1px solid #ddd;
    border-radius: 8px;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
  }
  
  .profil-header {
    text-align: center;
    margin-bottom: 20px;
  }
  
  .profil-header h1 {
    color: #2c3e50;
  }
  
  .profil-header h2 {
    color: #8d929a;
    font-weight: bold;
  }
  
  .profil-body {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
  }
  
  .profil-left, .profil-right {
    flex: 1;
    padding: 20px;
    border: 1px solid #f0f0f0;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  }
  
  .profil-left {
    background-color: #f9f9f9;
  }
  
  .profil-right {
    background-color: #fff;
  }
  
  h3 {
    color: #333;
  }
  
  ul {
    list-style-type: disc;
    margin-left: 20px;
  }
  
  p, li {
    color: #555;
    line-height: 1.6;
  }
  
  @media (max-width: 768px) {
    .profil-body {
      flex-direction: column;
    }
  }
  .section {
  margin: 2rem 0;
  padding: 1rem;
  background-color: hsl(180, 5%, 73%);
  border-radius: 8px;
}

.section-title {
  font-size: 2rem;
  color:#333;
  margin-bottom: 1rem;
  text-align: center;
}

.section-content {
  font-size: 1rem;
  color: #333;
  line-height: 1.6;
}

.identitas-content {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1rem;
}

.identitas-item {
  background-color: #fff;
  padding: 1rem;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.identitas-item h3 {
  color: #333;
  font-size: 1.1rem;
}
</style>
  