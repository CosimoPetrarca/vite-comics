<script>
import FooterMerchandise from './FooterMerchandise.vue';
import FooterInfo from './FooterInfo.vue';
import FooterSocial from './FooterSocial.vue';

export default {
    data() {
        return {
            name: 'Footer'
        }
    },
    components: {
        FooterMerchandise,
        FooterInfo,
        FooterSocial
    }
}
</script>
<template>
    <FooterMerchandise />
    <FooterInfo />
    <FooterSocial />
</template>
<style lang="scss" scoped>
</style>