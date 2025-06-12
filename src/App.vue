
<template>
<div class="view-general">
  <RouterView>

  </RouterView>
</div>
</template>

<script setup>
 
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
