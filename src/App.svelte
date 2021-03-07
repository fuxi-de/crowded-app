<script lang="ts">
  export let name: string;
</script>

<main>
  <section class="text-gray-400 bg-gray-900 body-font h-screen flex items-center">
    <div class="container px-5 py-24 mx-auto">
      <div class="flex flex-col text-center w-full mb-12">
        <h1 class="sm:text-3xl text-2xl font-medium title-font mb-4 text-white">
          Master Cleanse Reliac Heirloom
        </h1>
        <p class="lg:w-2/3 mx-auto leading-relaxed text-base">
          Whatever cardigan tote bag tumblr hexagon brooklyn asymmetrical
          gentrify, subway tile poke farm-to-table. Franzen you probably haven't
          heard of them man bun deep.
        </p>
      </div>
      <div
        class="flex lg:w-2/3 w-full sm:flex-row flex-col mx-auto px-8 sm:px-0 items-end sm:space-x-4 sm:space-y-0 space-y-4"
      >
        <div class="relative sm:mb-0 flex-grow w-full">
          <label for="place" class="leading-7 text-sm text-gray-400"
            >Place</label
          >
          <input
            type="text"
            id="place"
            name="place"
            class="h-12 w-full bg-gray-800 bg-opacity-40 rounded border border-gray-700 focus:border-purple-500 focus:ring-2 focus:ring-purple-900 focus:bg-transparent text-base outline-none text-gray-100 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out"
          />
        </div>
        <div class="relative sm:mb-0 flex-grow w-full">
          <label for="placeType" class="leading-7 text-sm text-gray-400"
            >Place Type</label
          >
          <select
            id="placeType"
            name="placeType"
            class="h-12 w-full bg-gray-800 bg-opacity-40 rounded border border-gray-700 focus:border-purple-500 focus:ring-2 focus:ring-purple-900 focus:bg-transparent text-base outline-none text-gray-100 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out"
          >
            <option value="supermarkt">Supermarkt</option>
            <option value="baumarkt">Baumarkt</option>
            <option value="bäckerei">Bäckerei</option>
            <option value="post">Post</option>
          </select>
        </div>
        <button
          class="h-12 text-white bg-purple-500 border-0 py-2 px-8 focus:outline-none hover:bg-purple-600 rounded text-lg"
          >Results!</button
        >
      </div>
    </div>
  </section>
  <!-- <h1>Hello {name}!</h1>
  <p>
    Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn
    how to build Svelte apps.
  </p> -->
</main>

<style global>
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
</style>
