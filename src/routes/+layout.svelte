<script>
	import '@picocss/pico'
	import Header from '$lib/Header.svelte'
	import Footer from '$lib/Footer.svelte'
</script>

<div class="wrapper">
  <Header />
  <main class="container">
    <slot />
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