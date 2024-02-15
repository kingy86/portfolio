<script>
    import Header from "$lib/components/Header.svelte"
</script>


<style>
    .hero {
      background: url("/images/hero-bg.webp");
      background-size: cover;
      background-repeat: no-repeat;
    }
</style>

<div class="hero min-h-screen flex flex-col">
  <Header />
  <div class="hero-content w-8/12">
    <div>
      <h1 class="text-5xl font-bold text-white font-poppins leading-tight">Building digital avenues to communicate with your audience.</h1>
      <p class="text-2xl py-6 text-white font-poppins">Providing web development services to startups and SME’s across Scotland.</p>
    </div>
  </div>
</div>