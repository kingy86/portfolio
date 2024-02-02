<script>
  import "tailwindcss/tailwind.css";

  import Hero from "$lib/components/Hero.svelte"
  
</script>

<div class="app">
<Hero />
<main>
<slot />
</main>

</div>
