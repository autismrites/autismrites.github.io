<template>
  <div>
    <div class="bg-purple-700 text-white px-12 py-4 align-middle">
      <div class="flex justify-between">
        <div class="text-3xl">
          <nuxt-link to="/">
            <div>
              <h1>Creative<span class="font-bold">Khayr</span>Studio</h1>
            </div>
          </nuxt-link>
        </div>

        <div class="my-auto">
          <nuxt-link to="/students"
            ><a class="py-2 px-3 ml-2 hover:bg-indigo-500 rounded">
              students
            </a></nuxt-link
          >
          <nuxt-link to="/challenge"
            ><a class="py-2 px-3 ml-2 hover:bg-indigo-500 rounded">
              challenge
            </a></nuxt-link
          >
          <!-- <nuxt-link to="/gallery"><a class="py-2 px-3 ml-2 hover:bg-indigo-500 rounded">
             gallery 
          </a></nuxt-link> -->

          <nuxt-link to="/reportCard"
            ><a
              class="py-2 px-3 ml-2 hover:bg-indigo-400 bg-indigo-500 rounded shadow-lg text-white"
            >
              Report Card
            </a></nuxt-link
          >
        </div>
      </div>
    </div>

    <Nuxt />
  </div>
</template>
