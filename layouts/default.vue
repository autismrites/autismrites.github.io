<template>
  <div class="px-4">
    <div class="bg-purple-700 -mx-4 text-white px-12 py-4 align-middle">
      <div class="text-center">
        <div class="text-3xl my-12">
          <nuxt-link to="/">
            <h1>Creative<span class="font-bold">Khayr</span>Studio</h1>
          </nuxt-link>
        </div>

        <div class="grid justify-center grid-cols-2 sm:grid-cols-4 gap-4 mb-4">
          <nuxt-link to="/students"
            ><p class="py-2 px-3 hover:bg-indigo-500 rounded">students</p></nuxt-link
          >
          <nuxt-link to="/challenge"
            ><p class="py-2 px-3 hover:bg-indigo-500 rounded">challenge</p></nuxt-link
          >
          <nuxt-link to="/gallery"
            ><p class="py-2 px-3 hover:bg-indigo-500 rounded">gallery</p></nuxt-link
          >

          <nuxt-link to="/reportCard"
            ><p
              class="py-2 px-3 hover:bg-indigo-400 bg-indigo-500 rounded shadow-lg text-white"
            >
              Report Card
            </p></nuxt-link
          >
        </div>
        <!-- <p class="text-center text-gray-300 mb-2">
          please rotate your mobile device to landscape for better view
        </p> -->
      </div>
    </div>

    <Nuxt />
    <div class="bg-gray-800 -mx-4 py-20 px-8 text-gray-100 text-center">
      <h1 class="text-2xl md:text-4xl mb-2">
        Creative<span class="font-bold">Khayr</span>Studios
      </h1>
      <h3 class="text-lg">Empowering & Guiding Young Minds</h3>
      <p class="text-sm">EST 2021</p>
    </div>
  </div>
</template>
