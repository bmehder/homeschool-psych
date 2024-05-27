<script>
	import { page } from '$app/stores'
</script>

<section>
	<div class="grid">
		{#each $page.data.books as { src, alt }}
			<img class="square" {src} {alt} />
		{/each}
	</div>
</section>