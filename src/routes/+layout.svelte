<script lang="ts">
	import '../app.css';

	let { children } = $props();
</script>

<svelte:head>
	<title>Puar</title>
	<link
		rel="icon"
		href="
https://emojicdn.elk.sh/🫐"
	/>
</svelte:head>

{@render children()}
