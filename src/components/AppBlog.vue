<script>
export default {
    name: "AppBlog",
}
</script>

<template>
    <div class="my-container mt-5 mb-5">
        <div class="row justify-content-center align-items-center text-center mb-4 ">
            <div class="col-4">
                <hr>
            </div>
            <div class="col-4 fw-bolder fs-1 ">Faetured Product</div>
            <div class="col-4">
                <hr>
            </div>
        </div>
        <div class="row text-center mb-4">
            <div class="col-12">The latest Classic Shop News</div>
        </div>

        <!-- Card Blog -->

        <div class="row justify-content-between">
            <div class="col-4 d-flex justify-content-center">
                <div class="card border-0 " style="width: 18rem;">
                    <img src="../../public/images/post_img_12-300x188.jpg" class="" alt="...">
                    <div class="card-body ps-0">
                        <h5 class="card-title fw-bolder ">Leggi i nostri articoli</h5>
                        <h6><small>March 13, 2024 | 0 comment</small></h6>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of
                            the card's content.</p>
                    </div>
                </div>
            </div>
            <div class="col-4 d-flex justify-content-center">
                <div class="card border-0" style="width: 18rem;">
                    <img src="../../public/images/post_img_11-300x188.jpg" class="" alt="...">
                    <div class="card-body ps-0">
                        <h5 class="card-title fw-bolder">Leggi i nostri articoli</h5>
                        <h6><small>March 13, 2024 | 0 comment</small></h6>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of
                            the card's content.</p>
                    </div>
                </div>
            </div>
            <div class="col-4 d-flex justify-content-center">
                <div class="card border-0" style="width: 18rem;">
                    <img src="../../public/images/post_img_10-300x188.jpg" class="" alt="...">
                    <div class="card-body ps-0">
                        <h5 class="card-title fw-bolder">Leggi i nostri articoli</h5>
                        <h6><small>March 13, 2024 | 0 comment</small></h6>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of
                            the card's content.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <hr>

    <div id="products" class="my-container mb-3 ">
        <div class="row pb-3  justify-content-center">
            <div class="col-3 text-uppercase">Feateured</div>
            <div class="col-3 text-uppercase">On Sale</div>
            <div class="col-3 text-uppercase">Top Rated</div>
            <div class="col-3 text-uppercase">Last Review</div>
        </div>
        <div class="row justify-content-center">
            <div class="col-3">
                <ul class="list-style-none p-0">

                    <!-- prima colonna -->

                    <li class="d-flex justify-content-between p-0 border-bottom pb-2  ">
                        <div>
                            <h6 class="ps-e">Black-jacket <span class="fw-bold">$45</span></h6>

                        </div>
                        <img src="../../public/images/black_elegant_leather_jacket-120x156.jpg" alt=""
                            class="img-product-width">

                    </li>
                    <li class="d-flex justify-content-between border-bottom pb-2">
                        <div>
                            <h6 class="ps-e">Black-jacket <span class="fw-bold">$45</span></h6>
                            <span><i v-for="n in 5" class="fa-solid fa-star"></i></span>

                        </div>
                        <img src="../../public/images/black_elegant_leather_jacket-120x156.jpg" alt=""
                            class="img-product-width">

                    </li>
                    <li class="d-flex justify-content-between border-bottom pb-2">
                        <h6 class="ps-e">Black-jacket <span class="fw-bold">$45</span></h6>
                        <img src="../../public/images/black_elegant_leather_jacket-120x156.jpg" alt=""
                            class="img-product-width">

                    </li>


                </ul>
            </div>

            <!-- seconda colonna -->

            <div class="col-3">
                <ul class="list-style-none p-0">

                    <li class="d-flex justify-content-between border-bottom pb-2">
                        <div>
                            <h6 class="ps-e">Black-jacket </h6>
                            <span><i v-for="n in 5" class="fa-solid fa-star"></i></span>
                            <div class="fw-bold">$235 <span class="fw-bold">$200</span></div>
    
                        </div>
    
                        <img src="../../public/images/black_elegant_leather_jacket-120x156.jpg" alt=""
                            class="img-product-width">
    
                    </li>
                    <li class="d-flex justify-content-between border-bottom pb-2">
                        <div>
                            <h6 class="ps-e">Black-jacket <span class="fw-bold text-decoration-line-through ">$80</span></h6>
                            <span class="fw-bold">60$</span>
    
                        </div>
                        <img src="../../public/images/black_elegant_leather_jacket-120x156.jpg" alt=""
                            class="img-product-width">
    
                    </li>
                    <li class="d-flex justify-content-between border-bottom pb-2">
                        <div>
                            <h6 class="ps-e">Black-jacket <span class="fw-bold text-decoration-line-through">$60</span></h6>
                            <span class="fw-bold">$30</span>
    
                        </div>
    
                        <img src="../../public/images/black_elegant_leather_jacket-120x156.jpg" alt=""
                            class="img-product-width">
    
                    </li>
                </ul>
            </div>

            <!-- terza colonna  -->

            <div class="col-3">
                <ul class="list-style-none p-0">

                    <li class="d-flex justify-content-between border-bottom pb-2">
                        <div>
                            <h6 class="ps-e">Black-jacket </h6>
                            <span><i v-for="n in 5" class="fa-solid fa-star"></i></span>
                            <div class="fw-bold">$235 <span class="fw-bold">$200</span></div>
    
                        </div>
                        <img src="../../public/images/black_elegant_leather_jacket-120x156.jpg" alt=""
                            class="img-product-width">
    
                    </li>
                    <li class="d-flex justify-content-between border-bottom pb-2">
                        <div>
                            <h6 class="ps-e">Black-jacket </h6>
                            <span><i v-for="n in 5" class="fa-solid fa-star"></i></span>
                            <div class="fw-bold">$235 <span class="fw-bold">$200</span></div>
    
                        </div>
                        <img src="../../public/images/black_elegant_leather_jacket-120x156.jpg" alt=""
                            class="img-product-width">
    
                    </li>
                    <li class="d-flex justify-content-between border-bottom pb-2">
                        <div>
                            <h6 class="ps-e">Black-jacket </h6>
                            <span><i v-for="n in 5" class="fa-solid fa-star"></i></span>
                            <div class="fw-bold">$235 <span class="fw-bold">$200</span></div>
    
                        </div>
                        <img src="../../public/images/black_elegant_leather_jacket-120x156.jpg" alt=""
                            class="img-product-width">
    
                    </li>
                </ul>
            </div>

            <!-- quarta colonna -->

            <div class="col-3">
                <ul class="list-style-none p-0 ">
                    <li class="d-flex justify-content-between border-bottom pb-2">
                        <h6 class="ps-e">Black-jacket <span class="fw-bold">$45</span></h6>
                        <img src="../../public/images/black_elegant_leather_jacket-120x156.jpg" alt=""
                            class="img-product-width">
    
                    </li>
                    <li class="d-flex justify-content-between border-bottom pb-2">
                        <h6 class="ps-e">Black-jacket <span class="fw-bold">$45</span></h6>
                        <img src="../../public/images/black_elegant_leather_jacket-120x156.jpg" alt=""
                            class="img-product-width">
    
                    </li>
                    <li class="d-flex justify-content-between border-bottom pb-2">
                        <h6 class="ps-e">Black-jacket <span class="fw-bold">$45</span></h6>
                        <img src="../../public/images/black_elegant_leather_jacket-120x156.jpg" alt=""
                            class="img-product-width">
    
                    </li>

                </ul>
            </div>
        </div>
    </div>

    <div id="logos" class="container-fluid logo-bg">
        <div class="my-container mb-5 pb-5">
            <div class="row text-center my-5 pt-5">
                <h4>Brand Logo</h4>
            </div>
            <div class="row">
                <div class="col-3">
                    <img src="../../public/images/b_logotype_1.png" alt="">
                </div>
                <div class="col-3">
                    <img src="../../public/images/b_logotype_2.png" alt="">
                </div>
                <div class="col-3">
                    <img src="../../public/images/b_logotype_3.png" alt="">
                </div>
                <div class="col-3">
                    <img src="../../public/images/b_logotype_4.png" alt="">
                </div>
                
            </div>
        </div>
    </div>






</template>

<style lang="scss">
#products {

    .img-product-width {
        width: 75px;
    }

    .fa-star {
        color: #427ED1
    }
}

#logos{
    background-color: #F6F6F6;
}

</style>