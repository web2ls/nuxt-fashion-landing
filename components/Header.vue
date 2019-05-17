<template>
    <header>
        <Logo />

        <nav>
            <ul>
                <li>home</li>
                <li>shop</li>
                <li>women</li>
                <li>men</li>
                <li>find store</li>
            </ul>
        </nav>

        <div class="nav-controls">
            <div class="nav-controls-item cart">
                <img src="~assets/images/cart.png" alt="shopping cart icon">
            </div>
            <div class="nav-controls-item search">
                <img src="~assets/images/search.png" alt="search icon">
            </div>
            <div class="nav-controls-item menu">
                <img src="~assets/images/icon.png" alt="menu icon">
            </div>
        </div>
    </header>
</template>

<script>
import Logo from '@/components/Logo.vue';

export default {
    components: {
        Logo
    }
}
</script>

<style scoped>
header {
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    justify-content: space-around;
    align-items: center;
    padding: 45px 0 25px 0;
    border-bottom: 5px solid #f3ebdc;
}

nav {
    flex-basis: 40%;
}

ul {
    display: flex;
}

li {
    margin-right: 5%;
    font-size: 12px;
    font-weight: 300;
    color: #000;
    text-transform: uppercase;
    cursor: pointer;
}

li:last-child {
    margin-right: 0;
}

.nav-controls {
    display: flex;
    flex-wrap: nowrap;
    flex-direction: row;
    justify-content: space-between;
    flex-basis: 10%;
}

.nav-controls-item {
    width: 15px;
    height: 15px;
    margin-right: 3%;
    cursor: pointer;
}

.nav-controls-item:last-child {
    margin-right: 0;
}

.nav-controls-item img {
    max-width: 100%;
    height: auto;
}
</style>
