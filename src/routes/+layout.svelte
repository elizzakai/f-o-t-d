<script lang="ts">
	import '../app.css';

	let { children } = $props();
</script>

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
		width: 50%;       /* or any fixed width */
		margin: auto;     /* centers horizontally */
		box-sizing: border-box;
		flex-shrink: 0;
		border-radius: 31px;
		background-color: #F5D09B;
		
	}
	
	:global(body) {
		background-color: rgba(255, 238, 214, 1);
	}
</style>


<container class="parent">parent contains everything
<h1>hello there, my man you are the base bones! </h1>
<div class="blurb">
</div>
</container>

{@render children()}
