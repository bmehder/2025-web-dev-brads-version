<blockquote>
	<slot></slot>
</blockquote>

<style>
	blockquote {
		quotes: '\201C' '\201D' '\2018' '\2019';
		margin-block: var(--size-1-5);
		padding-block: var(--size-1-5);
		text-align: left;
		text-indent: -3.3rem;
		font-size: var(--size-1-2-5);
		line-height: 1.5;
		font-style: italic;
	}

	blockquote::before {
		content: open-quote;
		font-family: Georgia, 'Times New Roman', Times, serif;
		font-size: var(--size-6);
		line-height: 0.1rem;
		margin-right: 1rem;
		vertical-align: -1.7rem;
	}

	blockquote::after {
		content: close-quote;
	}
</style>
