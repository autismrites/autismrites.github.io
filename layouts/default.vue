<template>
  <div class="px-4">
    <div class="bg-purple-700 -m-4 text-white px-12 py-4 align-middle">
      <div class="text-center">
        <div class="text-3xl my-4">
          <nuxt-link to="/">
            <h1>Creative<span class="font-bold">Khayr</span>Studio</h1>
          </nuxt-link>
        </div>

        <div class="grid grid-flow-col gap-8 mb-4">
          <nuxt-link to="/students"
            ><p class="py-2 px-3 ml-2 hover:bg-indigo-500 rounded">students</p></nuxt-link
          >
          <nuxt-link to="/challenge"
            ><p class="py-2 px-3 ml-2 hover:bg-indigo-500 rounded">
              challenge
            </p></nuxt-link
          >
          <nuxt-link to="/gallery"
            ><p class="py-2 px-3 ml-2 hover:bg-indigo-500 rounded">gallery</p></nuxt-link
          >

          <nuxt-link to="/reportCard"
            ><p
              class="py-2 px-3 ml-2 hover:bg-indigo-400 bg-indigo-500 rounded shadow-lg text-white"
            >
              Report Card
            </p></nuxt-link
          >
        </div>
        <p class="text-center text-gray-300 mb-2">
          please rotate your mobile device to landscape for better view
        </p>
      </div>
    </div>

    <Nuxt />
    <div class="py-32 bg-gray-800 -m-4">
      <h1 class="text-4xl text-gray-100 mx-auto text-center">
        Creative<span class="font-bold">Khayr</span>Studios -
        <span class="font-light">Empowering & Guiding Young Minds</span>
      </h1>
    </div>
  </div>
</template>
