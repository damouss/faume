<template>
    <section class="selection-products py-5">
        <div class="container-fluid py-5 overflow-hidden">
            <h2 class="min-h2 mb-5">Notre sélection</h2>
            <div class="hscroll">
                <div class="row ">
                    <div class="col col-md-3">
                        <div class="card">
                                <img src="../assets/images/product1.jpeg" class="card-img-top" alt="produit 1">
                            <div class="card-body">
                                <p class="title-product mb-0">T-shirt Homme</p>
                                <p class="price-product mb-0">70,00 €</p>
                            </div>
                        </div>
                    </div>
                    <div class=" col  col-md-3">
                        <div class="card">
                            <img  src="../assets/images/product2.jpeg" class="card-img-top" alt="produit 2">
                            <div class="card-body">
                                <p class="title-product mb-0">Veste cuire</p>
                                <p class="price-product mb-0">170,00 €</p>
                            </div>
                        </div>
                    </div>
                    <div class=" col  col-md-3">
                        <div class="card">
                            <img  src="../assets/images/product3.jpeg" class="card-img-top" alt="produit 3">
                            <div class="card-body">
                                <p class="title-product mb-0">Trench Homme</p>
                                <p class="price-product mb-0">250,00 €</p>
                            </div>
                        </div>
                    </div>
                    <div class=" col  col-md-3">
                        <div class="card">
                            <img  src="../assets/images/product4.jpeg" class="card-img-top" alt="produit 4">
                            <div class="card-body">
                                <p class="title-product mb-0">Sac cuire</p>
                                <p class="price-product mb-0">360,00 €</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'SelectionProducts',
    mounted() {
    }
}
</script>

<style lang="scss">
</style>