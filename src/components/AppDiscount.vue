<script>

export default{
    
    name:"AppDiscount",
}
</script>

<template>
    <div class="container-fluid sales-bg">
        <div class="my-container p-5">
            <div class="row justify-content-center gap-4 ">
                <div class="col-5 my-relative-sale  p-0">
                    <img src="../../public/images/promo_box_1_bg.jpg" class="w-100" alt="">
                    <div class="my-absolute-sale ps-5">
                        <h4>70% OFF </h4>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. <br> Quaerat eveniet cum.</p>
                        <button class="my-btn-trasparent">
                            VIEW MORE
                        </button>

                    </div>


                </div>
                <div class="col-5 my-relative-sale  p-0 ">
                    <img src="../../public/images/promo_box_2_bg.jpg" class="w-100" alt="">
                    <div class="my-absolute-sale ps-5">
                        <h4>Free Shipping</h4>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. <br> Quaerat eveniet cum.</p>
                        <button class="my-btn-trasparent">
                            VIEW MORE
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </div>
    
</template>

<style lang="scss">
@use "../newstyles/styles.scss" as *;

.sales-bg{
    background-image: url(/images/bkgd_confetti-compressor.jpg);
    // background-image: url(../../public/images/bkgb_confetti-compressor.jpg);
    
    background-position: center;
    // background-repeat: no-repeat;
    background-size: cover;

    

    .my-relative-sale{
        position: relative;
    }

    .my-absolute-sale{
        position: absolute;
        bottom: 20%;
        left: 0;

        h4{
        color: white;
        font-weight: bolder;
    }
    p{
        color: white;
    }

    }
    

}

</style>