<script>
import CardElement from './CardElement.vue';
export default {
    nome: 'Main',
    components: {
        CardElement
    },
    data() {
        return {
            locandine: [
                {
                    "thumb": "https://www.panini.it/media/catalog/product/cache/dcdcea88706ab1684584701c5b27598d/M/1/M1HCIN068ISBN_0.jpg",
                    "series": "BLACK ADAM",
                },
                {
                    "thumb": "https://www.panini.it/media/catalog/product/cache/dcdcea88706ab1684584701c5b27598d/M/1/M1FLAS032ISBN_0.jpg",
                    "series": "THE FLASH",
                },
                {
                    "thumb": "https://static.dc.com/dc/files/default_images/teentitansgo_s1_thumb_192x291_52abc1c8962e81.49398578.jpg?w=192",
                    "series": "TEEN TITANS GO!",
                },
                {
                    "thumb": "https://www.panini.it/media/catalog/product/cache/dcdcea88706ab1684584701c5b27598d/M/1/M1DLUX023ISBN_0.jpg",
                    "series": "AQUAMAN: LE CRONACHE DI ATLANTIDE",
                },
                {
                    "thumb": "https://www.panini.it/media/catalog/product/cache/dcdcea88706ab1684584701c5b27598d/M/1/M1HCIN061ISBN_0.jpg",
                    "series": "SUICIDE SQUAD",
                },
                {
                    "thumb": "https://www.panini.it/media/catalog/product/cache/dcdcea88706ab1684584701c5b27598d/m/1/m1dceg019isbn_0.jpg",
                    "series": "LANTERNA VERDE",
                },
                {
                    "thumb": "https://www.panini.it/media/catalog/product/cache/dcdcea88706ab1684584701c5b27598d/M/1/M1DCEG050ISBN_0.jpg",
                    "series": "CATWOMAN",
                },
                {
                    "thumb": "https://www.panini.it/media/catalog/product/cache/dcdcea88706ab1684584701c5b27598d/M/1/M1REHC042ISBN_0.jpg",
                    "series": "SUPERMAN",
                },
                {
                    "thumb": "https://www.panini.it/media/catalog/product/cache/dcdcea88706ab1684584701c5b27598d/M/1/M1VEMH057ISBN_0.jpg",
                    "series": "LUCIFER: INFERNO ",
                },
                {
                    "thumb": "https://www.panini.it/media/catalog/product/cache/dcdcea88706ab1684584701c5b27598d/M/1/M1ANNI009ISBN_0.jpg",
                    "series": "HARLEY QUINN ",
                },
                {
                    "thumb": "https://www.panini.it/media/catalog/product/cache/dcdcea88706ab1684584701c5b27598d/m/1/m1batm068isbnv1_0.jpg",
                    "series": "BATMAN",

                },
                {
                    "thumb": "https://www.panini.it/media/catalog/product/cache/dcdcea88706ab1684584701c5b27598d/M/1/M1HCIN064ISBN_0.jpg",
                    "series": "WONDER WOMAN",
                }
            ]
        }
    }
}
</script>
<template>
    <div class="jumbo">
    </div>
    <section>
        <div class="btn-top">
            <button><h3>CURRENT SERIES</h3></button>
        </div>
        <div class="locandine">
            <CardElement v-for="(locandina, index) in locandine" :key="index" :img="locandina.thumb"
                :title="locandina.series">
            </CardElement>
        </div>
        <div class="btn-bottom">
            <button>LOAD MORE</button>
        </div>


    </section>
</template>
<style lang="scss" scoped >
.jumbo {
    background-image: url(../assets/jumbotron.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    height: 400px;
    position: relative;
}

section {
    background-color: #1c1c1c;
    position: relative;


    .locandine {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-around;
        max-width: 1300px;
        margin: auto;
        padding: 50px 0;
    }

    .btn-bottom {
        padding: 20px;
    }

    .btn-top {
        position: absolute;
        left: 300px;
        top: -20px;
    }

    button {
        display: flex;
        margin: auto;
        padding: 10px 50px;
        background-color: #0282f9;
        border: none;
        color: white;
        font-size: 15px;
        cursor: pointer;
        transition: all 0.3s ease-out;
    }

    button:hover {
        transform: scale(1.1);
    }


}
</style>