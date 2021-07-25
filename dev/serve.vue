<script lang="ts">
import { defineComponent } from 'vue';
// Uncomment import and local "components" registration if library is not registered globally.
// import { VueGridLayoutSample } from '@/entry.esm';

export default defineComponent({
  name: 'ServeDev',
  // components: {
  //  VueGridLayoutSample,
  // }
});
</script>

<template>
  <div id="app">
    <vue-grid-layout-sample />
  </div>
</template>
