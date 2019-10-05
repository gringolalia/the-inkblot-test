<template lang="pug">
div
	.section
		img(alt='A Onça Sulfúrica ', src='../assets/alchemy-sulphuric.svg')
		h1.mt-5 Polvo na Própria Tinta!
		h2 Bom Dia, Meia-Noite
		a.ink-button.black.with.dignity.left-drawer-trigger(href="/about" style="margin-bottom: 70px") Imprint Me
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
.home {
	margin-top: 125px;
	text-align: center;
}
</style>
