<script>
import FooterTop from '../components/footer-sections/FooterTop.vue'
import FooterBottom from '../components/footer-sections/FooterBottom.vue'


export default {
    components: {
        FooterTop,
        FooterBottom
    }
}
</script>

<template>
    <footer>
        <!-- Import Top Footer Section -->
        <FooterTop />
        <FooterBottom />

    </footer>
</template>


<style lang="scss" scoped>

</style>