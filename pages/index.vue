<template>
	<div class="container">
		<Header />

		<Hero />

		<Categories />

		<WeOffer />

		<section class="product-types"></section>

		<section class="featured-products"></section>

		<section class="subcribe"></section>

		<section class="blog-news"></section>

		<section class="summary-info"></section>

		<Footer />
	</div>
</template>

<script>
import Header from '@/components/Header.vue';
import Footer from '@/components/Footer.vue';
import Hero from '@/components/Hero.vue';
import Categories from '@/components/Categories.vue';
import WeOffer from '@/components/WeOffer.vue';

export default {
	components: {
		Header,
		Footer,
		Hero,
		Categories,
		WeOffer,
	}
};
</script>

<style>
</style>
