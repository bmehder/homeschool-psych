<script>
	import Logo from '$lib/Logo.svelte'
	import Nav from '$lib/Nav.svelte'	
</script>

<header>
	<div class="container">
		<Logo />
		<Nav />
	</div>
</header>

<style>
	header {
		inline-size: 100%;
		position: fixed;
		padding-block: 1rem;
		background-color: #13171f;
		box-shadow: 0 0.5rem 1rem rgba(0, 0, 0, 0.1);

		& div {
			display: flex;
			flex-wrap: wrap;
			justify-content: space-between;
			align-items: center;
		}
	}
</style>
