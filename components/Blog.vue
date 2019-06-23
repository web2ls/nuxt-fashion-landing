<template>
    <section class="blog">
        <div class="bg-footer"></div>

        <div class="left-control">
            <i aria-hidden="true" class="fa fa-caret-left"></i>
        </div>
        <div class="right-control">
            <i aria-hidden="true" class="fa fa-caret-right"></i>
        </div>

        <div class="container">
            <div class="header">our blogs and news</div>
            <div class="content">
                <div class="blog-first">
                    <div class="description">
                        <div class="post-header">the 15 secrets about fashion people</div>
                        <div class="date"><i>january 12, 2020 by admin</i></div>
                    </div>
                </div>
                <div class="blog-second">
                    <div class="description">
                        <div class="post-header">the 15 secrets about fashion people</div>
                        <div class="date"><i>january 12, 2020 by admin</i></div>
                    </div>
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
    .blog {
        position: relative;
        margin: 100px 0;
    }
    .header {
        margin-bottom: 60px;
        font-weight: 600;
        font-size: 26px;
        text-transform: uppercase;
        text-align: center;
    }

    .content {
        display: flex;
        justify-content: space-between;
        height: 400px;
        position: relative;
    }

    .bg-footer {
        position: absolute;
        left: 0;
        bottom: -100px;
        width: 100%;
        height: 35%;
        background: #f8f8f8;
        z-index: 1;
    }

    .blog-first {
        position: relative;
        z-index: 2;
        width: 100%;
        height: 100%;
        margin-right: 25px;
        background: url(~assets/images/blog1.jpg) no-repeat;
        background-size: cover;
    }

    .blog-second {
        position: relative;
        z-index: 2;
        width: 100%;
        height: 100%;
        background: url(~assets/images/blog2.jpg) no-repeat;
        background-size: cover;
    }

    .description {
        position: absolute;
        bottom: 0;
        left: 50%;
        width: 80%;
        transform: translate(-50%, 50%);
        padding-top: 22px;
        padding-bottom: 22px;
        text-align: center;
        background: #fff;
    }

    .description .post-header {
        font-weight: 600;
        font-size: 16px;
        text-transform: uppercase;
    }

    .description .date {
        font-family: 'Open Sans', sans-serif;
        font-size: 14px;
        
    }

    .left-control {
        display: flex;
        justify-content: center;
        align-items: center;
        position: absolute;
        left: 5%;
        top: 50%;
        transform: translateY(-50%);
        width: 35px;
        height: 35px;
        border: 1px solid #e3e3e3;
        border-radius: 50%;
        color: #e3e3e3;
        font-size: 24px;
    }

    .right-control {
        display: flex;
        justify-content: center;
        align-items: center;
        position: absolute;
        right: 5%;
        top: 50%;
        transform: translateY(-50%);
        width: 35px;
        height: 35px;
        border: 1px solid #000;
        border-radius: 50%;
        color: #000;
        font-size: 24px;
    }

</style>
