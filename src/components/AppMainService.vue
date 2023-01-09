<script>
</script>

<template>
    <section id="service">
        <div class="service-cards d-flex container-wrapped">
            <div class="single-card d-flex align-center">
                <img src="../assets/buy-comics-digital-comics.png" alt="Digital Comics">
                <h2>Digital Comics</h2>
            </div>
            <div class="single-card d-flex align-center">
                <img src="../assets/buy-comics-merchandise.png" alt="DC Merchandise">
                <h2>DC Merchandise</h2>
            </div>
            <div class="single-card d-flex align-center">
                <img src="../assets/buy-comics-subscriptions.png" alt="Subscription">
                <h2>Subscription</h2>
            </div>
            <div class="single-card d-flex align-center">
                <img src="../assets/buy-comics-shop-locator.png" alt="Shop Locator">
                <h2>Comic Shop Locator</h2>
            </div>
            <div class="single-card d-flex align-center">
                <img src="../assets/buy-dc-power-visa.svg" alt="DC Power Visa">
                <h2>DC Power Visa</h2>
            </div>
        </div>
    </section>
</template>

<style lang="scss">
@use '../styles/partials/variables.scss' as *;

section#service {
    background-color: $brand-color;
    padding: 2rem 0;
}

div.single-card {
    width: calc((100% / 5) - 1rem);
    padding: 0 .5rem;
    justify-content: center;



    img {
        width: 55px;
        height: 55px;
        object-fit: contain;
        margin-right: .5rem;
    }

    h2 {
        font-size: 1rem;
        color: white;
        text-transform: uppercase;
        font-weight: 300;
    }
}
</style>