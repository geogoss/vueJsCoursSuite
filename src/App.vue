<template>
  <div>
    <h1 class="m-5 text-danger">Bonjour</h1>
    <contenu></contenu>
  </div>
</template>

<script>

import Contenu from './components/Contenu/Contenu-formation-1.vue'


export default {
  name: 'App',
  components: {
    'contenu': Contenu
  }
}
</script>

<style scoped>

</style>
