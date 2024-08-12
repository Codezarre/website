<script>
	import * as Icon from 'svelte-awesome-icons';
</script>

<main>
	<article class="print:hidden prose prose-invert text-center">
		<h1
			class="
			brightness-150 text-transparent text-6xl
			bg-clip-text bg-gradient bg-gradient-to-r
			from-[#50A3F2] to-[#2A489D] !print:text-black"
		>
			Codezarre.
		</h1>
		<span class="flex gap-5 justify-center">
			<a href="/youtube"><Icon.YoutubeBrand size="30" /></a>
			<a href="/github"><Icon.GithubBrand size="30" /></a>
			<a href="/x"><Icon.XTwitterBrand size="30" /></a>
			<a href="/fosstodon"><Icon.MastodonBrand size="30" /></a>
			<a href="/discord" style="display: none"><Icon.DiscordBrand size="30" /></a>
		</span>
	</article>
	<div data-nosnippet class="hidden print:block text-left">
		<article class="text-xl leading-snug">
			<h1 class="text-2xl">Codezarre's Hidden Message</h1>
			<pre>			
				Beautiful is better than ugly.
				Explicit is better than implicit.
				Simple is better than complex.
				Complex is better than complicated.
				Flat is better than nested.
				Sparse is better than dense.
				Readability counts.
				Special cases aren't special enough to break the rules.
				Although practicality beats purity.
				Errors should never pass silently.
				Unless explicitly silenced.
				In the face of ambiguity, refuse the temptation to guess.
				There should be one—and preferably only one—obvious way to do it.
				Although that way may not be obvious at first unless you're Dutch.
				Now is better than never.
				Although never is often better than *right* now.
				If the implementation is hard to explain, it's a bad idea.
				If the implementation is easy to explain, it may be a good idea.
				Namespaces are one honking great idea—let's do more of those!
			</pre>
			<p>By Tim Peters (PEP 20)</p>
		</article>
	</div>
</main>

<style>
	a {
		transition: transform 2.5s;
	}

	a:hover {
		transition: transform 1s;
		transform: rotate(360deg);
	}

	pre {
		tab-size: 0;
		font: inherit;
	}
</style>
