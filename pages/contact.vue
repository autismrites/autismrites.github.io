<template>
  <div class="mx-auto max-w-2xl my-12">
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
