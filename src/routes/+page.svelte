<script>
	import Hero from '$lib/Hero.svelte'
	import Cards from '$lib/Cards.svelte'

	export let data
</script>

<Hero />
<Cards cards={data.cards} />
