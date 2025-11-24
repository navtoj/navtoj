<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.webp';
	import { ModeWatcher } from 'mode-watcher';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

<ModeWatcher themeColors={{ dark: 'black', light: 'white' }} />

{@render children()}
