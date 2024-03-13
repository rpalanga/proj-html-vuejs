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
            <div class="col-4 fw-bolder fs-1 ">New Arrivals</div>
            <div class="col-4">
                <hr>
            </div>
        </div>
        <div class="row text-center mb-3">
            <div class="col-12">Brand New product from top designer</div>
        </div>
    </div>


    <div id="big-carousel" class="container-fluid mb-5">
        <!-- Carosello con cinque elementi -->

        

        <div id="carouselExampleIndicators" class="carousel slide">

            <div class="carousel-inner">
                <div class="carousel-item active">
                    <div class="d-flex my-big-car-width ">
                        <img src="/public/images/blue_leather_jacket-231x300.jpg" class="d-block w-100" alt="...">
                        <img src="/public/images/hipster_black_top-231x300.jpg" class="d-block w-100" alt="...">
                        <img src="/public/images/spring_printed_dress-231x300.jpg" class="d-block w-100" alt="...">
                        <img src="/public/images/black_elegant_leather_jacket-231x300.jpg" class="d-block w-100"
                            alt="...">
                        <img src="/public/images/black_leather_jacket-231x300.jpg" class="d-block w-100" alt="...">
                    </div>

                </div>
                <div class="carousel-item">
                    <div class="d-flex my-big-car-width ">
                        <img src="/public/images/blue_leather_jacket-231x300.jpg" class="d-block w-100" alt="...">
                        <img src="/public/images/hipster_black_top-231x300.jpg" class="d-block w-100" alt="...">
                        <img src="/public/images/spring_printed_dress-231x300.jpg" class="d-block w-100" alt="...">
                        <img src="/public/images/black_elegant_leather_jacket-231x300.jpg" class="d-block w-100"
                            alt="...">
                        <img src="/public/images/black_leather_jacket-231x300.jpg" class="d-block w-100" alt="...">
                    </div>
                </div>

            </div>
            <button class="carousel-control-prev my-prev" type="button" data-bs-target="#carouselExampleIndicators"
                data-bs-slide="prev">
                <span class="carousel-control-prev-icon my-icon-prev" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next my-next" type="button" data-bs-target="#carouselExampleIndicators"
                data-bs-slide="next">
                <span class="carousel-control-next-icon my-icon-next" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
            </button>
        </div>





    </div>

</template>

<style lang="scss">
@use "../newstyles/styles.scss" as *;

#big-carousel {
    width: 100%;
    

    // display: flex;
    // // justify-content: center;
    // position: relative;


    .my-next,
    .my-prev {
        position: absolute;
        top: 50%;
        transform: translateY(-50%);
        z-index: 1;
    }

    .my-prev {
        left: 10px;
    }

    .my-next {
        right: 10px;
    }
}
</style>