<script>
	import Heading from "$lib/components/custom/heading.svelte";
import Stats from "$lib/components/custom/home/stats.svelte";
</script>

<main class="flex flex-col items-center justify-center">
	<section class="flex h-screen flex-col items-center justify-center text-center space-y-3">
		<h1 class="brand heading text-4xl md:text-7xl uppercase font-thin">
			lyallpur <br /> khalsa college
		</h1>
		<br />
		<span class="text-lg md:text-2xl font-semibold tracking-wide text-slate-400"
			>Over 100 years of Selfless Service to Humanity.</span
		>
		<p class="font-medium text-slate-600">
			( 8J72+555, Mohyal Nagar, Jalandhar )
		</p>
	</section>
	<Stats />
	<!-- <Heading title="Our departments" url="/departments" /> -->
</main>
