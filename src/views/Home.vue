<template>
  <div>
    <div class="main-container">
      <Hero />
      <Contact />
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Hero from "@/components/Hero.vue";
import Contact from "@/components/Contact.vue";

export default {
  name: "home",
  components: {
    Hero,
    Contact
  }
};
</script>
