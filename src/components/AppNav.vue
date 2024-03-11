<script>

export default {
    name: "AppNav",
}

</script>

<template>
    <div class="my-container">
        <div class="top-nav d-flex justify-content-between align-items-center  border border-warning">
            <div class="my-icon d-flex gap-2">
                <i class="fa-brands fa-facebook-f"></i>
                <i class="fa-brands fa-x-twitter"></i>
                <i class="fa-brands fa-instagram"></i>
                <i class="fa-brands fa-youtube"></i>
            </div>

            <div class="personal-space d-flex align-items-center">
                <div class="my-shop p-2 ">
                    
                        <ul class="navbar-nav">
                            <li class="nav-item dropdown">
                                <button class="btn " data-bs-toggle="dropdown"
                                    aria-expanded="false">
                                    Shopping Cart <i class="fa-solid fa-chevron-down"></i>
                                </button>
                                <ul class="dropdown-menu dropdown-menu">
                                    <li><a class="dropdown-item">Le tue Scelte</a></li>
                                   
                                </ul>
                            </li>
                        </ul>
                    
                   
                </div>
                <div class="account p-2">
                    <span>My Account <i class="fa-solid fa-chevron-down"></i></span>

                </div>
                <div class="shop d-flex align-items-center p-2">
                    <i class="fa-solid fa-cart-shopping"></i>
                    <span>CART</span>
                </div>

            </div>
        </div>

        <!-- inizio seconda Nav -->

        <div class="down-nav d-flex justify-content-between align-items-center  py-3 border border-warning">
            <div class="my-logo">
                <img src="../../public/images/classic_shop_logo1x.png" alt="">
            </div>
            <div class="site-section d-flex gap-2 align-items-center  ">
                <ul class="d-flex gap-2 m-0">
                    <li>Home <i class="fa-solid fa-chevron-down"></i></li>
                    <li>Shop <i class="fa-solid fa-chevron-down"></i></li>
                    <li>Product <i class="fa-solid fa-chevron-down"></i></li>
                    <li>Categories <i class="fa-solid fa-chevron-down"></i></li>
                    <li>News </li>
                    <li>Element <i class="fa-solid fa-chevron-down"></i></li>
                </ul>
                <button class="btn btn-primary py-2 rounded-pill ">
                    SHOP NOW
                </button>
                <div class="serch-icon">
                    <i class="fa-solid fa-magnifying-glass"></i>
                </div>
            </div>

        </div>
    </div>

    <!-- jumpotron -->
    <div class="container-fluid my-bg-jumbo ">
        <div class="my-container text-center  d-flex flex-column align-item-center text-white my-padding">
            <h2 class="display-1 fw-bolder my-3  ">Brand New Arrivals</h2>
            <h3 class="fw-lighter">New Collection from New York</h3>
            <div class="d-flex justify-content-center gap-3">
                <div class="my-btn-trasparent">VIEW ALL</div>
                <div class="my-btn-trasparent">LOOKBOOK</div>

                
            </div>

        </div>
    </div>

</template>

<style lang="scss">
@use "../newstyles/styles.scss" as *;

.my-bg-jumbo{
    background-image: url(../../public/images/home1_slide_three_bg_2.jpg);
    background-position: top;
    background-repeat: no-repeat;

    height: 650px;
    display: flex;
    align-items: center;

    .my-padding{
        padding-top: 150px;
        padding-bottom: 110px;
    }
    
}

ul{
    list-style-type: none;
}
</style>
