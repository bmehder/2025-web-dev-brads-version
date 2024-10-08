<script>
	export let src = ''
	export let title = ''
	export let description = ''
</script>

<li class="flow relative p-2 bg-light radius-4">
	<img class="absolute" {src} width="56" height="56" alt="" />
	<h3 class="blue-900">{title}</h3>
	<p>{description}</p>
	<div><a class="bold" href="/blog">Read More &raquo;</a></div>
</li>

<style>
	img {
		max-width: 3.5rem;
		top: -2rem;
	}

	p {
		font-size: 1.1rem;
	}
</style>
