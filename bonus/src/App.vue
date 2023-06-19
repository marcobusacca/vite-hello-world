<!-- SCRIPT JS -->
<script>
  // IMPORTO LA COMPONENTE APP TITLE
  import AppTitle from './components/AppTitle.vue';

  // IMPORTO LA COMPONENTE APP HERO
  import AppHero from './components/AppHero.vue';

  export default {
    // COMPONENTI
    components:{
      // DICHIARO LA COMPONENTE APP TITLE
      AppTitle,
      // DICHIARO LA COMPONENTE APP HERO
      AppHero,
    }
  }
</script>

<!-- TEMPLATE HTML -->
<template lang="">
  <div>
    <!-- USO LA COMPONENTE APP TITLE IN HTML -->
    <AppTitle/>
    <!-- USO LA COMPONENTE APP HERO IN HTML -->
    <AppHero/>
  </div>
</template>

<!-- STYLE CSS -->
<style scoped lang="">
  
</style>