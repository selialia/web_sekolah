<template>
    <div class="row">
</div>
<div class="footer">
  <p>Copyright <i class="fa-regular fa-copyright"></i> SMKN 4 Tasikmalaya 2024 by selialiaa</p>
</div>

  </template>
  
  <style scoped>
  .footer {
    position: fixed; 
    top: 0;
    left: 0;
    background-color: #343434; /* Warna merah */
    color: rgb(255, 255, 255); /* Warna teks putih */
    text-align: center; /* Teks di tengah */
    padding: 0.5rem 0; /* Padding lebih kecil */
    position: relative; /* Footer berada setelah konten */
    width: 100%; /* Memastikan footer selebar layar */
    font-size: 0.9rem; /* Ukuran font lebih kecil */
    margin-top: 20px; /* Jarak dengan konten atas */
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