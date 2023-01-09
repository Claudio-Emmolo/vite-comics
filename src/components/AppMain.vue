<script>
import MainService from './AppMainService.vue'

export default {
    components: {
        MainService
    }
}
</script>

<template>
    <main>

        <section id="jumbotron">
            <div class="container-wrapped">
                <h2> __> Content Here {{ '<__' }} </h2>
            </div>
        </section>
        <!-- Import service section -->
        <MainService />
    </main>
</template>


<style lang="scss" scoped>
section#jumbotron {
    background-color: black;
    color: white;
    padding: 2rem;
}
</style>