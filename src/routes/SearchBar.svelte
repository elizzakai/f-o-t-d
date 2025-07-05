<script>
	import { topAO3Tags } from './tagsData.js';
	import { topAO3Fandoms } from './fandomData.js';
	import Typeahead from 'svelte-typeahead';
	let search = $state('');
	let fandoms = [];
	let checked = $state(false);
	const searchText = $derived(checked ? `what is/are your fav tag(s)?` : `what is your fandom?`);
	export let state;
	let cur_state = state;
	// $inspect(search);
	// $inspect(checked);
	// $inspect(topAO3Tags);

	// const getFandoms = () => {
	// 	//parse api to grab all fandoms from ao3
	// };
	//
	// const getTags = () => {
	// 	//parse to get all tags
	// };
</script>

<div class="flex flex-col items-center">
	<div class="mt-20 flex">
		<!-- <input class="search-box pl-20" type="search" bind:value={search} placeholder={searchText} /> -->
		<Typeahead
			hideLabel={true}
			label={''}
			bind:value={search}
			placeholder={searchText}
			data={checked ? topAO3Tags : topAO3Fandoms}
			showDropdownOnFocus={true}
		/>

		<svg
			class="search-icon mt-7 ml-4"
			xmlns="http://www.w3.org/2000/svg"
			width="51"
			height="36"
			viewBox="0 0 51 36"
			fill="none"
		>
			<path
				d="M9.8803 2.375C3.40886 3.83629 2.36346 12.7724 2.36346 17.0814C2.36346 20.8305 2.48787 26.3398 7.14691 28.6929C15.7134 33.0194 29.9927 29.7657 32.4308 22.2952C34.2482 16.7267 33.7669 8.98691 26.8122 5.86465C21.4812 3.47135 13.2168 3.37204 7.14691 3.37204"
				stroke="black"
				stroke-width="3"
				stroke-linecap="round"
			/>
			<path
				d="M32.0435 26.9458C35.4823 27.1536 40.2242 29.7897 42.5494 31.1945C44.4226 32.3263 47.6279 32.8777 48.8191 34.3171"
				stroke="black"
				stroke-width="3"
				stroke-linecap="round"
			/>
		</svg>
	</div>
	<div class="mt-2 flex flex-row justify-center">
		<label class="" for="we want tags"
			>tags instead :)<input class="ml-3" type="checkbox" bind:checked /></label
		>
	</div>
	<div class="flex-self-end flex flex-col">
		<button on:click={() => cur_state = 'getfic'}>next</button>
	</div>
	<div class="mt-28 flex flex-col items-center">
		<svg xmlns="http://www.w3.org/2000/svg" width="547" height="8" viewBox="0 0 547 8" fill="none">
			<path
				d="M2.10608 3.9854C9.0554 3.9854 16.0047 3.9854 22.954 3.9854C34.9042 3.9854 46.6736 2.14258 58.5863 2.14258C96.8303 2.14258 135.074 2.14258 173.318 2.14258C216.537 2.14258 259.454 3.9854 302.562 3.9854C349.666 3.9854 396.463 2.14258 443.592 2.14258C464.19 2.14258 484.59 4.563 505.182 4.90682C518.589 5.13067 531.86 5.82823 545.379 5.82823"
				stroke="black"
				stroke-width="3"
				stroke-linecap="round"
			/>
		</svg>
	</div>
</div>

<style>
	@reference "tailwindcss";

	:global([data-svelte-typeahead]) {
		border: none !important;
		border-color: transparent !important;

		box-sizing: border-box;
		font-family: Inter;
		font-size: 17px;

		width: 514.247px;
		height: 85.999px;
		flex-shrink: 0;

		border-radius: 39px !important;
		background: #fdfbf6;

		//padding-left: 20px !important;
	}

	:global([data-svelte-search] input) {
		border: none !important;
		border-color: transparent !important;
		box-sizing: border-box !important;
		font-family: Inter !important;
		font-size: 17px;

		width: 514.247px !important;
		height: 85.999px !important;
		flex-shrink: 0;

		border-radius: 39px !important;
		background: #fdfbf6;

		padding-left: 70px !important;
	}

	button:hover {
		text-decoration: underline;
		color: #9f2ab2;
	}

	.container {
		position: relative;
	}
	.search-box {
		width: 514.247px;
		height: 85.999px;
		flex-shrink: 0;

		border-radius: 39px;
		background: #fdfbf6;
	}

	input {
		border: none;
		border-color: transparent;
		box-sizing: border-box;
		font-family: Inter;
		font-size: 17px;
	}

	.search-icon {
		width: 46.456px;
		height: 31.942px;
		flex-shrink: 0;
		stroke: #000;
		pointer-events: none; /* Make input clickable beneath */
		position: absolute;
	}
</style>
