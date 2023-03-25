<script>
export default {
    data() {
        return {
            name: 'Main'
        }
    }
}
</script>
<template>
    <section>
        <div class="container">
    
        </div>
    </section>
</template>
<style lang="scss" scoped >
section {
    background-image: url(../assets/jumbotron.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    height: 400px;
    

    .container{
        max-width: 1300px;
        margin: auto;
    }


    .container h2 {
        color: white;
    }
}
</style>