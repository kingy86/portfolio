<script>
    // your script goes here
</script>

<style>
    /* your styles go here */
</style>

<div class="drawer drawer-end">
  <input id="responsive-menu" type="checkbox" class="drawer-toggle" /> 
    <div class="drawer-content flex flex-col">
      <!-- Navbar -->
      <div class="w-full navbar">
        <div class="flex-none lg:hidden">
          <label for="responsive-menu" aria-label="open sidebar" class="btn btn-square btn-ghost text-white">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" class="inline-block w-6 h-6 stroke-current"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path></svg>
          </label>
        </div>

        <div class="flex-none max-lg:hidden">
          <ul class="menu menu-horizontal px-1">
            <li class="font-semibold text-white text-lg"><a>About</a></li>
            <li class="font-semibold text-white text-lg"><a>Services</a></li>
            <li class="font-semibold text-white text-lg"><a>Contact</a></li>
          </ul>
        </div>
      </div>

    </div>
    <div class="drawer-side z-1">
      <label for="responsive-menu" aria-label="close sidebar" class="drawer-overlay">
       <p class="drawer-toggle text-black">Close</p>
      </label> 
      
      <ul class="menu p-4 w-80 min-h-full bg-orange-600">
        <li class="font-semibold text-white text-lg"><a>About</a></li>
        <li class="font-semibold text-white text-lg"><a>Services</a></li>
        <li class="font-semibold text-white text-lg"><a>Contact</a></li>
      </ul>
    </div>
</div>