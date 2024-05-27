<script>
  const items = [
		{
			href: 'https://x.com/homeschoolpsych',
			src: '/socials/twitter.png',
			alt: 'x logo',
		},
		{
			href: 'https://www.facebook.com/homeschoolpsych/',
			alt: 'facebook logo',
			src: '/socials/facebook.png',
		},
	]
</script>

<nav>
	<ul>
		{#each items as { href, src, alt }}
			<li>
				<a {href} target="_blank"><img {src} {alt} /></a>
			</li>
		{/each}
	</ul>
</nav>

<style>
  img {
		inline-size: 2rem;
	}
</style>