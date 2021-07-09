<template>
  <div class="mx-12 my-6">
    <my-hero />
    <about />
  </div>
</template>

<script>
import About from "~/components/about.vue";
import myHero from "~/components/myHero.vue";

export default {
  components: { myHero, About },
};
</script>

Hero
