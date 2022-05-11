<template>
  <div>
    <Header></Header>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import Header from './components/Header.vue'

export default defineComponent({
    components: { Header }
})
</script>

<style >
  @import url('https://fonts.googleapis.com/css2?family=Source+Sans+Pro:wght@300&display=swap');

  * {
    margin: 0;
    padding: 0;
    font-family: 'Source Sans Pro', sans-serif;
  }
</style>