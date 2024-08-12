<script>
	import '../app.css';
	let { children } = $props();
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
	}

	div {
		background-size: min(50vw, 50vh);
	}
</style>
