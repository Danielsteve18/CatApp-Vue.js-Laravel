
<template>
  <Nav></Nav>
  <div class="view-general">
  <SectionOne></SectionOne>
  <br>
  <br>
  <SectionTwo></SectionTwo>
  </div>

</template>

<script setup>
import Nav from './components/navHomePrincipal/navH_P.vue';
import SectionOne from './components/sectionOne/sectionOne.vue';
import SectionTwo from './components/ip_gatunas/ipGatunas.vue';
</script>

<style scoped>

 
  .view-general {
  max-height: 100vh;
  overflow-y: auto;
}
:global(::-webkit-scrollbar) {
  width: 0px;
  background: rgb(17, 17, 17);
}

:global(::-webkit-scrollbar-thumb) {
  background: rgb(20, 20, 20);
}

</style>
