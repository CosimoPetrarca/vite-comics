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
    </section>
    <!-- /info -->

    <!-- logo -->
</template>
<style lang="scss" scoped >
section {
    background-image: url(../assets/footer-bg.jpg);
    display: flex;
    width: 100%;

    .info {
        width: 40%;
        display: flex;
        justify-content: center;
        padding: 40px 0;
    }

    .info div{
        padding-right: 60px;
    }

    .logo {
        width: 60px;
    }

    h4{
        color: white;
        padding-bottom: 20px;
    }

    ul{
        list-style: none;
        color: gray;
    }

    .uno{
        padding-top: 20px;
    }

}
</style>