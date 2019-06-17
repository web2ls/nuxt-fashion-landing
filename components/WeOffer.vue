<template>
    <div class="container">
        <section class="we-offer">          
                <div class="content">
                    <div class="header">
                        <span>we offer new brand styles</span>
                    </div>
                    <div class="description">sign up now and get 50% off</div>
                    <div class="see-full-btn">see full collection</div>
                </div>
        </section>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
    .we-offer {
        width: 100%;
        height: 250px;
        margin: 25px 0 100px;
        background: url(~assets/images/we-offer.png) no-repeat,#00b7d9;
    }

    .content {
        position: relative;
        left: 40%;
        top: 20%;
        width: 50%;
        text-align: center;
    }

    .header {
        margin-bottom: 20px;
        font-weight: 600;
        font-size: 26px;
        text-transform: uppercase;
    }

    .description {
        margin-bottom: 30px;
        font-weight: 400;
        font-size: 14px;
        text-transform: uppercase;
    }

    .see-full-btn {
        display: flex;
        justify-content: center;
        align-items: center;
        width: 245px;
        height: 50px;
        margin: 0 auto;
        background: #fff;
        color: #000;
        font-size: 12px;
        text-transform: uppercase;
        border-radius: 30%;
        cursor: pointer;
    }
</style>
