<script>
export default {
    data() {
        return {
            name: 'FooterSocial',
            socials: [
                {
                    social: 'Facebook',
                    image: 'src/assets/footer-facebook.png',
                },
                {
                    social: 'Twitter',
                    image: 'src/assets/footer-twitter.png',
                },
                {
                    social: 'YouTube',
                    image: 'src/assets/footer-youtube.png',
                },
                {
                    social: 'Pinterest',
                    image: 'src/assets/footer-pinterest.png',
                },
                {
                    social: 'Periscope',
                    image: 'src/assets/footer-periscope.png',
                }
            ]
        }
    }
}
</script>
<template>
    <section>
        <div class="container">
            <div class="btn">
                <button>Sign-Up Now!</button>
            </div>
            <div class="social">
                <h4>FOLLOW US</h4>
                <ul v-for="social in socials">
                    <li><img :src= social.image></li>
                   
                </ul>
            </div>
        </div>
    </section>
</template>
<style lang="scss" scoped >
section {
    background-color: #303030;
    position: relative;

    .container{
        display: flex;
        max-width: 1300px;
        margin: auto;
        padding: 30px 0;
    }


    button {
        padding: 10px;
        border: 2px solid #0282f9;
        background-color: #303030;
        color: white;
        font-size: 20px;
        cursor: pointer;
    }

    .btn,
    .social {
        width: 50%;
    }

    .social {
        display: flex;
        justify-content: end;
        align-items: center;
    }

    .social h4 {
        color: #0282f9;
        font-size: 20px;
    }

    .social ul {
        display: flex;
        list-style: none;
        padding-left: 15px;
    }

    .social ul li {
        padding-right: 20px;
        color: grey;
    }
}
</style>