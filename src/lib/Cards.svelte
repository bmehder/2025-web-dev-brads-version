<script>
	import AutoFit from './AutoFit.svelte'
	import Card from './Card.svelte'

	export let cards = []
</script>

<section class="full-width bg-gradient-light py-8">
	<AutoFit classes="gap-3">
		<div class="px-2 py-4 bg-gradient-pink white radius-4">
			<h2 class="h1">Check out our most popular categories!</h2>
		</div>
		<ul class="display-contents list-style-none">
			{#each cards as { title, src, description }}
				<Card {title} {src} {description} />
			{/each}
		</ul>
	</AutoFit>
</section>
