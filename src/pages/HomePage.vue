<template>
    <div>
        <Navbar/>
        <BannerLarge/>
        <SectionTwo/>
        <CollectionsHF/>
        <SelectionProducts/>
        <PointOfSales/>
    </div>
</template>

<script>
import BannerLarge from "@/components/BannerLarge";
import Navbar from "@/components/Navbar.vue";
import SectionTwo from "@/components/SectionTwo.vue";
import CollectionsHF from "@/components/CollectionsHF.vue";
import SelectionProducts from "@/components/SelectionProducts.vue";
import PointOfSales from "@/components/PointOfSales.vue";

export default {
    name: 'HomePage',
    components: {
        BannerLarge,
        Navbar,
        SectionTwo,
        CollectionsHF,
        SelectionProducts,
        PointOfSales
        },
    mounted() {

    }
}

</script>

<style lang="scss">

</style>