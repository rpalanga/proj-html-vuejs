<script>

export default {
    name: "AppMain"


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

        <!-- immagini  -->

        <div class="row">
            <div class="col-3">
                <div class="card border-0" style="width: 18rem;">
                    <img src="../../public/images/black_elegant_leather_jacket-200x260.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of
                            the card's content.</p>
                    </div>
                </div>
            </div>
            <div class="col-3">
                <div class="card border-0" style="width: 18rem;">
                    <img src="../../public/images/black_leather_suit-200x260.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of
                            the card's content.</p>
                    </div>
                </div>
            </div>
            <div class="col-3">
                <div class="card border-0" style="width: 18rem;">
                    <img src="../../public/images/blue_jacket_and_white_stripe_tee-200x260.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of
                            the card's content.</p>
                    </div>
                </div>
            </div>
            <div class="col-3">
                <div class="card border-0" style="width: 18rem;">
                    <img src="../../public/images/modern_black_leather_suit-200x260.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of
                            the card's content.</p>
                    </div>
                </div>
            </div>
        </div>

    </div>

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
</style>