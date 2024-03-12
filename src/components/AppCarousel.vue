<script>
import { store } from "../store.js"

export default {
    name: "AppCarousel",

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
            <div class="col-4 fw-bolder fs-1 ">Best Seller</div>
            <div class="col-4">
                <hr>
            </div>
        </div>
        <div class="row text-center mb-3">
            <div class="col-12">Must have product form our top sellers</div>
        </div>

        <!-- Carosello con cinque elementi -->

        <div id="carouselExample" class="carousel slide mb-3 position-relative  ">
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <div class="d-flex ">
                        <img src="/public/images/blue_leather_jacket-231x300.jpg" class="d-block w-20" alt="...">
                        <img src="/public/images/blue_leather_jacket-231x300.jpg" class="d-block w-20" alt="...">
                        <img src="/public/images/blue_leather_jacket-231x300.jpg" class="d-block w-20" alt="...">
                        <img src="/public/images/blue_leather_jacket-231x300.jpg" class="d-block w-20" alt="...">
                        <img src="/public/images/blue_leather_jacket-231x300.jpg" class="d-block w-20" alt="...">
                    </div>
                </div>
                <div class="carousel-item">
                    <div class="d-flex ">
                        <img src="/public/images/blue_leather_jacket-231x300.jpg" class="d-block w-20" alt="...">
                        <img src="/public/images/blue_leather_jacket-231x300.jpg" class="d-block w-20" alt="...">
                        <img src="/public/images/blue_leather_jacket-231x300.jpg" class="d-block w-20" alt="...">
                        <img src="/public/images/blue_leather_jacket-231x300.jpg" class="d-block w-20" alt="...">
                        <img src="/public/images/blue_leather_jacket-231x300.jpg" class="d-block w-20" alt="...">
                    </div>
                </div>
            </div>

            <button class="carousel-control-prev position-absolute top-50 start-0 translate-middle" type="button" data-bs-target="#carouselExampleControlsNoTouching" data-bs-slide="prev">
                <span class="carousel-control-prev-icon text-black" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next position-absolute top-50 start-100 translate-middle" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden ">Next</span>
            </button>
        </div>




    </div>

</template>

<style lang="scss">
@use "../newstyles/styles.scss" as *;
</style>