<template>
  <div class="container-fluid">
    <div class="row my-5">

      <div class="col-lg-12 mb-5">
        <div class="crounded-5">
          <img src="~/assets/img/guru.jpg" alt="gambar" style="width: 100%; height: 50%;" />
        </div>
      </div>

      <div class="col-lg-12">
        <div class="sambutan rounded-5">
          <div class="sambutan-content">
            <img src="~/assets/img/kepalasekolah.jpg" alt="Kepala Sekolah" class="kepala-sekolah-img" />

            <!--Teks Sambutan-->
            <div class="Sambutan Kepala Sekolah">
              <p>
                Assalamualaikum Warahmatullahi Wabarakatuh<br />
                Selamat datang di SMKN 4 Tasikmalaya. Segala puji dan syukur kita panjatkan kehadirat Allah SWT, semoga
                kita semua ada dalam lindungan-Nya. Dan atas perkenan-Nya pula kami dapat menghadirkan website SMK
                Negeri 4 Tasikmalaya ini. Kami berharap dengan adanya website di SMK Negeri 4 Tasikmalaya ini para
                pengunjung dapat mengenal lebih jauh tentang sekolah kami sehingga dapat mempererat tali silaturrahmi
                antara sekolah dengan masyarakat demi kemajuan kita bersama. Tiada gading yang tak retak, website kami
                ini masih dalam proses pengembangan, masih banyak kekurangan yang harus kami perbaiki. Kritik dan
                sarannya yang membangun sangat kami harapkan untuk pengembangan ke depan.
                <br> <br />
                Akhirnya, saya mengucapkan terimakasih yang sebesar-besarnya kepada semua pihak yang tidak dapat
                disebutkan satu segala bantuan dan persatu atas fasilitasnya yang telah diberikan semoga semua yang kita
                lakukan bermanfaat bagi masyarakat. Wassalamu'alaikum Warahmatullahi Wabarakatuh.

              </p>
            </div>

            <p><strong>- Kurniawan, S.Pd, M.Pd.</strong></p>

          </div>
        </div>
      </div>

    </div>
  </div>
</template>

<style scoped>
.card {
  height: 400px;
  box-shadow: 1px 1px 10px #424242;
  width: 50vw;
  max-width: 10000px;
  padding-left: 100px;
  padding-right: 100px;

}

.kepala-sekolah-img {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  object-fit: cover;
}


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