<script>
  import { fly } from 'svelte/transition'
  let hover = false
</script>

<button on:mouseover={() => (hover = true)}> asdf</button>
{#if hover}
  <a
    transition:fly={{ y: 100, duration: 1000 }}
    on:mouseover={() => (hover = true)}
    on:mouseleave={() => (hover = false)}
    href="#"
    class="rounded-md bg-[#638ef4] p-4 font-medium text-white"
  >
    <div class="absolute h-full w-full bg-orange-500">a</div>
    <u class="decoration-wavy underline-offset-8">Lorem</u>
    <p class="mt-8">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores ea assumenda maxime, aut
    </p>
  </a>
{/if}
