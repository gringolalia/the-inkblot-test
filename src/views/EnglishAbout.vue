<template lang="pug">
div
	.section
		img.bottom-space(alt='A Onça Sulfúrica ', src='../assets/alchemy-sulphuric.svg')
		.hello
			h1.mt-5 All About The Router 
			h2 Portuguese User Experience
			a.ink-button.black.with.dignity.left-drawer-trigger(href="/about" style="margin-bottom: 70px") Footprint Me

	.section
		.ink-grid(style="z-index: -1")
			.column-group.horizontal-gutters.top-space
				.all-33
					figure.ink-image
						img(src="../assets/hindenburger.jpg" width="400px")
						figcaption.over-top.dark
							| Danger, Danger
				.all-33
					figure.ink-image
						img(src="../assets/hindenburger.jpg" width="400px")
						figcaption.over-top.dark
							| Stranger, Stranger
				.all-33
					figure.ink-image
						img(src="../assets/hindenburger.jpg" width="400px")
						figcaption.over-top.dark
							| Stranger, Stranger

			.column-group.horizontal-gutters.top-space
				.all-33
					figure.ink-image
						img(src="../assets/hindenburger.jpg" width="400px")
						figcaption.over-top.dark
							| Money Changer Ranger
				.all-33
					figure.ink-image
						img(src="../assets/hindenburger.jpg" width="400px")
						figcaption.over-top.dark
							| Stranger, Stranger
				.all-33
					figure.ink-image
						img(src="../assets/hindenburger.jpg" width="400px")
						figcaption.over-top.dark
							| Stranger, Stranger

</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
	name: 'home',
	components: {
		HelloWorld
	}
}
</script>

<style>
.section {
	height: 100vh;
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
	text-align: center;
}
</style>
