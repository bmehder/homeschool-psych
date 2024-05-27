<script>
	const books = [
		{
			src: '/books/homeschool-psych-and-student-workbook.jpg',
			alt: 'Homeschool Psych and Student Workbook',
		},
		{
			src: '/books/psychology-a-christian-perspective-and-teachers-guide.jpg',
			alt: 'Psychology: A Christian Perspective',
		},
		{
			src: '/books/bring-your-christian-worldview-to-psychology-class.jpg',
			alt: 'Bring Your Christian Worldview To Psychology Class',
		},
		{
			src: '/books/its-not-that-simple-natty-rose.jpg',
			alt: "It's Not That Simple, Natty Rose.",
		},
	]
</script>

<div class="grid">
	{#each books as { src, alt }}
		<img class="square" {src} {alt} />
	{/each}
</div>