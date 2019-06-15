<template>
    <section class="hero">
        <aside class="socialbar">
            <div>
                <img src="~assets/images/fb.png" alt="facebook icon">
            </div>
            <div>
                <img src="~assets/images/tw.png" alt="twitter icon">
            </div>
            <div>
                <img src="~assets/images/g+.png" alt="google+ icon">
            </div>
            <div>
                <img src="~assets/images/insta.png" alt="instagram icon">
            </div>
            <div class="follow-us"><span>follow us</span></div>
        </aside>

        <div class="content">
            <div class="content-wrapper">
                <div class="header">
                    <span>summer</span>
                    <br />
                    <span>collection</span>
                    <div class="slider-controls">
                        <div>
                            <span>prev</span>
                            <div><i class="fa fa-long-arrow-left" aria-hidden="true"></i></div>
                        </div>
                        <div>
                            <span>next</span>
                            <div><i class="fa fa-long-arrow-right" aria-hidden="true"></i></div>
                        </div>
                    </div>
                </div>

                <div class="slide-name">
                    <span class="slide-number">01</span><span> men's wear</span>
                </div>

                <div class="slide-actions">
                    <div><i class="fa fa-angle-right" aria-hidden="true"></i></div>
                    <div><i class="fa fa-heart" aria-hidden="true"></i></div>
                    <div><i class="fa fa-share-alt" aria-hidden="true"></i></div>
                </div>

                <div class="slide-description">
                    <span>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid doloremque optio ipsum</span>
                </div>

                <div class="shop-now-btn">shop now</div>

            </div>

            <SpecialOffer />
        </div>
    </section>
</template>

<script>
import SpecialOffer from './SpecialOffer.vue';

export default {
    components: {
        SpecialOffer
    }
}
</script>

<style scoped>
    .hero {
        display: flex;
        width: 100%;
        height: 550px;
        background: #ededed;
    }

    .socialbar {
        flex-basis: 5%;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        position: relative;
    }

    .socialbar div {
        margin-bottom: 30%;
        cursor: pointer;
    }

    .socialbar .follow-us {
        position: absolute;
        bottom: 28%;
        width: 80px;
        transform: rotate(-90deg);
        text-transform: uppercase;
        font-weight: 600;
        font-size: 10px;
    }

    .content {
        flex-basis: 95%;
        position: relative;
        background: url(~assets/images/hero-bg.jpg) no-repeat;
        background-size: contain;
    }

    .content-wrapper {
        position: absolute;
        left: 50%;
        top: 100px;
    }

    .content .header {
        font-weight: 600;
        font-size: 56px;
        text-transform: uppercase;
    }

    .header .slider-controls {
        position: absolute;
        top: 1%;
        right: 1%;
        font-size: 12px;
        font-weight: 600;
        letter-spacing: 1px;
    }

    .slider-controls div {
        cursor: pointer;
    }

    .slider-controls div:hover {
        color: #fff;
    }

    .slide-name {
        margin-top: 10px;
        text-transform: uppercase;
        font-size: 10px;
        font-weight: bold;
        letter-spacing: 2px;
    }

    .slide-name span {
        display: inline-block;
    }

    .slide-number {
        margin-right: 20px;
        font-size: 12px;
    }

    .slide-actions {
        display: flex;
        margin-top: 20px;
    }

    .slide-actions div {
        display: flex;
        justify-content: center;
        align-items: center;
        width: 35px;
        height: 35px;
        margin-right: 10px;
        border: 1px solid #000;
        border-radius: 50%;
        cursor: pointer;
    }

    .slide-actions div:hover {
        background: #000;
        color: #fff;
    }

    .slide-actions div:last-child {
        margin-right: 0;
    }

    .slide-description {
        max-width: 200px;
        margin-top: 20px;
        font-family: "Open Sans", sans-serif;
        font-size: 14px;
    }

    .shop-now-btn {
        display: flex;
        justify-content: center;
        align-items: center;
        width: 116px;
        height: 40px;
        margin-top: 20px;
        font-weight: 400;
        font-size: 14px;
        border: 1px solid #000;
        border-radius: 10%;
        text-transform: uppercase;
        cursor: pointer;
    }

    .shop-now-btn:hover {
        color: #fff;
        background: #000;
    }
</style>
