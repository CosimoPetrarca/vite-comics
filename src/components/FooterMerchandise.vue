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
    <div>
        <ul>
            <li>Digital Comics<img src="../assets/buy-comics-digital-comics.png" alt="logo"></li>
            <li>Digital Comics<img src="../assets/buy-comics-digital-comics.png" alt="logo"></li>
            <li>Digital Comics<img src="../assets/buy-comics-digital-comics.png" alt="logo"></li>
            <li>Digital Comics<img src="../assets/buy-comics-digital-comics.png" alt="logo"></li>
            <li>Digital Comics<img src="../assets/buy-comics-digital-comics.png" alt="logo"></li>

        </ul>
    </div>
</template>
<style lang="scss" scoped >
div {
    background-color: #0282f9;

    div ul {
        display: flex;
        justify-content: center;
    }

    div li {
        display: flex;
        align-items: center;
        list-style: none;
        padding: 50px 10px;
        color: white;
    }

    img {
        color: white;
        width: 50px;
        height: 50px;
        padding: 0 10px;
    }

}
</style>