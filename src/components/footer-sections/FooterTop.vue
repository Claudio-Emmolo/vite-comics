<script>
export default {
    data() {
        return {
            navItems: [
                {
                    text: 'Characters',
                    url: '#',
                    active: false
                },
                {
                    text: 'Comics',
                    url: '#',
                    active: true
                },
                {
                    text: 'Movies',
                    url: '#',
                    active: false
                },
                {
                    text: 'Tv',
                    url: '#',
                    active: false
                },
                {
                    text: 'Games',
                    url: '#',
                    active: false
                },
                {
                    text: 'Collectibles',
                    url: '#',
                    active: false
                },
                {
                    text: 'Videos',
                    url: '#',
                    active: false
                },
                {
                    text: 'Fans',
                    url: '#',
                    active: false
                },
                {
                    text: 'News',
                    url: '#',
                    active: false
                },
                {
                    text: 'Shop',
                    url: '#',
                    active: false
                },
            ]
        }
    }
}
</script>

<template>
    <section id="top-footer">
        <div class="container-wrapped d-flex flex-between">
            <div class="nav-info d-flex">

                <nav class="d-flex">
                    <div class="nav-wrap">
                        <div class="single-nav">
                            <h2>DC Comics</h2>
                            <ul>
                                <li>
                                    <a href="#">Characters</a>
                                </li>
                                <li>
                                    <a href="#">Comics</a>
                                </li>
                                <li>
                                    <a href="#">Movies</a>
                                </li>
                                <li>
                                    <a href="#">TV</a>
                                </li>
                                <li>
                                    <a href="#">Games</a>
                                </li>
                                <li>
                                    <a href="#">Videos</a>
                                </li>
                                <li>
                                    <a href="#">News</a>
                                </li>
                            </ul>
                        </div>

                        <div class="single-nav shop-nav">
                            <h2>Shop</h2>
                            <ul>
                                <li>
                                    <a href="#">Shop DC</a>
                                </li>
                                <li>
                                    <a href="#">Shop DC Collectibles</a>
                                </li>

                            </ul>
                        </div>
                    </div>

                    <div class="single-nav">
                        <h2>DC</h2>
                        <ul>
                            <li>
                                <a href="#">Term Of Use</a>
                            </li>
                            <li>
                                <a href="#">Privacy policy (New)</a>
                            </li>
                            <li>
                                <a href="#">Ad Choices</a>
                            </li>
                            <li>
                                <a href="#">Advertising</a>
                            </li>
                            <li>
                                <a href="#">Jobs</a>
                            </li>
                            <li>
                                <a href="#">Subscriptions</a>
                            </li>
                            <li>
                                <a href="#">Talent Workshop</a>
                            </li>
                            <li>
                                <a href="#">CPSC Certificates</a>
                            </li>
                            <li>
                                <a href="#">Rating</a>
                            </li>
                            <li>
                                <a href="#">Shop Help</a>
                            </li>
                            <li>
                                <a href="#">Contact US</a>
                            </li>
                        </ul>
                    </div>

                    <div class="single-nav">
                        <h2>Sites</h2>
                        <ul>
                            <li>
                                <a href="#">DC</a>
                            </li>
                            <li>
                                <a href="#">MAD Magazine</a>
                            </li>
                            <li>
                                <a href="#">DC Kids</a>
                            </li>
                            <li>
                                <a href="#">DC Universe</a>
                            </li>
                            <li>
                                <a href="#">DC Power Visa</a>
                            </li>
                        </ul>
                    </div>
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
    background-image: url(../../assets/footer-bg.jpg);
    background-size: cover;
    background-repeat: no-repeat;
}

div.nav-info {
    padding: 2rem 0;
}

div.single-nav {
    margin-right: 2rem;
    width: max-content;

    h2 {
        font-weight: bold;
        font-size: 1.5rem;
        margin-bottom: .5rem;
        color: white;
        text-transform: uppercase;
    }

    ul li {
        list-style-type: none;
        margin: .15rem 0;

        a {
            text-decoration: none;
            color: white;
            font-weight: 300;
            font-size: .8rem;
            filter: opacity(.6);

            &:hover {
                filter: opacity(1);
            }
        }
    }

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