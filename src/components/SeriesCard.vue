<script>
export default {
    props: [
        'srThumb', 'srPrice', 'srSeries', 'srType'
    ]
}
</script>

<template>
    <article class="series-card">
        <div class="thum-container">
            <img :src="srThumb" alt="">
        </div>
        {{ srSeries }}
    </article>
</template>


<style lang="scss">
article {
    width: calc((100% / 6) - 1rem);
    margin: 1rem .5rem;

    div.thum-container {
        width: 100%;

        img {
            display: block;
            width: 100%;
        }
    }

}
</style>