<script>
	import { page } from '$app/stores'
</script>

<nav>
	<ul>
		{#each $page.data.socials as { href, src, alt }}
			<li>
				<a {href} target="_blank"><img {src} {alt} /></a>
			</li>
		{/each}
	</ul>
</nav>