<script>
	import 'cheekycss'
	import '$lib/style.css'
	import Header from '$lib/Header.svelte'
	import Footer from '$lib/Footer.svelte'
</script>

<div class="wrapper">
	<Header />
	<main class="content-grid">
		<slot></slot>
	</main>
	<Footer />
</div>
