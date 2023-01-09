<script>

</script>

<template>
    <section id="top-footer">
        <div class="container-wrapped d-flex flex-between">
            <div class="nav-info d-flex">

                <!-- DC Comics and Shop NAV -->
                <nav>
                    <h2>DC Comics</h2>
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
                        <li>
                            <a href="#">Item</a>
                        </li>
                        <li>
                            <a href="#">Item</a>
                        </li>
                    </ul>

                    <div class="shop-nav">
                        <h2>Shop</h2>
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
                        </ul>
                    </div>
                </nav>

                <!-- DC Nav -->
                <nav>
                    <h2>DC</h2>
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
                        <li>
                            <a href="#">Item</a>
                        </li>
                    </ul>
                </nav>

                <!-- Sites Nav -->
                <nav>
                    <h2>Sites</h2>
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
            </div>

            <div class="dc-bg-img">
                <img src="../../assets/dc-logo-bg.png" alt="Dc Bg Logo">
            </div>
        </div>
    </section>
</template>


<style lang="scss" scoped>
section#top-footer {
    padding: 1rem;
    background-color: rgb(102, 89, 89);
}

h2 {
    margin-bottom: .5rem;
}

div.shop-nav {
    margin-top: 1.5rem;
}

div.nav-info nav {
    padding: 0 1rem;
}

div.dc-bg-img {
    width: 100%;
    position: relative;
    overflow: hidden;

    img {
        height: 150%;
        position: absolute;
        top: 50%;
        right: 0;
        transform: translateY(-50%);
    }
}
</style>