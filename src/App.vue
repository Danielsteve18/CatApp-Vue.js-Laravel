
<template>
  <Nav></Nav>
  <br>
    <br>
      <br>
  <div class="view-general">
    <br>
      <br>
        <br>
  <SectionOne ></SectionOne>
    <br>
      <br>
        <br>
  <SectionTwo id="ip-gatunas"></SectionTwo>
    <br>
      <br>
  <SectionThree id="siesta-felina" ></SectionThree>
  <br>
    <br>
      <br>

  <sectionFour id="codigo-felino"></sectionFour>    
  </div>

</template>

<script setup>
import Nav from './components/01-navHomePrincipal/navH_P.vue';
import SectionOne from './components/02-sectionOne/sectionOne.vue';
import SectionTwo from './components/03-ip_gatunas/ipGatunas.vue';
import SectionThree from './components/04-siesta_felina/siestaFelina.vue';
import sectionFour from './components/05-codigo_felino/codigoFelino.vue';
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
