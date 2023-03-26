<script>
export default {

    data() {
        return {
            name: 'Header',
            navbar: [
                'Characters',
                'Comics',
                'Movies',
                'TV',
                'Games',
                'Collectibles',
                'Videos',
                'Fans',
                'News',
                'Shop'
            ]
        }
    }
}
</script>
<template>
    <!-- logo -->
    <section>
        <div class="container">
            <div class="logo"><img src="../assets/dc-logo.png" alt="logo"></div>
            <div class="lista">
                <!-- lista header -->
                <ul>
                    <li v-for="item in navbar"><strong><a href="#">{{ item }}</a></strong></li>
                </ul>
            </div>
        </div>
    </section>
</template>
<style lang="scss" scoped >
section {
    position: fixed;
    left: 0;
    top: 0;
    right: 0;
    z-index: 20;
    background-color: white;

    .container {
        display: flex;
        align-items: center;
        justify-content: space-between;
        max-width: 1300px;
        margin: auto;
    }

    img {
        padding: 10px 0;
        width: 80%;
    }

    .lista ul {
        display: flex;
        list-style: none;
    }

    .lista ul li {
        padding: 15px;
    }

    a {
        text-decoration: none;
        color: #464646;
        font-size: 15px;
        padding-bottom: 40px;
        text-transform: uppercase;
    }

    a:hover {
        color: #0282f9;
        border-bottom: 3px solid #0282f9;
    }
}
</style>