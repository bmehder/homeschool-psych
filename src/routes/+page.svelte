<script>
	import '@picocss/pico'
	import '$lib/utils.css'
	import Seo from '$lib/SEO.svelte'
	import Header from '$lib/Header.svelte'
	import Introduction from '$lib/Introduction.svelte'
	import Books from '$lib/Books.svelte'
	import Footer from '$lib/Footer.svelte'
</script>

<Seo />

<div class="wrapper">
	<Header />

	<main class="container">
		<section>
			<Introduction />
		</section>

		<section>
			<Books />
		</section>
	</main>

	<Footer />
</div>

<style>
  .wrapper {
    min-block-size: 100dvh;
    display: grid;
    grid-template-rows: 1fr auto;
  }

  main {
    padding-block-start: 8rem;
    padding-block-end: 2rem;
  }
</style>