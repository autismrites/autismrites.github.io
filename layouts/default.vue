<template>
  <div>
    <div class="bg-purple-700 text-white px-12 py-4 align-middle">
      <div class="flex justify-between">
        <div class="text-3xl">
          <nuxt-link to="/">
            <h1>Creative<span class="font-bold">Khayr</span>Studio</h1>
          </nuxt-link>
        </div>

        <div class="my-auto">
          <a class="py-2 px-3 ml-2 hover:bg-indigo-500 rounded">
            <nuxt-link to="/students"> students </nuxt-link>
          </a>
          <a class="py-2 px-3 ml-2 hover:bg-indigo-500 rounded">
            <nuxt-link to="/challenge"> challenge </nuxt-link>
          </a>
          <!-- <a class="py-2 px-3 ml-2 hover:bg-indigo-500 rounded">
            <nuxt-link to="/gallery"> gallery </nuxt-link>
          </a> -->

          <a
            class="py-2 px-3 ml-2 hover:bg-indigo-400 bg-indigo-500 rounded shadow-lg text-white"
          >
            <nuxt-link to="/reportCard"> Report Card </nuxt-link>
          </a>
        </div>
      </div>
    </div>

    <Nuxt />
  </div>
</template>
