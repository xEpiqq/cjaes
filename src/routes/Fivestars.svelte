<script>
  import Hero from './Hero.svelte';


  import Navbar from './Navbar.svelte';
</script>

<div class="flex justify-center items-center flex-col">
<!-- xs -->
<div class="rating rating-xs">
    <input type="radio" name="rating-5" class="mask mask-star-2 bg-yellow-400" />
    <input type="radio" name="rating-5" class="mask mask-star-2 bg-yellow-400" />
    <input type="radio" name="rating-5" class="mask mask-star-2 bg-yellow-400" />
    <input type="radio" name="rating-5" class="mask mask-star-2 bg-yellow-400" />
    <input type="radio" name="rating-5" class="mask mask-star-2 bg-yellow-400" checked/>
</div>
<!-- sm -->
<div class="rating rating-sm">
    <input type="radio" name="rating-6" class="mask mask-star-2 bg-yellow-400" />
    <input type="radio" name="rating-6" class="mask mask-star-2 bg-yellow-400" />
    <input type="radio" name="rating-6" class="mask mask-star-2 bg-yellow-400" />
    <input type="radio" name="rating-6" class="mask mask-star-2 bg-yellow-400" />
    <input type="radio" name="rating-6" class="mask mask-star-2 bg-yellow-400" checked />
</div>
<!-- md -->
<div class="rating rating-md">
    <input type="radio" name="rating-7" class="mask mask-star-2 bg-yellow-400" />
    <input type="radio" name="rating-7" class="mask mask-star-2 bg-yellow-400" />
    <input type="radio" name="rating-7" class="mask mask-star-2 bg-yellow-400" />
    <input type="radio" name="rating-7" class="mask mask-star-2 bg-yellow-400" />
    <input type="radio" name="rating-7" class="mask mask-star-2 bg-yellow-400" checked/>
</div>
<!-- lg -->
<div class="rating rating-lg">
    <input type="radio" name="rating-8" class="mask mask-star-2 bg-yellow-400" />
    <input type="radio" name="rating-8" class="mask mask-star-2 bg-yellow-400" />
    <input type="radio" name="rating-8" class="mask mask-star-2 bg-yellow-400" />
    <input type="radio" name="rating-8" class="mask mask-star-2 bg-yellow-400" />
    <input type="radio" name="rating-8" class="mask mask-star-2 bg-yellow-400" checked/>
</div>

</div>
