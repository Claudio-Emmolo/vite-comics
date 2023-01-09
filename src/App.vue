<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';


export default {
  components: {
    AppHeader,
    AppMain
  }
}
</script>



<template>
  <!-- Import Header -->
  <AppHeader />

  <!-- Import Main -->
  <AppMain />


</template>



<style lang="scss">
@use './styles/general.scss' as *;

div.container-wrapped {
  width: 80%;
  border: 1px solid red;
  margin: 0 auto;
}
</style>
