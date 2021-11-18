<script>
	import Nav from '$lib/Nav.svelte';
</script>

<div class="container">
	<div class="logo"><img src="/src/assets/img/LogoTransparentDark.png" alt=""></div>

	<Nav />

	<slot />

	
</div>

<style lang="scss">
	@import 'vari';
	

	* {
		margin: -8px;
		overflow-x: hidden;
	}

	.container {
		
		color: $textColorMain;
		background: rgb(11, 8, 14);
		font-family: 'Amiko', sans-serif;
	}

	.logo {
		overflow-y:hidden;
		margin-top: 5px;

		img {
		width: 80%;
		height: 80%;
		
	}
	}

	
	
		
</style>