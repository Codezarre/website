<script>
	import { onMount } from 'svelte';
	import { goto } from '$app/navigation';
	onMount(() => goto('/'));
</script>

<main>
	<article class="prose prose-invert text-center">
		<h1 class="text-6xl text-red-700 animate-pulse">Codezerror?</h1>
	</article>
</main>
