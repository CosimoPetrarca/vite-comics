<script>
export default {
    data() {
        return {
            name: 'FooterMarchandise',
            icons: [
                {
                    text: "DIGITAL COMICS",
                    img: "src/assets/buy_1.png"

                },
                {
                    text: "DC MERCHANDISE",
                    img: "src/assets/buy-comics-merchandise.png"

                },
                {
                    text: "SUBSCRIPTION",
                    img: "src/assets/buy-comics-subscriptions.png"

                },
                {
                    text: "COMIC SHOP LOCATOR",
                    img: "src/assets/buy-comics-shop-locator.png"

                },
                {
                    text: "DC POWER VISA",
                    img: "src/assets/buy-dc-power-visa.svg"

                }
            ]
        }
    }
}
    

</script>
<template>
    <section>
        <div class="container">
            <ul>
                <li v-for="icon in icons"><img :src= icon.img>{{ icon.text }}</li>
            </ul>
        </div>
    </section>
</template>
<style lang="scss" scoped >
section {
    background-color: #0282f9;

    .container {
        max-width: 1300px;
        margin: auto;
    }

    .container ul {
        display: flex;
        justify-content: space-between;
        padding: 0 30px;
    }

    .container ul li {
        display: flex;
        align-items: center;
        list-style: none;
        padding: 50px 10px;
        color: white;
    }

    img {
        color: white;
        padding: 0 10px;
        width: 60px;
        height: 50px;
    }

}
</style>