<script>
	let isChecked = false

	const uncheckInput = () => (isChecked = false)
</script>

<header class="content-grid py-2">
	<div class="inner">
		<div class="non-nav-wrapper">
			<a href="/" on:click={uncheckInput}>
				<img src="/logo-dark.svg" width="112" height="29" alt="dark logo" />
			</a>
			<div class="hamburger">
				<input type="checkbox" id="dropdown" bind:checked={isChecked} />
				<label for="dropdown" class="dropdown">
					<span class="hamburger">
						<span class="icon-bar top-bar"></span>
						<span class="icon-bar middle-bar"></span>
						<span class="icon-bar bottom-bar"></span>
					</span>
				</label>
			</div>
		</div>
		<nav>
			<ul class="nav-list">
				<li>
					<a on:click={uncheckInput} href="/">Home</a>
				</li>
				<li>
					<a on:click={uncheckInput} href="/about">About</a>
					<ul class="sublist flow-1">
						<li><a href="/">One</a></li>
						<li><a href="/">Two</a></li>
						<li><a href="/">Three Three Three</a></li>
					</ul>
				</li>
				<li>
					<a on:click={uncheckInput} href="/blog">Blog</a>
				</li>
				<li>
					<a on:click={uncheckInput} href="/contact">Contact</a>
				</li>
				<li>
					<a on:click={uncheckInput} class="button bg-blue-900 white" href="/blog"
						>Get Started</a
					>
				</li>
			</ul>
		</nav>
	</div>
</header>

<style>
	/* Default element resets */
	ul {
		list-style: none;
	}

	img {
		max-width: 112px;
	}

	.button:hover {
		background-image: var(--gradient-pink);
	}

	/* Hamburger */
	input[type='checkbox'] {
		display: none;
	}

	input[type='checkbox'] + label {
		& .icon-bar {
			display: block;
			width: 2rem;
			height: 3px;
			background-color: var(--blue-900);
			margin: 0.25rem;
			transition: all 0.2s;
		}
		& .top-bar {
			transform: rotate(0);
		}
		& .middle-bar {
			opacity: 1;
		}
	}

	input[type='checkbox']:checked + label {
		& .top-bar {
			transform: rotate(45deg);
			transform-origin: 22% 0%;
		}
		& .middle-bar {
			opacity: 0;
		}
		& .bottom-bar {
			transform: rotate(-45deg);
			transform-origin: 10% 90%;
		}
	}

	/* Mobile first */
	.inner,
	.nav-list {
		display: flex;
		flex-direction: column;
		gap: 1.5rem;
	}

	.non-nav-wrapper {
		display: flex;
		justify-content: space-between;
		align-items: center;
		gap: 1.5rem;
	}

	.nav-list .sublist {
		padding: 1rem;
	}

	/* Mobile only */
	@media (width < 48rem) {
		nav {
			display: none;
		}

		header:has(input:checked) nav {
			min-height: 100dvh;
			display: block;
		}

		.nav-list > li:not(:last-child) {
			padding-bottom: 1rem;
			border-bottom: 1px solid var(--blue-600);
		}
	}

	/* Desktop only */
	@media (width >= 48rem) {
		.inner,
		.nav-list {
			flex-direction: row;
			justify-content: space-between;
			align-items: center;
		}

		.hamburger,
		.nav-list .sublist {
			display: none;
		}

		.nav-list > li {
			position: relative;
		}

		.nav-list > li:hover .sublist {
			display: block;
		}

		.nav-list .sublist {
			position: absolute;
			left: -1rem;
			width: max-content;
			background-color: white;
		}
	}
</style>
