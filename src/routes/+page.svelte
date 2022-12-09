<main>
  <h1 class="mb-8 text-center text-4xl font-bold">Hotel Booking</h1>
  <section class="[ card-container ] flex grid-cols-2 flex-col gap-4 px-4 lg:grid 2xl:grid-cols-3">
    {#each [0, 1, 2, 3, 4, 5] as i}
      <a
        href="#"
        class="group relative overflow-hidden rounded-md bg-[#638ef4] p-4 font-medium text-white"
      >
        <div
          class="absolute -top-36 left-0 h-full w-full rounded-md bg-[#f18776] opacity-0 transition-all duration-500 group-hover:top-0 group-hover:opacity-100"
        />
        <u class="relative decoration-wavy underline-offset-8">Lorem</u>
        <p class="relative mt-8">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores ea assumenda maxime, aut
        </p>
      </a>
    {/each}
  </section>
</main>
