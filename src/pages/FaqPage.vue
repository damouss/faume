<template>
    <div>
        <Navbar/>
        <ContentFaq/>
        <FooterSmall/>
    </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue";
import FooterSmall from "@/components/FooterSmall.vue";
import ContentFaq from "@/components/ContentFaq.vue";

export default {
    name: 'FaqPage',
    components: {      
        Navbar,    
        ContentFaq,   
        FooterSmall
        },
    mounted() {

    }
}

</script>

<style lang="scss">

</style>