<template>
	<div class="container-wrapper">
		<Header />

		<Hero />

		<Categories />

		<WeOffer />

		<ProductTypes />

		<FeaturedProducts />

		<Subscribe />

		<Blog />

		<Info />

		<Footer />
	</div>
</template>

<script>
import Header from '@/components/Header.vue';
import Footer from '@/components/Footer.vue';
import Hero from '@/components/Hero.vue';
import Categories from '@/components/Categories.vue';
import WeOffer from '@/components/WeOffer.vue';
import ProductTypes from '@/components/ProductTypes.vue';
import FeaturedProducts from '@/components/FeaturedProducts.vue';
import Subscribe from '@/components/Subscribe.vue';
import Blog from '@/components/Blog.vue';
import Info from '@/components/Info.vue';

export default {
	components: {
		Header,
		Footer,
		Hero,
		Categories,
		WeOffer,
		ProductTypes,
		FeaturedProducts,
		Subscribe,
		Blog,
		Info
	}
};
</script>

<style>
</style>
