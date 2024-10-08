<script>
	import Title from '$lib/Title.svelte'

	export let data
</script>

<Title>
	{data.post.title}
</Title>

<section class="py-4 flow">
	<h2>Heading Two</h2>
	<p>{data.post.body}</p>
</section>
