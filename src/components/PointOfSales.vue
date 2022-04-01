<template>
    <section class="point-of-sales">
        <div class="container-fluid ">
            <div class="row  row-cols" >
                <div class="col-md-6 col-point-of-sales">
                    <div class="card bg-dark text-white img-store"></div>
                </div>
                <div class="col-md-6  col-point-of-sales">
                    <div class="card text-white bg-grey-light">                        
                        <div class="card-img-overlay d-flex align-items-center justify-content-center ">
                            <a class="btn btn-outline-primary dark mb-7 mb-md-0" href="#">
                                Découvrir
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'PointOfSales',
    mounted() {
    }
}
</script>

<style lang="scss">
</style>