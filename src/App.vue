<template>
  <div id="app">
    <BarraNavegacao />
    <router-view />
  </div>
</template>

<script>
import BarraNavegacao from '../src/components/BarraNavegacao.vue';

export default {
  components: {
    BarraNavegacao
  }
}
</script>