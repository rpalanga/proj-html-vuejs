<script>
import { store } from "../store.js"

export default {
    name: "AppBigCarousel",

    data() {
        return {
            store
        }
    }



}

</script>

<template>
    
    <div class="my-container">
        
        <div class="row justify-content-center align-items-center text-center my-main-padding ">
            <div class="col-4">
                <hr>
            </div>
            <div class="col-4 fw-bolder fs-1 ">New Arrives</div>
            <div class="col-4">
                <hr>
            </div>
        </div>
        <div class="row text-center mb-3">
            <div class="col-12">Must have product form our top sellers</div>
        </div>
    </div>
    
    
    <div id="pippo" class="container-fluid mb-5">
        <!-- Carosello con cinque elementi -->
       
        <div id="carouselExampleAutoplaying" class="carousel slide mb-3 position-relative " data-bs-ride="carousel">
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <div class="d-flex my-car-width ">
                        <img src="/public/images/blue_leather_jacket-231x300.jpg" class="d-block w-100" alt="...">
                        <img src="/public/images/hipster_black_top-231x300.jpg" class="d-block w-100" alt="...">
                        <img src="/public/images/spring_printed_dress-231x300.jpg" class="d-block w-100" alt="...">
                        <img src="/public/images/black_elegant_leather_jacket-231x300.jpg" class="d-block w-100" alt="...">
                        <img src="/public/images/black_leather_jacket-231x300.jpg" class="d-block w-100" alt="...">
                    </div>
                </div>
                <div class="carousel-item">
                    <div class="d-flex my-car-width">
                        <img src="/public/images/blue_leather_jacket-231x300.jpg" class="d-block w-100" alt="...">
                        <img src="/public/images/blue_leather_jacket-231x300.jpg" class="d-block w-100" alt="...">
                        <img src="/public/images/blue_leather_jacket-231x300.jpg" class="d-block w-100" alt="...">
                        <img src="/public/images/blue_leather_jacket-231x300.jpg" class="d-block w-100" alt="...">
                        <img src="/public/images/blue_leather_jacket-231x300.jpg" class="d-block w-100" alt="...">
                    </div>
                </div>
            </div>

            <button class="carousel-control-prev my-position-absolute-left " type="button" data-bs-target="#carouselExampleAutoplaying" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next my-position-absolute-right" type="button" data-bs-target="#carouselExampleAutoplaying" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden ">Next</span>
            </button>
        </div>



    </div>
    
</template>

<style lang="scss">
@use "../newstyles/styles.scss" as *;

#pippo{

    display: flex;
    justify-content: center;

    .carousel-control-prev,
    .carousel-control-next {
      background-color: #000000;
    }
    
    .my-position-absolute-left{
        position: absolute;
        
        top: 100px;
        left: -110px;
        bottom: 100px;
        width: 30px;
    }
    .my-position-absolute-right{
        position: absolute;
        
        top: 100px;
        right: -110px;
        bottom: 100px;
        width: 30px;
    
    }
    
    .my-car-width{
        width: calc(100% / 5);
        
    }
}

</style>