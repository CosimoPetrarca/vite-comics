<script>
export default {
    data() {
        return {
            name: 'FooterInfo',
            comics: [
                "Characters",
                "Comics",
                "Movies",
                "TV",
                "Games",
                "Videos",
                "News"
            ],
            shop: [
                "Shop DC",
                "Shop DC Collectibles"
            ],
            dc: [
                "Terms Of Use",
                "Privacy policy (New)",
                "Ad Choices",
                "Advertising",
                "Jobs",
                "Subscriptions",
                "Talent Workshops",
                "CPSC Certificates",
                "Ratings",
                "Shop Help",
                "Contact Us"
            ],
            sites: [
                "DC",
                "MAD Magazine",
                "DC Kids",
                "DC Universe",
                "DC Power Visa"
            ]
        }
    }
}
</script>
<template>
    <!-- info -->
    <section>
        <div class="container">
            <div class="info">
                <div>
                    <h4>DC COMICS</h4>
                    <ul>
                        <li v-for="comic in comics"><a href="#">{{ comic }}</a></li>
                    </ul>

                    <h4 class="uno">SHOP</h4>
                    <ul>
                        <li v-for="shop in shop"><a href="#">{{ shop }}</a></li>
                    </ul>
                </div>

                <div>
                    <h4>DC</h4>
                    <ul>
                        <li v-for="dc in dc"><a href="#">{{ dc }}</a></li>
                    </ul>
                </div>
                <div>
                    <h4>SITIES</h4>
                    <ul>
                        <li v-for="site in sites"><a href="#">{{ site }}</a></li>
                    </ul>
                </div>
            </div>

            <div class="logo"><img src="../assets/dc-logo-bg.png" alt=""></div>
        </div>
    </section>
    <!-- /info -->

    <!-- logo -->
</template>
<style lang="scss" scoped >
section {
    background-image: url(../assets/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;

    .container {
        display: flex;
        max-width: 1300px;
        margin: auto;
        position: relative;
    }

    .info {
        width: 50%;
        display: flex;
        padding: 40px 0;
    }

    .info div {
        padding-right: 60px;
    }

    .logo {
        display: flex;
        justify-content: end;
        position: absolute;
        right: 0;
        bottom: 0;
        transform: translateY(+10%);
    }

    h4 {
        color: white;
        padding-bottom: 20px;
    }

    li {
        list-style: none;
        padding-bottom: 5px;
    }

    a {
        color: #959595;
        text-decoration: none;
    }

    a:hover {
        color: #0282f9;
    }

    .uno {
        padding-top: 20px;
    }


}
</style>