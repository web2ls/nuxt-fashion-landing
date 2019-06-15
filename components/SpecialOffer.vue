<template>
    <div class="special-offer">
        <div class="preview"></div>
        <div class="details">
            <div class="header">
                <span>special offer</span>
                <span>of the month</span>
            </div>

            <div class="special-object">Black long sleeve</div>

            <div class="special-price">
                <div class="pricing">
                    <div class="old-price">$105</div>
                    <div class="new-price">$65</div>
                </div>
                <div class="special-shop-now-btn">shop now</div>
            </div>

            <div class="timer">
                <div class="timer-item">
                    <div class="value">09</div>
                    <div class="divider">...</div>
                    <div class="measure">hours</div>
                </div>
                <div class="timer-item">
                    <div class="value">45</div>
                    <div class="divider">...</div>
                    <div class="measure">minutes</div>
                </div>
                <div class="timer-item">
                    <div class="value">53</div>
                    <div class="divider">...</div>
                    <div class="measure">seconds</div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
    .special-offer {
        display: flex;
        position: absolute;
        right: 0;
        bottom: 0;
        width: 330px;
        height: 250px;
        background: url(~assets/images/special-offer-bg.jpg) no-repeat;
        background-size: cover;
        color: #fff;
    }

    .preview {
        flex-basis: 30%;
        background: url(~assets/images/special-offer-preview.jpg) no-repeat center center;
        background-size: cover;
    }

    .details {
        flex-basis: 70%;
        padding: 10px 20px;
    }

    .details .header {
        display: flex;
        flex-direction: column;
        font-weight: 800;
        font-size: 20px;
        text-transform: uppercase;
    }

    .details .special-object {
        margin-top: 10px;
        font-family: "Open Sans", sans-serif;
        font-weight: 400;
        font-size: 10px;
    }

    .special-price {
        display: flex;
        margin-top: 10px;
        justify-content: space-between;
    }

    .pricing {
        display: flex;
        align-items: center;
    }

    .old-price {
        margin-right: 10px;
        font-weight: 400;
        font-size: 14px;
        text-decoration: line-through;
    }

    .new-price {
        font-weight: 700;
        font-size: 18px;
    }

    .special-shop-now-btn {
        width: 80px;
        height: 25px;
        border: 1px solid #f3ebdc;
        border-radius: 10%;
        font-size: 12px;
        text-align: center;
        line-height: 22px;
        cursor: pointer;
    }

    .special-shop-now-btn:hover {
        background: #f3ebdc;
        color: #000;
    }

    .timer {
        display: flex;
        justify-content: space-between;
        margin-top: 20px;
    }

    .timer-item {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        width: 60px;
        height: 80px;
        background: #fff;
        border-radius: 10%;
        overflow: hidden;
        color: #000;
    }

    .value {
        font-weight: 700;
        font-size: 20px;
        text-align: center;
    }

    .divider {
        text-align: center;
    }

    .measure {
        font-size: 10px;
        text-align: center;
        text-transform: uppercase;
    }
</style>
