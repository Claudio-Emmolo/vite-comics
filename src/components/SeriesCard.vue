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
            <div class="hover-thumb d-flex">
                <div class="hover-content">
                    <span>{{ srPrice }}</span>
                    <span>{{ srType }} </span>
                </div>
            </div>
            <img :src="srThumb" :alt="srSeries">
        </div>
        <h4>{{ srSeries }}</h4>
    </article>
</template>


<style lang="scss">
article {
    width: calc((100% / 6) - 1rem);
    margin: 1rem .5rem;

    div.thum-container {
        width: 200px;
        height: 200px;
        overflow: hidden;
        margin-bottom: 1.2rem;
        position: relative;

        img {
            display: block;
            width: 100%;
        }

        div.hover-thumb {
            position: absolute;
            top: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.664);
            display: none;

            div.hover-content {
                margin: auto;

                span {
                    text-align: center;
                    display: block;
                    text-transform: uppercase;
                    margin: .5rem 0;
                }
            }

        }

        &:hover div.hover-thumb {
            display: flex;
        }
    }

    h4 {
        text-transform: uppercase;
        margin-bottom: .8rem;
        font-weight: 200;
    }



}
</style>