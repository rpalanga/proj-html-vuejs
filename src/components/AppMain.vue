<script>
import {store} from "../store.js";
import AppCarousel from './AppCarousel.vue';
import AppDiscount from './AppDiscount.vue';
import AppBigCarousel from './AppBigCarousel.vue';
import AppCircleCarousel from './AppCircleCarousel.vue';
import AppBlog from './AppBlog.vue';




export default {
    name: "AppMain",

    data(){
        return{
            store
        }
    },
    components:{
        AppCarousel,
        AppDiscount,
        AppBigCarousel,
        AppCircleCarousel,
        AppBlog,
    }



}
</script>

<template>
    <div class="my-container">

        <div class="row justify-content-center align-items-center text-center my-main-padding ">
            <div class="col-4">
                <hr>
            </div>
            <div class="col-4 fw-bolder fs-1 ">Faetured Product</div>
            <div class="col-4">
                <hr>
            </div>
        </div>
        <div class="row text-center mb-3">
            <div class="col-12">Must have product form our top sellers</div>
        </div>

        <!-- sezione dei bottoni in hover -->

        <div class="row justify-content-center mb-5">
            <div class="col-10 d-flex justify-content-center">
                <div class="btn-group btn-group-lg" role="group" aria-label="Large button group">
                    <button type="button"
                        class="btn btn-light border border-3 rounded-0 button-padding fw-bolder">Man</button>
                    <button type="button"
                        class="btn btn-light border border-3 rounded-0 button-padding fw-bolder">Woman</button>
                    <button type="button"
                        class="btn btn-light border border-3 rounded-0 button-padding fw-bolder">Accessories</button>
                </div>

            </div>

        </div>

        <!-- immagini card-abiti  -->

        <div class="row mb-4">
            <div class="col-3">
                <div class="card border-0" style="width: 18rem;">
                    <div class="my-card-hover">
                        
                        <img src="../../public/images/black_elegant_leather_jacket-200x260.jpg" class="card-img-top "
                            alt="...">
                        <div class="my-overlay">
                            <div>
                                <i class="fa-solid fa-circle-check fs-1"></i>
                            </div>
                        </div>


                    </div>
                    <div class="card-body">
                        <h5 class="card-title">
                            Black Leather Jacket
                        </h5>
                        <p class="card-text">
                            <span>Vestito interessante</span>
                            <strong>45.00$</strong>
                        </p>
                    </div>
                </div>
            </div>
            <div class="col-3">
                <div class="card border-0" style="width: 18rem;">
                    <div class="my-card-hover">
                        <img src="../../public/images/black_leather_suit-200x260.jpg" class="card-img-top" alt="...">
                        <div class="my-overlay">
                            <div>
                                <i class="fa-solid fa-circle-check fs-1"></i>
                            </div>
                        </div>
                    </div>
                    <div class="card-body">
                        <h5 class="card-title">
                            Black Lather Suit
                        </h5>
                        <p class="card-text">
                            <span>Man,Jacket,Jeans</span>
                            <strong>45.00$</strong>
                        </p>
                    </div>
                </div>
            </div>
            <div class="col-3">
                <div class="card border-0" style="width: 18rem;">
                    <div class="my-card-hover">
                        <img src="../../public/images/blue_jacket_and_white_stripe_tee-200x260.jpg" class="card-img-top"
                            alt="...">

                            <div class="my-overlay">
                                <div>
                                <i class="fa-solid fa-circle-check fs-1"></i>
                            </div>
                            </div>
                        
                    </div>
                    <div class="card-body">
                        <h5 class="card-title">
                            Black Leather Suit
                        </h5>
                        <p class="card-text">
                            <span>Men, Jacket</span>
                            <strong>45.00$</strong>
                        </p>
                    </div>
                </div>
            </div>
            <div class="col-3">
                <div class="card border-0" style="width: 18rem;">
                    <div class="my-card-hover">
                        <img src="../../public/images/modern_black_leather_suit-200x260.jpg" class="card-img-top" alt="...">
                        <div class="my-overlay">
                            <div>
                                <i class="fa-solid fa-circle-check fs-1"></i>
                            </div>
                        </div>
                    </div>
                    <div class="card-body">
                        <h5 class="card-title">
                            Blue Jacket & Stripe Tee
                        </h5>
                        <p class="card-text">
                            <span>Men,  Jacket, Suits</span>
                            <strong>45.00$</strong>
                        </p>
                    </div>
                </div>
            </div>
        </div>

    </div>

    <!-- immagine Cubiche per le Season -->

    <div class="container-fluid">
        <div class=" row  ">
            <div class="col-4 p-0 my-width" 
            style="
            background-image: url(/images/winter_collection_bg.jpg);
            background-position:top;
            background-size: cover;
            ">
               
                <div class="collection text-white">
                    <h4>Winter Collection</h4>
                    <h6>Stylish and More</h6>
                    <button class="my-btn-trasparent">VIEW MORE</button>
                </div>
            </div>
            <div class="col-4 p-0 my-width"
            style="
            background-image: url(/images/spring_collection_bg.jpg);
            background-position:top;
            background-size: cover;"
            >
                
             <div class="collection text-white">
                    <h4>Winter Collection</h4>
                    <h6>Stylish and More</h6>
                    <button class="my-btn-trasparent">VIEW MORE</button>
                </div>

            </div>
            <div class="col-4 p-0 my-width"
            style="
            background-image: url(/images/autumn_collection_bg.jpg);
            background-position:top;
            background-size: cover;"
            >
             <div class="collection text-white">
                    <h4>Winter Collection</h4>
                    <h6>Stylish and More</h6>
                    <button class="my-btn-trasparent">VIEW MORE</button>
                </div>
                

            </div>
        </div>
    </div>


<AppCarousel/>

<AppDiscount/>

<AppBigCarousel/>

<AppCircleCarousel/>

<AppBlog/>

</template>

<style lang="scss">
@use "../newstyles/styles.scss" as *;

.my-container {

    .my-main-padding {
        padding-top: 110px;
    }

    .button-padding {
        padding: 25px 50px;
    }

}
// .limit-container{
//     max-width: 1920px;


    .my-width{
        width: calc(100% / 3);


    }

    .collection{
        margin-top: 300px;
    margin-bottom: 60px;
    text-align: center;

    h4{
        font-weight: bolder;
    }

    }
    
    .my-position-absolute{
        position: absolute;
        top: 0;
        left: 0;
    }

    .my-card-hover{
       position: relative;
        
    }
    .my-overlay{
        position: absolute;
        height: 100%;
        width: 100%;
        top: 0;
        left: 0;
        background-image: linear-gradient(rgba(150, 125, 157, .8), rgba(95, 107, 171, .8));

        opacity: 0;
        transition: opacity 0.7 ease;

        display: flex;
        align-items: center;
        justify-content: center;
    }

    .my-card-hover:hover .my-overlay{
        opacity: 1;
    }

    
// }
</style>