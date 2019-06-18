<template>
    <div class="container">
        <section class="subscribe">
            <div class="content">
                <div class="header">subscribe to our newsletter</div>
                <div class="description">sign up now and get 75% off</div>
                <div class="signup-btn">signup now</div>
            </div>
        </section>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
    .subscribe {
        position: relative;
        width: 100%;
        height: 250px;
        background: url(~assets/images/subscribe.png) no-repeat, #d7dbd5;
    }

    .content {
        position: absolute;
        top: 20%;
        left: 10%;
    }

    .header {
        margin-bottom: 10px;
        font-weight: 600;
        font-size: 26px;
        text-transform: uppercase;
    }

    .description {
        display: flex;
        justify-content: center;
        margin-bottom: 20px;
        font-weight: 400;
        font-size: 16px;
        text-transform: uppercase;
    }

    .signup-btn {
        display: flex;
        justify-content: center;
        align-items: center;
        width: 205px;
        height: 70px;
        margin: auto;
        background: #000;
        color: #fff;
        text-transform: uppercase;
        font-size: 14px;
        border-radius: 30%;
        cursor: pointer;
    }
</style>
