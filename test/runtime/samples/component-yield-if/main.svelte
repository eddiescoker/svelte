<script>
	import Widget from './Widget.svelte';

	export let widget;
	export let data = "Hello";
</script>

<div>
	<Widget bind:this={widget}>{data}</Widget>
</div>