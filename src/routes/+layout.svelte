<script lang="ts">
	import '@fontsource/outfit/100.css';
	import '@fontsource/outfit/200.css';
	import '@fontsource/outfit/300.css';
	import '@fontsource/outfit/400.css';
	import '@fontsource/outfit/500.css';
	import '@fontsource/outfit/600.css';
	import '@fontsource/outfit/700.css';
	import '@fontsource/outfit/800.css';
	import '@fontsource/outfit/900.css';

	import '../app.css';
	import { ModeWatcher } from 'mode-watcher';

	let { children } = $props();
</script>

<ModeWatcher />

<div class="flex h-dvh flex-col">
	{@render children()}
</div>
