<script>
	export let classes = ''
	export let styles = ''
</script>

<section class={classes} style={styles}>
	<div class="base-layout flow">
		<slot></slot>
	</div>
</section>
