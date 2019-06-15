<template>
	<div class="container">
		<Header />

		<Hero />

		<section class="offer"></section>

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

export default {
	components: {
		Header,
		Footer,
		Hero
	}
};
</script>

<style>
</style>
