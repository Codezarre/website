<script>
	import { inject } from '@vercel/analytics';

	import '../app.css';

	let { children } = $props();

	inject();
</script>

<div
	class="
	bg-[url('/Codezarre.png')] flex items-center justify-center bg-right-bottom
	bg-fixed bg-no-repeat size-full
	"
>
	{@render children()}
</div>

<style lang="postcss">
	:global(html) {
		height: 100%;
	}

	:global(*) {
		box-sizing: border-box;
	}

	:global(body) {
		margin: 0;
		background-color: #030018;
		height: 100%;

		@media print {
			background-color: white;
		}
	}

	div {
		background-size: min(50vw, 50vh);
		@media print {
			background: none;
		}
	}
</style>
