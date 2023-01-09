<script>
export default {

}
</script>

<template>
    <header>

        <img src="../assets/dc-logo.png" alt="DC Main Logo">

        <nav>
            <ul>
                <li>
                    <a href="#">Item</a>
                </li>
                <li>
                    <a href="#">Item</a>
                </li>
                <li>
                    <a href="#">Item</a>
                </li>
                <li>
                    <a href="#">Item</a>
                </li>
                <li>
                    <a href="#">Item</a>
                </li>
            </ul>
        </nav>

    </header>
</template>

<style lang="scss">
header {
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: .5rem;
}

img {
    height: 80%;
}

nav ul li {
    display: inline;
    padding: 0 1rem;
}
</style>