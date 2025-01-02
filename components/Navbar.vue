<template>
   <div>
  <nav class="navbar">
    <div class="logo">
      <img src="~/assets/img/logo.png" alt="Logo Sekolah">
      SMKN 4 TASIKAMALAYA <br>
    </div>
    <ul>
      <li><NuxtLink to="/">BERANDA</NuxtLink></li>
      <li><NuxtLink to="./profil">PROFIL</NuxtLink></li>
      <li><NuxtLink to="./jurusan">JURUSAN</NuxtLink></li>
      <li><NuxtLink to="./ekskul">EKSTRAKULIKULER</NuxtLink></li>
      <li><NuxtLink to="/galeri">GALERI</NuxtLink></li>
      <li><NuxtLink to="/berita">BERITA</NuxtLink></li>

    </ul>
  </nav>
</div>
</template>

<style scoped>
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #333;
  color: #fff;
  padding: 1rem;
}

.logo img {
  width: 50px;
  height: auto;
}

ul {
  list-style: none;
  margin: 0;
  padding: 0;
  display: flex;
}

li {
  margin-right: 20px;
}

a {
  color: #fff;
  text-decoration: none;
}

a:hover {
  color: #ccc;
}


</style>
