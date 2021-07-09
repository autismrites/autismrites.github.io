<template>
  <div class="mx-auto max-w-2xl my-12">
    <div class="mb-4 border-l-4 rounded px-4 py-3 bg-gray-100">
      <div class="flex items-start">
        <div class="py-1">
          <svg
            class="fill-current h-6 w-6 mr-4 text-gray-500"
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 20 20"
          >
            <path
              d="M2.93 17.07A10 10 0 1 1 17.07 2.93 10 10 0 0 1 2.93 17.07zm12.73-1.41A8 8 0 1 0 4.34 4.34a8 8 0 0 0 11.32 11.32zM9 11V9h2v6H9v-4zm0-6h2v2H9V5z"
            />
          </svg>
        </div>

        <div>
          <h3 class="font-semibold">Info Message</h3>

          <p class="text-sm text-gray-800">This page is currently under construction</p>
        </div>
      </div>
    </div>
    <div class="mb-12 flex justify-center">
      <h1 class="text-4xl font-serif">Got queries? let me know how I can help</h1>
    </div>
    <div class="mb-8 px-2 w-full">
      <input
        id="inputName"
        class="w-full border border-gray-400 px-4 py-2 rounded-full focus:border-blue-500 focus:shadow-outline outline-none"
        type="text"
        placeholder="Enter your name..."
      />
    </div>
    <div class="mb-8 px-2 w-full">
      <input
        id="inputEmail"
        class="w-full border border-gray-400 px-4 py-2 rounded-full focus:border-blue-500 focus:shadow-outline outline-none"
        type="email"
        placeholder="enter your email"
      />
    </div>
    <div class="mb-8 px-2 w-full">
      <textarea
        id="textarea1"
        class="w-full border border-gray-400 px-4 py-2 rounded focus:border-blue-500 focus:shadow-outline outline-none"
        rows="5"
        placeholder="Your message..."
      ></textarea>
    </div>
    <div class="flex justify-center">
      <button
        class="mx-2 px-8 py-2 rounded-full text-white bg-blue-500 focus:outline-none hover:bg-blue-400"
      >
        Send
      </button>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
