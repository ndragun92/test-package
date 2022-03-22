<script lang="ts">
import Vue from 'vue';
// Uncomment import and local "components" registration if library is not registered globally.
// import { CadenzaDemoSample } from '@/entry.esm';

export default Vue.extend({
  name: 'ServeDev',
  // components: {
  //  CadenzaDemoSample,
  // }
});
</script>

<template>
  <div id="app">
    <cadenza-demo-sample />
    <cadenza-demo-button />
  </div>
</template>
