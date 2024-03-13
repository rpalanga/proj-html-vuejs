<script>
import { store } from "../store.js";


export default {
    name: "AppFooter",

    data() {
        return {
            store
        }
    },
    props: {
        post: Array,
        footerTag: Array,
    }


}

</script>

<template>
    <div id="top-footer" class="container-fluid ">
        <div class="my-container d-flex justify-content-center p-5">

            <div class="row gap-2 justify-content-between align-items-center ">
                <div class="col-5 d-flex text-white fs-1 justify-content-between align-items-center gap-2  ">
                    <i class="fa-regular fa-envelope"></i>
                    <div class="text-white fs-5  ">Subscribe now and receive the Special Offer</div>
                </div>
                <div class="col-5 d-flex align-items-center gap-2 ">
                    <input type="email" name="" id="" placeholder="insert your email"
                        class="bg-white p-2 rounded-3 rounded-pill text-black ">
                    <button class="btn btn-primary rounded-pill ">SEND</button>
                </div>
            </div>

        </div>
    </div>

    <!-- middle footer -->

    <div id="middle-footer" class="container-fluid py-3">

        <div class="my-container p-3">
            <div class="row">
                <div class="col-3 d-flex flex-column justify-content-start">
                    <div class="pb-3">
                        <img src="../../public/images/classic_shop_logo_footer.png" alt="" class="w-100">

                    </div>

                    <div class="pb-3 text-white">
                        <ul class="list-unstyled">
                            <li> 12345 North manin Street,</li>
                            <li>New York, NY 5555555</li>
                            <li>Phone:1.800.555.6789</li>
                            <li>Email:info@compagny.com</li>
                            <li>Web:Theme-fusion.com</li>
                        </ul>

                    </div>

                    <div class="pb-5 text-white">
                        <i class="fa-brands fa-facebook-f"></i>
                        <i class="fa-brands fa-x-twitter"></i>
                        <i class="fa-brands fa-instagram"></i>
                        <i class="fa-brands fa-youtube"></i>
                    </div>

                </div>

                <div class="col-3">

                    <h5 class="text-white fw-bold mb-4 ">TOP RATED ELEMENT</h5>

                    <ul class="list-style-none p-0 text-white">

                        <li class="d-flex justify-content-between border-bottom pb-2">
                            <div>
                                <h6 class="ps-e">Black-jacket </h6>
                                <span><i v-for="n in 5" class="fa-solid fa-star"></i></span>
                                <div class="fw-bold">$235 <span class="fw-bold">$200</span></div>

                            </div>

                            <img src="../../public/images/black_elegant_leather_jacket-120x156.jpg" alt=""
                                class="img-product-footer">

                        </li>
                        <li class="d-flex justify-content-between border-bottom pb-2">
                            <div>
                                <h6 class="ps-e">Black-jacket <span
                                        class="fw-bold text-decoration-line-through ">$80</span></h6>
                                <span class="fw-bold">60$</span>

                            </div>
                            <img src="../../public/images/black_elegant_leather_jacket-120x156.jpg" alt=""
                                class="img-product-footer">

                        </li>
                        <li class="d-flex justify-content-between border-bottom pb-2">
                            <div>
                                <h6 class="ps-e">Black-jacket <span
                                        class="fw-bold text-decoration-line-through">$60</span></h6>
                                <span class="fw-bold">$30</span>

                            </div>

                            <img src="../../public/images/black_elegant_leather_jacket-120x156.jpg" alt=""
                                class="img-product-footer">

                        </li>
                    </ul>


                </div>

                <div class="col-3">
                    <h5 class="text-white fw-bold mb-4 ">RECENT POST</h5>
                    <ul class="list-unstyled">
                        <li v-for="currentPost in post " class="text-white border-bottom "> <i
                                class="fa-solid fa-chevron-right px-2"></i>{{ currentPost }}</li>
                    </ul>

                </div>

                <div class="col-3">
                    <h5 class="text-white fw-bold mb-4">TAGS</h5>
                    <ul class="d-flex flex-wrap list-unstyled">
                        <li v-for="currentTag in footerTag" class="text-white border m-2 p-2">{{ currentTag }}</li>
                    </ul>

                </div>
            </div>
        </div>


    </div>

    <div id="down-footer" class="container-fluid">
        <div class="my-container d-flex flex-column align-items-center py-3 ">
            <div class="row justify-content-center ">
                <div class="col-12">
                    <p class="text-white">© Copyright 2012-2020 | Avada by Theme by Theme Fusion | All Rights Reserved | Powered by Boolean</p>
                </div>
            </div>
            <div class="row justify-content-center">
                <div class="col-12">
                    <img src="../../public/images/payment_cards_footer.png" alt="">
                </div>
            </div>
            
        </div>


    </div>






</template>

<style lang="scss">
@use "../newstyles/styles.scss" as *;

#top-footer {
    background-color: #313337;
}

#middle-footer {
    background-color: #2C2E32;

    .img-product-footer {
        width: 75px;
    }

    .fa-star {
        color: #427ED1
    }
}

#down-footer {
    background-color: #1D1F22;
}
</style>