<template>
    <section class="categories">
        <div class="filters">
            <ul class="filters-list">
                <li class="filters-item">All</li>
                <li class="filters-item">spring-summer</li>
                <li class="filters-item">sweatshirt</li>
                <li class="filters-item">sneackers</li>
                <li class="filters-item">gadgets</li>
                <li class="filters-item">outdoor</li>
            </ul>
        </div>

        <div class="categories-list">
            <div class="left-side">
                <div class="first-category">
                    <div class="description">
                        <div>buy 2 get</div>
                        <div>up 50% off</div>
                    </div>
                </div>
                <div class="second-category"></div>
            </div>
            <div class="center-side">
                <div class="new-badge">
                    <div class="blackground"><span>new</span></div>
                    <div class="triangle"></div>
                </div>

                <div class="description">
                    <div class="object">Winter Jacket</div>
                    <div class="object-description">
                        <span>vintage look</span>
                        <span>for women</span>
                    </div>
                    <div class="description-shop-now-btn">shop now</div>
                </div>
            </div>
            <div class="right-side">
                <div class="first-category">
                    <div class="description">
                        <div class="object">Winter Jacket</div>
                        <div class="object-description">
                            <span>vintage look</span>
                            <span>for women</span>
                        </div>
                        <div class="description-shop-now-btn">shop now</div>
                    </div>
                </div>
                <div class="second-category">
                    <div class="new-badge">
                        <div class="blackground"><span>new</span></div>
                        <div class="triangle"></div>
                    </div>
                    <div class="description">40% off on sunglasses</div>
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
    .filters {
        width: 70%;
        margin: 40px auto 20px auto;
    }

    .filters-list {
        display: flex;
        justify-content: space-around;
        color: #000;
    }

    .filters-list li {
        cursor: pointer;
    }

    .categories-list {
        display: flex;
        justify-content: space-between;
        height: 530px;
        overflow: hidden;
    }

    .left-side {
        display: flex;
        flex-direction: column;
        flex-basis: 25%;
        position: relative;
    }

    .center-side {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: flex-start;
        position: relative;
        flex-basis: 40%;
        padding-left: 1%;
        background: url(~assets/images/central.jpg) no-repeat;
        background-size: cover;
    }

    .right-side {
        display: flex;
        flex-direction: column;
        flex-basis: 25%;
    }

    .left-side .first-category {
        flex-basis: 70%;
        margin-bottom: 20px;
        background: url(~assets/images/left-side-first.jpg) no-repeat center center;
        background-size: cover;
        position: relative;
    }

    .left-side .first-category .description {
        position: absolute;
        bottom: 5%;
        left: 50%;
        transform: translateX(-50%);
        font-weight: 700;
        text-transform: uppercase;
        font-size: 20px;
    }

    .left-side .first-category .description span {
        display: inline-block;
    }

    .left-side .second-category {
        flex-basis: 30%;
        background: url(~assets/images/left-side-second.jpg) no-repeat center center;
        background-size: cover;
    }

    .right-side .first-category {
        display: flex;
        flex-direction: column;
        justify-content: flex-end;
        align-items: flex-start;
        flex-basis: 50%;
        margin-bottom: 20px;
        padding-left: 1%;
        padding-bottom: 5%;
        background: url(~assets/images/right-side-first.png) no-repeat center center;
        background-size: cover;
    }

    .right-side .second-category {
        position: relative;
        flex-basis: 50%;
        background: url(~assets/images/right-side-second.png) no-repeat center center;
        background-size: cover;
        display: flex;
        flex-direction: column;
        justify-content: flex-end;
        align-items: center;
        padding-bottom: 5%;
    }

    .new-badge {
        position: absolute;
        top: 3%;
        right: 3%;
        width: 50px;
        height: 22px;
        color: #fff;
        text-transform: uppercase;
        font-weight: 700;
        background: #000;
        z-index: 1;
    }

    .blackground {
        position: absolute;
        width: 100%;
        height: 100%;
        top: 0;
        left: 0;
        color: #fff;
        z-index: 11;
        text-align: center;
    }

    .triangle {
        position: absolute;
        width: 0;
        height: 0;
        bottom: -10px;
        left: 0;
        border-style: solid;
        border-width: 15px 15px 0 0;
        border-color: #000 transparent transparent transparent;
        z-index: 10;
    }

    .center-side .description .object,
    .right-side .description .object {
        margin-bottom: 10px;
        font-family: "Open Sans", sans-serif;
        font-weight: 300;
        font-size: 14px;
    }

    .center-side .description .object-description,
    .right-side .description .object-description {
        display: flex;
        flex-direction: column;
        margin-bottom: 20px;
        font-weight: 700;
        font-size: 18px;
        text-transform: uppercase;
    }

    .description-shop-now-btn {
        display: flex;
        justify-content: center;
        align-items: center;
        width: 115px;
        height: 40px;
        border-radius: 10%;
        background: #000;
        color: #fff;
        font-size: 12px;
        text-transform: uppercase;
        font-weight: 700;
        overflow: hidden;
        cursor: pointer;
    }

    .right-side .second-category .description {
        font-weight: 700;
        font-size: 14px;
        text-transform: uppercase;
    }
</style>
