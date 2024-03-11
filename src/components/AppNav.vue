<script>

export default{
    name:"AppNav",
}

</script>

<template>
    <div class="container-fluid">
        <div class="top-nav d-flex justify-content-between border border-warning">
            <div class="my-icon">
                <i class="fa-brands fa-facebook-f"></i>
                <i class="fa-brands fa-x-twitter"></i>
                <i class="fa-brands fa-instagram"></i>
                <i class="fa-brands fa-youtube"></i>
            </div>
            <div class="personal-space d-flex">
                <div class="my-shop">
                    <span>Shopping cart </span>
                </div>
                <div class="account">
                    <span>My Account <i class="fa-solid fa-chevron-down"></i></span>

                </div>
                <div class="shop d-flex">
                    <i class="fa-solid fa-cart-shopping"></i>
                    <span>CART</span>
                </div>

            </div>
        </div>
        <div class="down-nav d-flex justify-content-between border border-warning">
            

        </div>
    </div>
  
</template>

<style lang="scss">
@use "../newstyles/styles.scss" as *;

</style>
