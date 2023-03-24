<script>
export default {
    data() {
        return {
            name: 'FooterMarchandise'
        }
    }
}

</script>
<template>
    <section>
        <div class="container">
            <ul>
                <li><img src="../assets/buy-comics-digital-comics.png" alt="logo">Digital Comics</li>
                <li><img src="../assets/buy-comics-digital-comics.png" alt="logo">Digital Comics</li>
                <li><img src="../assets/buy-comics-digital-comics.png" alt="logo">Digital Comics</li>
                <li><img src="../assets/buy-comics-digital-comics.png" alt="logo">Digital Comics</li>
                <li><img src="../assets/buy-comics-digital-comics.png" alt="logo">Digital Comics</li>
            </ul>
        </div>
    </section>
</template>
<style lang="scss" scoped >
section {
    background-color: #0282f9;

    .container{
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
        width: 60px;
        height: 50px;
        padding: 0 10px;
    }

}
</style>