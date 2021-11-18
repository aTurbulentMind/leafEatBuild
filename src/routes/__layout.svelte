<div class="container">
	<nav>
		<ul>
			<li>
				<a href="/">Home</a>
			</li>
		</ul>
	</nav>
	<slot />
</div>

<style>
	* {
		margin: 0;
		padding: 0;
	}

	.container {
		max-width: 800px;
		margin: 50px auto;
	}

	ul {
		display: flex;
		list-style: none;
	}
	li {
		margin-right: 10px;
	}

	/*netlify stuff
	npm i -D @sveltejs/adapter-netlify@next

	to svelte.config.js > import adapter from '@sveltejs/adapter-netlify';
	*/
</style>
