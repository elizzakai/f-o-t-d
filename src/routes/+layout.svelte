<script lang="ts">
	import '../app.css';
	import Header from './Header.svelte';
	import About from './About.svelte';
	import AboutBox from './AboutBox.svelte';
	import CreditsBox from './CreditsBox.svelte';
	// import Blurb from './Blurb.svelte';
	let { children } = $props();
</script>

<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<Header />
{@render children()}
<AboutBox />
<About />
<CreditsBox />

<style>
	h1 {
		font-size: medium;
		text-align: center;
	}

	h1:hover {
		color: rgb(72, 106, 203);
		font-family: sans-serif;
	}

	.blurb {
		width: 742px;
		height: 450px;
		width: 50%; /* or any fixed width */
		margin: auto; /* centers horizontally */
		box-sizing: border-box;
		flex-shrink: 0;
		border-radius: 31px;
		background-color: #f5d09b;
	}

	/* .pad {
		padding-top:40px;
	} */

	.parent {
		display: flex;
		width: 1440px;
		height: 717px;
		padding: 0px 100px;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		gap: 206px;
		flex-shrink: 0;
	}

	:global(body) {
		background-color: rgba(255, 238, 214, 1);
		/* text-align: center; */
	}
</style>
