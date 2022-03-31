<template>
    <nav id="navbar_top" class="navbar navbar-expand-lg">
        <div class="container-fluid">  
            <a class="navbar-brand d-lg-none d-lg-flex mx-lg-auto" href="./index.html"></a>   
            <div class="d-flex"> 
                <ul class="navbar-nav justify-content-end d-lg-none">
                    <li class="nav-item">
                        <a class="nav-link" href="#">
                            <button type="button" class="position-relative" data-bs-toggle="modal" data-bs-target="#cartModal">
                                <div class="icon-cart"></div>
                                <span class="position-absolute top-0 start-100 translate-middle badge">
                                    2
                                    <span class="visually-hidden">unread messages</span>
                                </span>
                            </button>
                        </a>
                    </li>                   
                </ul>  
                <button class="navbar-toggler collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#main_nav" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="toggler-icon top-bar"></span>
                    <span class="toggler-icon middle-bar"></span>
                    <span class="toggler-icon bottom-bar"></span>
                </button>  
            </div>
            
            <div class="collapse navbar-collapse" id="main_nav">
                <ul class="navbar-nav col ">
                    <li class="nav-item"><a class="nav-link" href="#"> Homme </a></li>
                    <li class="nav-item"><a class="nav-link" href="#"> Femme </a></li>
                    <li class="nav-item"><a class="nav-link" href="#"> Concept </a></li>
                </ul>
                <a class="navbar-brand d-none d-lg-flex mx-lg-auto" href="./index.html"></a>
                <ul class="navbar-nav col justify-content-end  d-none  d-sm-none d-md-none  d-lg-flex">
                    <li class="nav-item">
                        <a class="nav-link" href="#">
                            <button type="button" class="position-relative" data-bs-toggle="modal" data-bs-target="#cartModal">
                                <div class="icon-cart"></div>
                                <span class="position-absolute top-0 start-100 translate-middle badge">2</span>
                            </button>
                        </a>
                    </li>                   
                </ul>
            </div>

        </div> 
    </nav>

    <!--Modal cart-->
    <div  class="modal fade" id="cartModal" tabindex="-1" aria-labelledby="cartModal" aria-hidden="true">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title">VOTRE PANIER</h5>
                    <button type="button" class="btn-close btn-close-white" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <div class="modal-body d-flex justify-content-center align-items-center">
                    <div class="text-center">
                        <p class="text-empty-cart mb-0">Votre panier est vide</p>
                        <p>Livraison & Retours gratuits</p>
                    </div>
                </div>
                <div class="modal-footer">                   
                    <button type="button" class="btn btn-dark">Se connecter</button>
                </div>
            </div>
        </div>
    </div>

</template>

<script>

export default {
    name: "NavBar",
    mounted() {
        var navbar = document.getElementById("navbar_top");

        window.onscroll = function() {
        "use strict";
        if (document.body.scrollTop >= 50 || document.documentElement.scrollTop >= 50) {
            navbar.classList.add("sticky");
        } else {
            navbar.classList.remove("sticky");
        }
        };
    
    }
    
}
</script>

<style scoped>
</style>