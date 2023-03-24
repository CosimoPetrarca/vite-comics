<script>
export default {
    data() {
        return {
            name: 'FooterSocial'
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
                <ul>
                    <li>Social</li>
                    <li>Social</li>
                    <li>Social</li>
                    <li>Social</li>
                    <li>Social</li>
                </ul>
            </div>
        </div>
    </section>
</template>
<style lang="scss" scoped >
section {
    background-color: #303030;

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