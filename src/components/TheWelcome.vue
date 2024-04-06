<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Latar Pendidikan</template>

    Saya merupakan mahasiswa semester IV di Universitas Islam Riau, sebelumnya saya pernah bersekolah di SMKN 1 Pekanbaru, MTsN 1 Andalan Pekanbaru, dan SD Al Azhar Syifa Budi Pekanbaru.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Pengalaman dan Keahlian</template>

    Saya pernah melakukan Praktek Kerja Lapangan di Retyan Computer dan mendapatkan banyak sekali pelajaran seperti merakit pc customer, install ulang, instalasi CCTV dan masih banyak lagi.
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Karya</template>

    Pada mata kuliah Rekayasa Perangkat Lunak, saya dan teman sekelompok saya membuat NUSACO yang merupakan marketplace jual beli ekspor impor, berkat prototype ini kami menjadi kelompok terbaik.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Sertifikasi</template>

    Saya pernah mengambil beberapa sertifikasi pada website belajar seperti Dicoding, Myskill.id, Progate Indonesia, SejutaCita.id, dan masih banyak lagi.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Kontak</template>

   Hubungi saya melalui:<br>
   <li>Email: alifadityaforwork@gmail.com</li>
   <li>Instagram: @aalifadityaa</li>
   <li>Facebook: Alif Aditya</li>
  </WelcomeItem>
</template>
