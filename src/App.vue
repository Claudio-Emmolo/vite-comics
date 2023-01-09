<script>
import AppHeader from './components/AppHeader.vue';

export default {
  components: {
    AppHeader,
  }
}
</script>



<template>
  <div class="container-wrapped">
    <!-- Import Header -->
    <AppHeader />


    <!-- Import Main -->


  </div>
</template>



<style lang="scss">
@use './styles/general.scss' as *;

div.container-wrapped {
  width: 80%;
  border: 1px solid red;
  margin: 0 auto;
}
</style>
