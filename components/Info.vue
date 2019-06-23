<template>
    <section class="info">
        <div class="container">
            <div class="info-wrapper">
                <div class="info-item">
                    <div class="header">information</div>
                    <div class="link">The brand</div>
                    <div class="link">Local stores</div>
                    <div class="link">Customer service</div>
                    <div class="link">Privacy & cookies</div>
                    <div class="link">Site map</div>
                </div>
                <div class="info-item">
                    <div class="header">my profile</div>
                    <div class="link">Getting started</div>
                    <div class="link">FAQs</div>
                    <div class="link">Buying guide</div>
                    <div class="link">Order returns</div>
                    <div class="link">Affiliant program</div>
                </div>
                <div class="info-item">
                    <div class="header">your account</div>
                    <div class="link">Getting started</div>
                    <div class="link">FAQs</div>
                    <div class="link">Buying guide</div>
                    <div class="link">Order returns</div>
                    <div class="link">Affiliant program</div>
                </div>
                <div class="info-item">
                    <div class="header">lookbook</div>
                    <div class="link">Getting started</div>
                    <div class="link">FAQs</div>
                    <div class="link">Buying guide</div>
                    <div class="link">Order returns</div>
                    <div class="link">Affiliant program</div>
                </div>
                <div class="info-item">
                    <div class="header">contact details</div>
                    <div class="link">Getting started</div>
                    <div class="link">FAQs</div>
                    <div class="link">Buying guide</div>
                    <div class="link">Order returns</div>
                    <div class="link">Affiliant program</div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style scoped>
    .info {
        position: relative;
        padding-bottom: 100px;
        background: #f8f8f8;
    }

    .info-wrapper {
        display: flex;
        justify-content: space-between;
    }

    .info-item .header {
        margin-bottom: 40px;
        font-size: 15px;
        font-weight: 700;
        text-transform: uppercase;
    }

    .info-item .link {
        margin-bottom: 15px;
        font-size: 14px;
        font-weight: 300;
        color: #c2c2c2;
    }
</style>
