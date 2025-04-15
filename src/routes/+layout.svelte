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
</style>

<h1>hello there, my man you are the base bones! 
im boned down</h1>

{@render children()}
