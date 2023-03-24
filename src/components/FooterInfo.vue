<script>
export default {
    data() {
        return {
            name: 'FooterInfo'
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
                        <li>Comics</li>
                        <li>Comics</li>
                        <li>Comics</li>
                        <li>Comics</li>
                        <li>Comics</li>
                        <li>Comics</li>
                        <li>Comics</li>
                    </ul>

                    <h4 class="uno">SHOP</h4>
                    <ul>
                        <li>Shop</li>
                        <li>Shop</li>
                    </ul>
                </div>

                <div>
                    <h4>DC</h4>
                    <ul>
                        <li>Jobs</li>
                        <li>Jobs</li>
                        <li>Jobs</li>
                        <li>Jobs</li>
                        <li>Jobs</li>
                        <li>Jobs</li>
                        <li>Jobs</li>
                        <li>Jobs</li>
                        <li>Jobs</li>
                        <li>Jobs</li>
                        <li>Jobs</li>
                    </ul>
                </div>
                <div>
                    <h4>SITIES</h4>
                    <ul>
                        <li>Kids</li>
                        <li>Kids</li>
                        <li>Kids</li>
                        <li>Kids</li>
                        <li>Kids</li>
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
        width: 50%;
    }

    h4 {
        color: white;
        padding-bottom: 20px;
    }

    ul {
        list-style: none;
        color: gray;
    }

    .uno {
        padding-top: 20px;
    }

}
</style>