<script>
	import Header from '$lib/components/Header.svelte';
</script>

<div class="hero min-h-screen flex flex-col">
	<Header />
	<div class="hero-content w10/12 self-start justify-self-center">
		<div>
			<h1 class="text-5xl lg:text-7xl pl-12 font-bold text-white font-poppins leading-tight">
				Building digital avenues to communicate with your audience.
			</h1>
			<!-- <p class="text-2xl py-6 text-white font-poppins">Providing web development services to startups and SME’s across Scotland.</p> -->
		</div>
	</div>
</div>

<style>
	.hero {
		background: url('/images/hero-bg.webp');
		background-size: cover;
		background-repeat: no-repeat;
	}
</style>
