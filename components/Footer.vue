<template>
    <footer>
        <div class="content-wrapper">
            <div class="copyright">
                &copy; Copyright e-commerce  1.0. 2022 Designed by Psdfreebies.com
            </div>
            <Logo />
        </div>
    </footer>
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
footer {
    width: 100%;
    height: 172px;
    background: #fff;
    text-align: center;
}

.copyright {
    margin-top: 35px;
    margin-bottom: 45px;
    color: #000;
    font-size: 14px;
    font-weight: 300;
    color: #aaa;
}

.content-wrapper {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.logo {

}


</style>
