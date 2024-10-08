<blockquote>
	<slot></slot>
</blockquote>

<style>
	blockquote {
		quotes: '\201C' '\201D' '\2018' '\2019';
		margin-block: var(--size-1-5);
		/* margin-inline: var(--size-0-5); */
		padding-block: var(--size-1-5);
		/* padding-inline: var(--size-0-5); */
		text-align: left;
		text-indent: -3.3rem;
		font-size: 1.25rem;
		line-height: 1.5;
		font-style: italic;
	}

	blockquote::before {
		content: open-quote;
		color: var(--secondary);
		font-family: Georgia, 'Times New Roman', Times, serif;
		font-size: 6rem;
		line-height: 0.1rem;
		margin-right: 1rem;
		vertical-align: -1.7rem;
	}

	blockquote::after {
		content: close-quote;
	}
</style>
