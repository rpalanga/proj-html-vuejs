<script>
import { store } from "../store.js"

export default {
    name: "AppCircleCarousel",

    data() {
        return {
            store
        }
    }



}

</script>

<template>

    <div id="my-circle-carousel" class="container-fluid circle-bg p-3">
        <div class="row justify-content-center ">
            <div class="col-10 ">
    
                <div id="carouselIndicators" class="carousel slide d-flex flex-column align-items-center ">
                    <div class="carousel-indicators">
                        <button type="button" data-bs-target="#carouselIndicators" data-bs-slide-to="0"
                            class="active" aria-current="true" aria-label="Slide 1" id="my-cirlce-button"></button>
                        <button type="button" data-bs-target="#carouselIndicators" data-bs-slide-to="1"
                            aria-label="Slide 2" id="my-circle-button"></button>
                        
                    </div>
                    <div class="carousel-inner ">
                        <div class="carousel-item active text-white my-circle-padding">
                            <div class="d-flex flex-column align-items-center ">
                                <img src="../../public/images/woman_testimonial.png" class="d-block w-20 p-4" alt="...">
                                <h6>Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore voluptate ipsum adipisci temporibus et laboriosam dolorum,</h6>
                                <p>Lara Palmer</p>

                            </div>
                        </div>
                        <div class="carousel-item text-white ">
                            <div class="d-flex flex-column align-items-center my-circle-padding">
                                <img src="../../public/images/woman_testimonial.png" class="d-block w-20 p-4" alt="...">
                                <h6>Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore voluptate ipsum adipisci temporibus et laboriosam dolorum,</h6>
                                <p>Lara Palmer</p>

                            </div>
                        </div>
                    </div>
                </div>
            </div>

        </div>
    </div>

</template>

<style lang="scss">
@use "../newstyles/styles.scss" as *;

.circle-bg {
    background-image: url(/images/testimonials_home_1_bg.jpg);
    background-size: cover;

    
    
    
}
#my-circle-carousel{

    .carousel-indicators button  {
        border-radius: 50%;
        width: 16px;
        height: 16px;
        color: black;
    }

    .img-circle{
        width: 30px;
    }

    .my-circle-padding{
        padding: 150px 60px;
    }

}
</style>