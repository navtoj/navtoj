<script lang="ts">
	import '../app.css';
	let { children } = $props();

	import { ModeWatcher } from 'mode-watcher';
</script>

<ModeWatcher themeColors={{ dark: 'black', light: 'white' }} />

{@render children()}
