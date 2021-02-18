<template>
  <div>
    <CatalogCategories />
    <CatalogList />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import booksMock from '../../assets/json/books.json';
import gpusMock from '../../assets/json/gpus.json';
export default Vue.extend({
  name: 'CatalogMain',

})
</script>

<style scoped>
</style>
