<template lang="pug">
#app
	.ink-drawer(data-mode='over')
		.left-drawer(style="background:gray")
			| A Drawing of a Room

	nav.ink-navigation(style="position: fixed; top: 0; width: 100%;")
		ul.menu.horizontal.large.black.with.dignity.align-left
			li.heading
				a(href='#')
					i.fas.fa-sun.fa-2x
					| &nbsp;&nbsp;Engenhocas Cariocas
			li
				a(href='#')
					| Hemeroteca
					i.material-icons expand_more

				ul.submenu(style="z-index: 1001; width: 250px")
					li
						a(href='#') Howling Woof

					li
						a(href='#') Muddy Waters
					li.separator-above
					li
						a(href='#') John Lee Hooker

					li
						a(href='#') Blind Lemon Jefferson

					li
						a(href='#') Robert Crossroads Johnson

			li
				a(href='#') Sobre Pobres
			li
				a(href='#') Sobre Nobres
			li
				a.left-drawer-trigger.pull-right.with.dignity
					i.material-icons menu
					| &nbsp;O Cardápio


	#main-content.content-drawer.ink-grid(style="z-index: 69;")
		router-view
</template>

<style lang="scss">
#app {
	font-family: 'News Cycle', Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
}
#nav {
	padding: 30px;
	a {
		font-weight: bold;
		color: #2c3e50;
		&.router-link-exact-active {
			color: #42b983;
		}
	}
}
</style>
