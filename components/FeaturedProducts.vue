<template>
    <section class="featured-products">
        <div class="container">
            <div class="header">
                featured products
            </div>
            <ul class="product-filters">
                <li class="filter-item">All</li>
                <li class="filter-item">sping-summer</li>
                <li class="filter-item">sweatshirt</li>
                <li class="filter-item">sneakers</li>
                <li class="filter-item">gadgets</li>
                <li class="filter-item">outdoor</li>
            </ul>

            <ul class="product-list">
                <li class="product-item">
                    <div class="image">
                        <img src="~assets/images/product1.png" alt="product image">
                    </div>
                    <div class="description">
                        <div class="product-name">Ted Baker Womens Light</div>
                        <div class="product-firm">Gucci</div>
                        <div class="product-price">
                            <span class="old-price">$120</span>
                            <span class="new-price">$70</span>
                        </div>
                    </div>
                </li>
                <li class="product-item">
                    <div class="image">
                        <img src="~assets/images/product2.png" alt="product image">
                    </div>
                    <div class="description">
                        <div class="product-name">Ted Baker Womens Light</div>
                        <div class="product-firm">Gucci</div>
                        <div class="product-price">
                            <span class="old-price">$120</span>
                            <span class="new-price">$70</span>
                        </div>
                    </div>
                </li>
                <li class="product-item">
                    <div class="image">
                        <img src="~assets/images/product3.png" alt="product image">
                    </div>
                    <div class="description">
                        <div class="product-name">Ted Baker Womens Light</div>
                        <div class="product-firm">Gucci</div>
                        <div class="product-price">
                            <span class="old-price">$120</span>
                            <span class="new-price">$70</span>
                        </div>
                    </div>
                </li>
                <li class="product-item">
                    <div class="image">
                        <img src="~assets/images/product4.png" alt="product image">
                    </div>
                    <div class="description">
                        <div class="product-name">Ted Baker Womens Light</div>
                        <div class="product-firm">Gucci</div>
                        <div class="product-price">
                            <span class="old-price">$120</span>
                            <span class="new-price">$70</span>
                        </div>
                    </div>
                </li>
            </ul>
            <div class="show-more-btn">show more</div>
        </div>

         <div class="prev-slider-btn">
             <i class="fa fa-caret-left" aria-hidden="true"></i>
        </div>   
        <div class="next-slider-btn">
            <i class="fa fa-caret-right" aria-hidden="true"></i>     
        </div>   
    </section>
</template>

<script>
export default {

}
</script>

<style scoped>
    .featured-products {
        position: relative;
        margin-bottom: 90px;
    }

    .header {
        margin-bottom: 50px;
        font-weight: 600;
        font-size: 26px;
        text-transform: uppercase;
        text-align: center;
    }

    .product-filters {
        width: 70%;
        display: flex;
        justify-content: space-around;
        margin: 0 auto 60px;
        font-weight: 600;
        font-size: 18px;
    }

    .product-filters li {
        cursor: pointer;
    }

    .product-list {
        display: flex;
        justify-content: space-between;
    }

    .product-item {
        width: 100%;
        height: 480px;
        margin-right: 30px;
    }

    .product-item:last-child {
        margin-right: 0;
    }

    .image {
        width: 100%;
        margin-bottom: 30px;
        background: #f8f8f8;
    }

    .image img {
        max-width: 100%;
        height: auto;
    }

    .product-name {
        margin-bottom: 10px;
        font-weight: 600;
        font-size: 14px;
    }

    .product-firm {
        margin-bottom: 10px;
        font-weight: 400;
        font-size: 12px;
        color: gray;
    }

    .product-price span:first-child {
        text-decoration: line-through;
    }

    .show-more-btn {
        display: flex;
        justify-content: center;
        align-items: center;
        width: 170px;
        height: 55px;
        margin: 45px auto 0;
        border: 2px solid #eee7da;
        border-radius: 30%;
        font-size: 12px;
        text-transform: uppercase;
        cursor: pointer;
    }

    .prev-slider-btn {
        display: flex;
        justify-content: center;
        align-items: center;
        position: absolute;
        left: 5%;
        top: 50%;
        transform: translateY(-50%);
        width: 45px;
        height: 45px;
        border: 1px solid #e1e1e1;
        border-radius: 50%;
        color: #e1e1e1;
        font-size: 24px;
    }

    .next-slider-btn {
        display: flex;
        justify-content: center;
        align-items: center;
        position: absolute;
        right: 5%;
        top: 50%;
        transform: translateY(-50%);
        width: 45px;
        height: 45px;
        border: 1px solid #e1e1e1;
        border-radius: 50%;
        color: #000;
        font-size: 24px;
    }
</style>