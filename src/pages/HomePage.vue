<template>
    <div>
        <Navbar/>
        <BannerLarge/>
        <SectionTwo/>
        <CollectionsHF/>
    </div>
</template>

<script>
import BannerLarge from "@/components/BannerLarge";
import Navbar from "@/components/Navbar.vue";
import SectionTwo from "@/components/SectionTwo.vue";
import CollectionsHF from "@/components/CollectionsHF.vue";
export default {
    name: 'HomePage',
    components: {
        BannerLarge,
        Navbar,
        SectionTwo,
        CollectionsHF
        },
    mounted() {

    }
}

</script>

<style lang="scss">

</style>