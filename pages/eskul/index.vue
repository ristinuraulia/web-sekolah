<template>
  <div class="container-fluid">
    <div class="row p-5">
      <div class="col-md-4 text-center p-5">
        <img src="/assets/img/srl.jpeg" alt="Laskar Pustaka" class="rounded-circle" />
        <h4>LASKAR PUSTAKA</h4>
      </div>
      <div class="col-md-4 text-center p-5">
        <img src="/assets/img/plh.jpeg" alt="Paskibra" class="rounded-circle" />
        <h4>PASKIBRA</h4>
      </div>
      <div class="col-md-4 text-center p-5">
        <img src="/assets/img/safety.jpg" alt="Palang Merah Remaja" class="rounded-circle" />
        <h4>PALANG MERAH REMAJA</h4>
        <div class="col-md-4 text-center p-5">
          <img src="/assets/img/badminton.jpeg" alt=" Badminton" class="rounded-circle" />
          <h4>BADMINTON</h4>
        </div>
        <div class="col-md-4 text-center p-5">
          <img src="/assets/img/srl.jpeg" alt=" Badminton" class="rounded-circle" />
          <h4>SAFETY</h4>
        </div>
        <div class="col-md-4 text-center p-5">
          <img src="/assets/img/tari.jpeg" alt=" Badminton" class="rounded-circle" />
          <h4>TARI</h4>
        </div>
        <div class="col-md-4 text-center p-5">
          <img src="/assets/img/sepak bola.jpeg" alt=" Badminton" class="rounded-circle" />
          <h4>SEPAK BOLA</h4>
        </div>
        <div class="col-md-4 text-center p-5">
          <img src="/assets/img/voli.jpeg" alt=" Badminton" class="rounded-circle" />
          <h4>VOLI</h4>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
/* Menyusun gambar agar berbentuk lingkaran */
img {
  width: 150px;
  /* Ukuran tetap agar gambar bisa berbentuk lingkaran */
  height: 150px;
  /* Sesuaikan tinggi dan lebar agar persegi */
  object-fit: cover;
  /* Memastikan gambar tetap terlihat dengan baik tanpa terdistorsi */
  border-radius: 50%;
  /* Membuat gambar berbentuk lingkaran */
}

/* Menambahkan margin pada gambar untuk pemisahan yang lebih baik */
h4 {
  margin-top: 10px;
}
</style>