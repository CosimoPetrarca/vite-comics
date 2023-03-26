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
        <div class="logo"><img src="../assets/dc-logo.png" alt="logo"></div>
        <div class="lista">
            <!-- lista header -->
            <ul>
                <li v-for="item in navbar"><a href="#">{{item}}</a></li>
            </ul>
        </div>
    </section>
</template>
<style lang="scss" scoped >
section {
    display: flex;
    align-items: center;
    justify-content: space-between;
    max-width: 1300px;
    margin: auto;

    img {
        padding: 10px 0;
        width: 80%;
    }

    .lista ul {
        display: flex;
        list-style: none;
    }

    .lista ul li {
        padding: 10px;
    }

    a {
        text-decoration: none;
        color: black;
        font-size: 17px;
    }

    a:hover {
        color: #0282f9;
        border-bottom: 3px solid #0282f9;
    }
    
}
</style>