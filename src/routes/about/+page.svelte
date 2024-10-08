<script>
	import Blockquote from '$lib/Blockquote.svelte'
	import Title from '$lib/Title.svelte'
</script>

<Title>About</Title>

<section class="py-4 flow">
	<h2>Lorem ipsum dolor sit.</h2>

	<img
		class="image-shape-right"
		style="shape-outside: url('/man.png');"
		src="/man.png"
		alt="man"
	/>

	<p>
		Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim rem quae nam ipsa
		voluptatum molestiae nesciunt quos, voluptatem quam ut, ducimus sint molestias
		similique dignissimos perspiciatis commodi optio expedita placeat.
	</p>

	<p>
		Lorem ipsum dolor sit, amet consectetur adipisicing elit. Voluptatibus vitae
		impedit minus voluptatum mollitia hic quo ipsa nemo perspiciatis dicta. Cumque,
		saepe quod sint libero ut facilis illo dignissimos natus laboriosam atque.
		Deleniti eveniet vitae minima veniam! At cum atque, ab quia eveniet illum
		exercitationem doloremque, praesentium dolorum dolorem ipsa! Quaerat, possimus?
	</p>

	<p>
		Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero repellendus
		blanditiis, dolore optio facilis amet sunt totam tempore. Fugit illum est quaerat
		iusto quidem necessitatibus, quod accusantium molestiae magnam optio porro nemo.
	</p>

	<p>
		Lorem ipsum dolor, sit amet consectetur adipisicing elit. Beatae quo laborum
		itaque repellendus facere ratione ut.
	</p>

	<p>
		Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod eius earum,
		officiis fuga, culpa, et illo delectus dolorem cumque quia recusandae aliquam
		ipsa. Voluptate nemo eligendi eius?
	</p>
	<p>
		Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsa ipsum quos
		voluptate? Eligendi nulla earum ipsam quaerat. Itaque veniam beatae illum
		tempore, dolorem voluptates commodi distinctio. Labore laboriosam non rem dolor
		amet!
	</p>
</section>

<section class="breakout px-5 py-2 bg-gradient-pink white italic radius-4">
	<Blockquote>
		Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis sunt facere hic,
		perferendis repudiandae aliquam eligendi magni beatae iusto eum blanditiis rem
		quis iste obcaecati et illum! Dolor, hic omnis mollitia alias voluptatum expedita
		ullam.
	</Blockquote>
</section>

<section class="py-4">
	<p class="columns gap-2">
		Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis sunt facere hic,
		perferendis repudiandae aliquam eligendi magni beatae iusto eum blanditiis rem
		quis iste obcaecati et illum! Dolor, hic omnis mollitia alias voluptatum expedita
		ullam. Exercitationem nulla in repellat sequi, commodi error deserunt fugit
		laudantium itaque quisquam aperiam porro voluptatibus provident esse veniam rem
		veritatis consequatur ea, delectus dicta doloremque cum repellendus! Natus sunt
		hic labore sint numquam atque rem, exercitationem et vero id sequi nostrum earum,
		obcaecati nemo autem minus, optio iure iste. Unde rem doloribus doloremque optio,
		tenetur, nemo dolores ea assumenda accusamus impedit, neque tempore. Temporibus,
		optio?
	</p>
</section>

<section class="full-width py-4 bg-blue-900 white flow">
	<h2>Subheading</h2>

	<p class="max-width-100 columns gap-2 white">
		Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia itaque eligendi
		possimus unde, culpa consequatur assumenda ab debitis impedit. Exercitationem,
		necessitatibus labore modi aut voluptatibus asperiores odit quam sit quaerat
		voluptatum atque, sint eius reiciendis officiis ab minima autem. Voluptates
		laudantium ea cupiditate. Ut error a hic accusantium similique saepe debitis
		distinctio possimus id facere. Vero id doloribus quos beatae, ducimus veritatis.
		Corrupti quae ullam beatae nostrum molestiae earum accusantium magnam odit ipsum
		perspiciatis quis velit alias, porro id aspernatur voluptatum a nulla illum
		aperiam ipsam sed nihil, eius fugiat! Quia placeat voluptatem laboriosam
		quibusdam non sapiente, sint necessitatibus ad?
	</p>
</section>

<section class="py-4 flow">
	<h2>Lorem ipsum dolor sit.</h2>

	<div class="columns gap-2 flow">
		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim rem quae nam ipsa
			voluptatum molestiae nesciunt quos, voluptatem quam ut, ducimus sint molestias
			similique dignissimos perspiciatis commodi optio expedita placeat.
		</p>

		<p>
			Lorem ipsum dolor sit, amet consectetur adipisicing elit. Voluptatibus vitae
			impedit minus voluptatum mollitia hic quo ipsa nemo perspiciatis dicta. Cumque,
			saepe quod sint libero ut facilis illo dignissimos natus laboriosam atque.
			Deleniti eveniet vitae minima veniam! At cum atque, ab quia eveniet illum
			exercitationem doloremque, praesentium dolorum dolorem ipsa! Quaerat, possimus?
		</p>

		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero repellendus
			blanditiis, dolore optio facilis amet sunt totam tempore. Fugit illum est
			quaerat iusto quidem necessitatibus, quod accusantium molestiae magnam optio
			porro nemo.
		</p>

		<p>
			Lorem ipsum dolor, sit amet consectetur adipisicing elit. Beatae quo laborum
			itaque repellendus facere ratione ut.
		</p>
	</div>
</section>

<style>
	p {
		max-width: unset;
	}
</style>
