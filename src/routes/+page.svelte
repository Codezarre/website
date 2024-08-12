<script>
	import * as Icon from 'svelte-awesome-icons';
</script>

<main>
	<article class="prose prose-invert text-center">
		<h1
			class="
			brightness-150 text-transparent text-6xl
			bg-clip-text bg-gradient bg-gradient-to-r
			from-[#50A3F2] to-[#2A489D] drop-shadow-xl"
		>
			Codezarre.
		</h1>
		<span class="flex gap-5 justify-center drop-shadow-xl">
			<a href="/youtube"><Icon.YoutubeBrand size="30" /></a>
			<a href="/github"><Icon.GithubBrand size="30" /></a>
			<a href="/x"><Icon.XTwitterBrand size="30" /></a>
			<a href="/fosstodon"><Icon.MastodonBrand size="30" /></a>
			<a href="/discord" style="display: none"><Icon.DiscordBrand size="30" /></a>
		</span>
	</article>
</main>
