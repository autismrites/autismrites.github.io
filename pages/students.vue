<template>
  <div class="mx-auto max-w-2xl my-12">
    <div class="text-left mb-8 font-serif">
      <h1 class="text-gray-800 text-4xl font-bold mb-2">Students Game Studios</h1>

      <!-- change "border-indigo-500" to change the color -->
      <div
        class="border-indigo-500 border-b-2 border-t-2 w-32 md:w-40 rounded mb-16"
      ></div>
    </div>
    <div class="flex justify-evenly mb-8">
      <div class="mx-auto max-w-xl py-8">
        <div class="rounded w-full md:w-64 overflow-hidden">
          <div>
            <a href="#">
              <img
                class="object-cover"
                src="https://raw.githubusercontent.com/vuetailwind/storage/master/cards/card-1.jpg"
                alt="Najmi's Game"
              />
            </a>
          </div>

          <div class="px-4 py-4">
            <h3 class="font-semibold text-gray-900 mb-2 truncate">Najmi</h3>

            <div class="text-sm text-gray-800">
              Lorem ipsum dolor sit amet, conse ctetur adipiscing elit. In dignissim mi
              vehicula magna vulputate, sed placerat ex. Sit amet mattis odio.
            </div>

            <div class="text-right mt-2">
              <a href="#" class="py-2 text-indigo-600 text-xs uppercase hover:underline"
                >Read More <span>&rarr;</span></a
              >
            </div>
          </div>
        </div>
      </div>
      <div class="mx-auto max-w-xl py-8">
        <div class="rounded w-full md:w-64 overflow-hidden">
          <div>
            <a href="#">
              <img
                class="object-cover"
                src="https://raw.githubusercontent.com/vuetailwind/storage/master/cards/card-1.jpg"
                alt="Abdul Rahman's Game"
              />
            </a>
          </div>

          <div class="px-4 py-4">
            <h3 class="font-semibold text-gray-900 mb-2 truncate">Abdul Rahman</h3>

            <div class="text-sm text-gray-800">
              Lorem ipsum dolor sit amet, conse ctetur adipiscing elit. In dignissim mi
              vehicula magna vulputate, sed placerat ex. Sit amet mattis odio.
            </div>

            <div class="text-right mt-2">
              <a href="#" class="py-2 text-indigo-600 text-xs uppercase hover:underline"
                >Read More <span>&rarr;</span></a
              >
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="flex justify-evenly">
      <div class="mx-auto max-w-xl py-8">
        <div class="rounded w-full md:w-64 overflow-hidden">
          <div>
            <a href="#">
              <img
                class="object-cover"
                src="https://raw.githubusercontent.com/vuetailwind/storage/master/cards/card-1.jpg"
                alt="Abdullah's Game"
              />
            </a>
          </div>

          <div class="px-4 py-4">
            <h3 class="font-semibold text-gray-900 mb-2 truncate">Abdullah</h3>

            <div class="text-sm text-gray-800">
              Lorem ipsum dolor sit amet, conse ctetur adipiscing elit. In dignissim mi
              vehicula magna vulputate, sed placerat ex. Sit amet mattis odio.
            </div>

            <div class="text-right mt-2">
              <a href="#" class="py-2 text-indigo-600 text-xs uppercase hover:underline"
                >Read More <span>&rarr;</span></a
              >
            </div>
          </div>
        </div>
      </div>
      <div class="mx-auto max-w-xl py-8 mb-16">
        <div class="rounded w-full md:w-64 overflow-hidden">
          <div>
            <a href="#">
              <img
                class="object-cover"
                src="https://raw.githubusercontent.com/vuetailwind/storage/master/cards/card-1.jpg"
                alt="Faiq's Game"
              />
            </a>
          </div>

          <div class="px-4 py-4">
            <h3 class="font-semibold text-gray-900 mb-2 truncate">Faiq</h3>

            <div class="text-sm text-gray-800">
              Lorem ipsum dolor sit amet, conse ctetur adipiscing elit. In dignissim mi
              vehicula magna vulputate, sed placerat ex. Sit amet mattis odio.
            </div>

            <div class="text-right mt-2">
              <a href="#" class="py-2 text-indigo-600 text-xs uppercase hover:underline"
                >Read More <span>&rarr;</span></a
              >
            </div>
          </div>
        </div>
      </div>
    </div>
    <assignment />
  </div>
</template>

<script>
import assignment from "~/components/assignment.vue";
export default {
  components: { assignment },
};
</script>

<style></style>
