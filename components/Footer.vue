<template>
	<div>
        <div class="container">
			<div class="flex mx-4 mb-10">
				<div class="w-1/4 px-4 flex items-center">
					<div class="min-w-max mr-4">
						<img width="80" src="~/assets/img/customer-support.png" alt="">
					</div>
					<div class="w-full">
						<h3 class="text-xl font-normal mb-2">24 Customer Support</h3>
						Contact us 24 hours
					</div>
				</div>
				<div class="w-1/4 px-4 flex items-center">
					<div class="min-w-max mr-4">
						<img width="80" src="~/assets/img/authentic-products.png" alt="">
					</div>
					<div class="w-full">
						<h3 class="text-xl font-normal mb-2">Authentic Products</h3>
						Contact us 24 hours
					</div>
				</div>
				<div class="w-1/4 px-4 flex items-center">
					<div class="min-w-max mr-4">
						<img width="80" src="~/assets/img/secure-payment.png" alt="">
					</div>
					<div class="w-full">
						<h3 class="text-xl font-normal mb-2">Secure Payment</h3>
						Contact us 24 hours
					</div>
				</div>
				<div class="w-1/4 px-4 flex items-center">
					<div class="min-w-max mr-4">
						<img width="80" src="~/assets/img/best-price.png" alt="">
					</div>
					<div class="w-full">
						<h3 class="text-xl font-normal mb-2">Best Price & Offers</h3>
						Contact us 24 hours
					</div>
				</div>
			</div>

		</div>
		<div class="bg-gray-200 py-20">
			<div class="container">
				<div class="flex">
					<div class="w-3/5 pr-10">
						<Logo/>
						<p class="my-8">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Vero dolor voluptatem tempore corrupti sint autem omnis, iusto voluptate unde animi at voluptas optio cupiditate! Numquam sit possimus exercitationem beatae architecto.</p>
						<div class="flex">
							<a href="#" class="mr-4"><img src="~/assets/img/playstore.png" alt=""></a>
							<a href="#"><img src="~/assets/img/appstore.png" alt=""></a>
						</div>
					</div>
					<div class="w-1/5 pl-6">
						<h3 class="text-2xl mb-6">About Us</h3>
						<ul class="leading-loose">
							<li><nuxt-link to="/">About Karte</nuxt-link></li>
							<li><nuxt-link to="/">Contact</nuxt-link></li>
							<li><nuxt-link to="/">Career</nuxt-link></li>
							<li><nuxt-link to="/">Terms & Conditions</nuxt-link></li>
							<li><nuxt-link to="/">Category</nuxt-link></li>
							
						</ul>
					</div>
					<div class="w-1/5 pl-6">
						<h3 class="text-2xl mb-6">Info</h3>
						<ul class="leading-loose">
							<li><nuxt-link to="/">Information</nuxt-link></li>
							<li><nuxt-link to="/">Shipping</nuxt-link></li>
							<li><nuxt-link to="/">Payment</nuxt-link></li>
							<li><nuxt-link to="/">Return</nuxt-link></li>
							<li><nuxt-link to="/">Blog</nuxt-link></li>
							
						</ul>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
export default {
	name: 'Footer',
}
</script>

<style scoped>

</style>