<script setup>
import Header from '../components/Header.vue'
import Banner from '../components/Banner.vue'
import Sidebar from '../components/Sidebar.vue'
</script>

<template>
  <Header/>
  <Banner/>
  <main class="flex">
    <Sidebar/>
    <div class="flex-1 p-10">


      <p class="text-3xl font-semibold">Visi & Misi Desa</p>
      <br/>
      <p>Visi, Misi Desa Dayeuh disamping merupakan Visi, Misi Calon Kepala Desa terpilih, juga diintegrasikan dengan keinginan bersama masyarakat desa dimana proses penyusunannya dilakukan secara partisipatif mulai dari tingkat Dusun/RW sampai tingkat Desa.</p>

<br/>
<p>Adapun Visi Desa Dayeuh sebagai berikut:</p>
<br/>
“SADAR DIRI” atau Desa Dayeuh Religi, Dinamis dan Mandiri.
<br/>
<br/>
<p>Sedangkan Misi Desa Dayeuh adalah:</p>
<br/>
<p>1. Memberdayakan masyarakat melalui partisipasi aktif dalam pembangunan.</p>
<p>2. Merata dalam Pelaksanaan Pembangunan diseluruh wilayah Desa Dayeuh.</p>
<p>3. Menyelenggarakan pemerintahan yang bersih, amanah dan terbuka berorientasi pada optimalisasi pelayanan kepada masyarakat.</p>
<p>4. Peningkatan sarana dan prasarana dasar untuk menunjang kesejahteraaan dan meningkatkan pelayanan publik.</p>
<p>5. Memanpaatkan potensi sumber daya alam.</p>
<p>6. Memberdayakan potensi lembaga dan Bumdes yang ada di Desa, untuk mendorong usaha ekonomi masyarakat.</p>

      <p class="text-3xl font-semibold my-4">Struktur Desa</p>
      <img src="@/assets/bagan.png" alt=""/>
    </div>
  </main>
</template>

<style>
  body{
    background: #f1f1f1;
  }
</style>
