<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';



export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter
  }
}
</script>



<template>
  <!-- Import Header -->
  <AppHeader />

  <!-- Import Main -->
  <AppMain />

  <!-- Import Footer -->
  <AppFooter />


</template>



<style lang="scss">
@use './styles/general.scss' as *;
@use './styles/partials/variables.scss' as *;


div.container-wrapped {
  width: 80%;
  margin: 0 auto;
}

.d-flex {
  display: flex;
}

.flex-between {
  justify-content: space-between;
}

.align-center {
  align-items: center;
}
</style>
