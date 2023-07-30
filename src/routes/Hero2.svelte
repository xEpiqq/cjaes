<script>
  import Fivestars from './Fivestars.svelte';

  import Hero from './Hero.svelte';


  import Navbar from './Navbar.svelte';
</script>

    <div class="hero min-h-screen mt-44" style="background-image: url(./kid.jpg);">
      <div class="hero-overlay bg-opacity-90"></div>
        <div class="hero-content text-center text-neutral-content">
          <div class="max-w-md flex justify-center items-center flex-col -mt-64">
            <h1 class="text-5xl font-bold w-[700px] text-white">Check out what the people think</h1>
            <p class="text-xl w-[700px] mt-5">
                <Fivestars />
                <button class="btn btn-primary text-white mt-5 w-auto text-2xl text-center font-bold">GET YOUR FREE ESTIMATE NOW 🔧</button>

              </div>



        </div>
      </div>

