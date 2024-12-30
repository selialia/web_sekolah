<template>
  <!-- Logo Section -->
  <div class="text-center mt-4">
  <h3 style="color: black; text-align: center; margin: 0px;">SELAMAT DATANG DI SMK PUSAT KEUNGGULAN SMKN 4 TASIKMALAYA</h3>
  </div>
  <div class="container-fluid">
    <div class="row my-5">
      
      <div class="col-lg-12 mb-5">
        <div class="crounded-5">
          <img src="~/assets/img/skul.png" alt="gambar" style="width: 100%; height: 500px;" />
        </div>
      </div>

      <!-- Sambutan Kepala Sekolah -->
      <div class="col-lg-12">
        <div class="sambutan rounded-5">
          <div class="sambutan-content">
            <!-- Gambar Kepala Sekolah -->
            <img src="~/assets/img/bapak.png" alt="Kepala Sekolah" class="kepala-sekolah-img" />

            <!-- Teks Sambutan -->
            <div class="sambutan-text">
              <h2>Sambutan Kepala Sekolah</h2>
              <p>
                Assalamualaikum Warahmatullahi Wabarakatuh<br />
                Selamat datang di SMKN 4 Tasikmalaya. Segala puji dan syukur kita panjatkan kehadirat Allah SWT, semoga kita semua ada dalam lindungan-Nya. Dan atas perkenan-Nya pula kami dapat menghadirkan website SMK Negeri 4 Tasikmalaya ini. Kami berharap dengan adanya website di SMK Negeri 4 Tasikmalaya ini para pengunjung dapat mengenal lebih jauh tentang sekolah kami sehingga dapat mempererat tali silaturrahmi antara sekolah dengan masyarakat demi kemajuan kita bersama. Tiada gading yang tak retak, website kami ini masih dalam proses pengembangan, masih banyak kekurangan yang harus kami perbaiki. Kritik dan sarannya yang membangun sangat kami harapkan untuk pengembangan ke depan.
                <br /><br />
                Akhirnya, saya mengucapkan terimakasih yang sebesar-besarnya kepada semua pihak yang tidak dapat disebutkan satu segala bantuan dan persatu atas fasilitasnya yang telah diberikan semoga semua yang kita lakukan bermanfaat bagi masyarakat. Wassalamu'alaikum Warahmatullahi Wabarakatuh.
              </p>
              <p><strong>- Kurniawan, S.Pd, M.Pd.</strong></p>
            </div>
          </div>
        </div>
      </div>

    </div>
  </div>
</template>

<style scoped>
/* Styling Kartu */
.card {
  height: 400px;
  box-shadow: 1px 1px 10px #424242;
  width: 50vw;
  max-width: 10000px; /* Responsif untuk lebar kartu */
  padding-left: 100px; /* Tambah jarak kiri */
  padding-right: 100px; /* Tambah jarak kanan */
}
/* Styling Sambutan */
.sambutan {
  background-color: #f9f9f9;
  box-shadow: 1px 1px 10px #dadada;
  padding: 20px;
}

.sambutan-content {
  display: flex;
  flex-direction: column; /* Mengatur gambar dan teks supaya berada dalam satu kolom */
  align-items: center; /* Menyusun elemen-elemen di tengah */
}

.kepala-sekolah-img {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  object-fit: cover;
  box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.2);
  margin-bottom: 15px; /* Menambahkan jarak bawah gambar */
}

.sambutan-text h2 {
  color: #424242;
  margin-bottom: 10px;
  font-size: 1.8rem;
}

.sambutan-text p {
  font-size: 1rem;
  line-height: 1.6;
  color: #555;
}

.sambutan-text strong {
  color: #333;
}

/* Responsivitas */
@media (max-width: 768px) {
  .sambutan-content {
    align-items: center;
  }

  .card {
    width: 90vw;
    padding-left: 50px;
    padding-right: 50px;
  }
}
</style>
