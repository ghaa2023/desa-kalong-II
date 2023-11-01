<script setup>
import Header from "../components/Header.vue";
import Banner from "../components/Banner.vue";
import Sidebar from "../components/Sidebar.vue";
</script>

<template>
  <Header />
  <Banner />

  <main class="flex">
    <Sidebar />

    <div class="flex-1 p-10">
      <p class="text-3xl font-semibold">Visi & Misi Desa</p>
      <p class="text-lg font-semibold">Visi</p>
      <p>
        “Terwujudnya masyarakat desa Kalong II yang beriman (Berahlak Karimah, Intelektual, Mandiri dan Nyaman)”
      </p>
      <p class="text-lg font-semibold">Misi</p>
      <ul>
        <li>
          1. Meningkatkan Kegiatan Keagamaan, sosial, ekonomi dan kepemudaan;
        </li>
        <li>
          2. Meningkatkan pelayanan yang prima dan pengabdian yang tulus terhadap masyarakat;
        </li>
        <li>
          3. Meningkatkan kualitas SDM aparatur pemerintah Desa yang berorientasi menuju Desa presisi;
        </li>
        <li>
          4. Meningkatkan Pembangunan sarana prasarana desa, agar tercipta masyarakat desa yang "BERIMAN";
        </li>
        <li>
          5. Meningkatkan Pemberdayaan dan serta masyarakat dalam rangka sistem keamanan lingkungan (SISKAMLING);
        </li>
      </ul>
    </div>
  </main>
</template>

<style>
body {
  background: #f1f1f1;
}
</style>
