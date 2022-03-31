<template>
    <div>
        <Navbar/>
        <BannerLarge/>
        <SectionTwo/>
        <CollectionsHF/>
        <SelectionProducts/>
        <PointOfSales/>
        <FooterSmall/>
    </div>
</template>

<script>
import BannerLarge from "@/components/BannerLarge";
import Navbar from "@/components/Navbar.vue";
import SectionTwo from "@/components/SectionTwo.vue";
import CollectionsHF from "@/components/CollectionsHF.vue";
import SelectionProducts from "@/components/SelectionProducts.vue";
import PointOfSales from "@/components/PointOfSales.vue";
import FooterSmall from "@/components/FooterSmall.vue"

export default {
    name: 'HomePage',
    components: {
        BannerLarge,
        Navbar,
        SectionTwo,
        CollectionsHF,
        SelectionProducts,
        PointOfSales,
        FooterSmall
        },
    mounted() {

    }
}

</script>

<style lang="scss">

</style>