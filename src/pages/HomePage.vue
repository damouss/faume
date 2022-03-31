<template>
    <div>
        <Navbar/>
        <BannerLarge/>
        <SectionTwo/>
    </div>
</template>

<script>
import BannerLarge from "@/components/BannerLarge";
import Navbar from "@/components/Navbar.vue";
import SectionTwo from "@/components/SectionTwo.vue"

export default {
    name: 'HomePage',
    components: {
        BannerLarge,
        Navbar,
        SectionTwo
        },
    mounted() {

    }
}

</script>

<style lang="scss">

</style>