<script>
	import Title from '$lib/Title.svelte'

	export let data
</script>

<Title>Blog</Title>

<section class="py-4 flow">
	<h2>Recent Articles</h2>

	{#each data.posts as post}
		<h3 class="capitalize">
			<a href="/blog/{post.id}">{post.title}</a>
		</h3>
	{/each}
</section>
