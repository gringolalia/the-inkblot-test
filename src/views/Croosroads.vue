<template lang="pug">
div
	.section
		img.bottom-space(alt='A Onça Sulfúrica ', src='../assets/alchemy-sulphuric.svg')
		h1 Sobre Nobres e Pobres
		h2 Addio Mondo Crudele
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
