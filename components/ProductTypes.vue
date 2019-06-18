<template>
    <section class="product-types">
        <div class="container">
            <div class="header">product types</div>
            <div class="description">up to 30% discount</div>

            <div class="slider">
                <div class="slider-item mens">
                    <div class="shop-btn">shop men</div>
                </div>
                <div class="slider-item womens">
                    <div class="shop-btn">shop men</div>
                </div>
                <div class="slider-item kids">
                    <div class="shop-btn">shop men</div>
                </div>
            </div>
        </div>

        <div class="prev-slider-control">
            <span>prev</span>
        </div>
        <div class="next-slider-control">
            <span>next</span>
        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style scoped>
    .product-types {
        position: relative;
        width: 100%;
        margin-bottom: 100px;
    }

    .header {
        margin: 0 auto 10px;
        font-weight: 600;
        font-size: 26px;
        text-align: center;
        text-transform: uppercase;
    }

    .description {
        margin: 0 auto 20px;
        font-weight: 400;
        font-size: 14px;
        text-align: center;
        text-transform: uppercase;
        letter-spacing: 2px;
    }

    .slider {
        display: flex;
        justify-content: space-between;
    }

    .slider-item {
        position: relative;
        width: 100%;
        height: 480px;
        margin-right: 30px;
        background: #f4f4f6;
    }

    .slider-item:last-child {
        margin-right: 0;
    }

    .mens {
        background: url(~assets/images/product-type-slide1.png) no-repeat;
    }

    .womens {
        background: url(~assets/images/product-type-slide2.png) no-repeat;
    }
    .kids {
        background: url(~assets/images/product-type-slide3.png) no-repeat;
    }

    .shop-btn {
        position: absolute;
        bottom: 45px;
        left: 50%;
        transform: translateX(-50%);
        display: flex;
        justify-content: center;
        align-items: center;
        width: 175px;
        height: 60px;
        color: #fff;
        background: #000;
        text-transform: uppercase;
        font-size: 13px;
        border-radius: 30%;
        cursor: pointer;
    }

    .prev-slider-control {
        position: absolute;
        left: 3%;
        top: 50%;
        width: 45px;
        height: 110px;
        background: #afafaf;
    }

    .next-slider-control {
        position: absolute;
        right: 3%;
        top: 50%;
        width: 45px;
        height: 110px;
        background: #d7d7d7;
    }

    .prev-slider-control span,
    .next-slider-control span {
        display: inline-block;
        font-size: 14px;
        color: #353535;
        transform: rotate(-90deg);
        text-align: center;
        line-height: 110px;
        text-transform: uppercase;
    }
</style>
