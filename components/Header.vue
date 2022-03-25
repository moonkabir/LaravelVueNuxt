<template>
	<div>
        <ul>
			<li> <nuxt-link to="/">Home</nuxt-link> </li>
			<li> <nuxt-link to="/about">About</nuxt-link> </li>
		</ul>
		<div class="container flex justify-between items-center py-6">
			<nuxt-link to="/" class="flex font-size-32 font-medium items-center">
				<img class="mr-3" src="~/assets/img/logo.png" alt="">Bengal shop
			</nuxt-link>
			<div class="w-96">
				<div class="border border-gray-100 p-1 flex rounded-full items-center">
					<div class="min-w-max px-3">
						<img src="~/assets/img/search.png" alt="">
					</div>
					<input class="w-full px-3 py-1 focus:outline-none" type="search" placeholder="Search here .....">
					<button class="bg-gray bs-button-bg px-6 rounded-full py-2 text-white" type="submit">
						Search
					</button>
				</div>
			</div>
			<div class="min-w-max flex items-center">
				<nuxt-link to="/"><span class="bs-icon-box rounded-full hover:bg-gray-200 inline-block flex items-center justify-center"><img src="~/assets/img/heart.png" alt=""></span></nuxt-link>
				<nuxt-link to="/" class="relative mx-4"><span class="bs-icon-box rounded-full hover:bg-gray-200 inline-block flex items-center justify-center"><img src="~/assets/img/u_shopping-bag.png" alt=""></span><span class="absolute bg-red-600 w-4 h-4 top-0 right-0 rounded-full text-xs flex items-center justify-center">0</span></nuxt-link>
				<nuxt-link to="/" class="flex items-center"><span class="bs-icon-box rounded-full hover:bg-gray-200 inline-block flex items-center justify-center"><img src="~/assets/img/user.png" alt=""></span><span>Account</span></nuxt-link>
			</div>
		</div>
	</div>
</template>

<script>
export default {
	name: 'Header',
}
</script>

<style scoped>

</style>