<script>
export default {
    data() {
        return {
            name: 'Header'
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
                <li><a href="#">Character</a></li>
                <li><a href="#">Character</a></li>
                <li><a href="#">Character</a></li>
                <li><a href="#">Character</a></li>
                <li><a href="#">Character</a></li>
                <li><a href="#">Character</a></li>
                <li><a href="#">Character</a></li>
                <li><a href="#">Character</a></li>
                <li><a href="#">Character</a></li>
                <li><a href="#">Character</a></li>
            </ul>
        </div>
    </section>
</template>
<style lang="scss" scoped >
section{
    display: flex;
    align-items: center;
    width: 100%;

    img{
        padding: 10px 0;
    }
    
    .logo{
        width: 40%;
        display: flex;
        justify-content: center;
    }

    .lista{
        width: 60%;
    }

    .lista ul{
        display: flex;
        list-style: none;

    }

    .lista ul li{
        padding: 10px;
    }

    a{
        text-decoration: none;
        color: black;
        font-size: 17px;
    }

    a:hover{
        color: blue;
    }
}
</style>