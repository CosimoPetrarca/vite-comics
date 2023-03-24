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
            <h2>Content goes here</h2>
        </div>
    </section>
</template>
<style lang="scss" scoped >
section {
    background-color: #1c1c1c;
    height: 130px; //debug

    .container{
        max-width: 1300px;
        margin: auto;
    }


    .container h2 {
        color: white;
    }
}
</style>