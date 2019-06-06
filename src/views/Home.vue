<template>
  <div>
    <div class="home">
      <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
      <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    </div>
    <div>
      <Hero/>
      <Tiles/>
      <TextBox/>
      <Cards/>
      <Testimony/>
      <Contact/>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import Tiles from "@/components/Tiles";
import Hero from "@/components/Hero";
import TextBox from "@/components/TextBox";
import Cards from "@/components/Cards";
import Testimony from "@/components/Testimony";
import Contact from "@/components/Contact";
export default {
  name: "home",
  components: {
    // HelloWorld,
    Tiles,
    Hero,
    TextBox,
    Cards,
    Testimony,
    Contact
  }
};
</script>
