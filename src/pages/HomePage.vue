<template>
    <div>
        <Navbar/>
        <BannerLarge/>
    </div>
</template>

<script>
import BannerLarge from "@/components/BannerLarge";
import Navbar from "@/components/Navbar.vue";

export default {
    name: 'HomePage',
    components: {
        BannerLarge,
        Navbar
        },
    mounted() {

    }
}

</script>

<style lang="scss">

</style>