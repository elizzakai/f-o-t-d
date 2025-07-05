<script>
	import SearchBar from './SearchBar.svelte';
	export let state = 'start';
</script>

<container class="parent items-center">
	<div class="blurb flex justify-center">
		{#if state == 'start'}
			<SearchBar/>
		{:else if state == 'getfic'}
			<Confirm/>
		{:else}
		{/if}
	</div>
</container>

<style>
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
</style>
