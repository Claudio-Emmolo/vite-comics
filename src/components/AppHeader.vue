<script>
export default {
    data() {
        return {
            navItems: [
                {
                    text: 'characters',
                    url: '#',
                    active: false
                },
                {
                    text: 'comics',
                    url: '#',
                    active: true
                },
                {
                    text: 'movies',
                    url: '#',
                    active: false
                },
                {
                    text: 'tv',
                    url: '#',
                    active: false
                },
                {
                    text: 'games',
                    url: '#',
                    active: false
                },
                {
                    text: 'collectibles',
                    url: '#',
                    active: false
                },
                {
                    text: 'videos',
                    url: '#',
                    active: false
                },
                {
                    text: 'fans',
                    url: '#',
                    active: false
                },
                {
                    text: 'news',
                    url: '#',
                    active: false
                },
                {
                    text: 'shop',
                    url: '#',
                    active: false
                },
            ]
        }
    }
}
</script>

<template>
    <header>

        <div class="container-wrapped d-flex flex-between align-center">
            <img src="../assets/dc-logo.png" alt="DC Main Logo">

            <nav>
                <ul>
                    <li v-for="item in navItems" class="active">
                        <a :href="item.url">{{ item.text }}</a>
                    </li>
                </ul>
            </nav>
        </div>

    </header>
</template>

<style lang="scss" scoped>
header {
    width: 100%;
    padding: .5rem;
}

img {
    height: 80%;
}

nav ul li {
    height: 100%;
    display: inline-block;
    padding: 0 1rem;

    a {
        text-decoration: none;
        text-transform: uppercase;
        font-weight: 700;
        font-size: .9rem;
        color: black;
    }

}

.active a {
    color: blue;
    border-bottom: 3px solid blue;
}
</style>