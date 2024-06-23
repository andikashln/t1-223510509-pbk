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
    <template #heading>PENDIDIKAN</template>
    PENDIDIKAN YANG DITEMPUH<br> SD 21 PEKANBARU<br> MTSN 3 PEKANBARU <br> SMA 14 PEKANBARU
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>OLAHRAGA</template>
    Futsal
    <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>GAMES</template>
    Games Favorite untuk saat ini,<br> 1.Mobile legends<br> 2.Gta 5 <br> 3.PUBG
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>MEDIA SOSIAL</template>
    -Instagram : @andikashln<br> -Tiktok : @dika<br>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>DATA DIRI</template>
    1.NAMA : Andika Shalihin<br> 2.UMUR : 20<br> 3.KULIAH : Universitas Islam Riau<br> 4.JENIS KELAMIN : LAKI-LAKI
    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener"></a>
  </WelcomeItem>
</template>
