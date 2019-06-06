<template>
  <div class="text-box">
    <Box>
      <div class="image-wrapper">
        <img
          src="https://www.elegantthemes.com/layouts/wp-content/uploads/2018/07/insurance-31.png"
          alt
        >
      </div>
    </Box>
    <Box>
      <h1>Bundle & Save</h1>
      <p>
        Proin eget tortor risus. Praesent sapien massa, convallis a
        pellentesque nec, egestas non nisi. Donec rutrum congue leo eget
        malesuada. Nulla porttitor accumsan tincidunt. Donec rutrum congue leo
        eget malesuada.
      </p>
    </Box>
  </div>
</template>

<script>
import Box from "../components/Utils/Box";
export default {
  name: "TextBox",
  components: {
    Box
  }
};
</script>

<style lang="sass" scoped>
.text-box 
    width: 80%
    margin: 0.5em auto
    display: flex
    align-content: flex-start
    flex-wrap: 1
    .image-wrapper 
        width: 100%
        
    img 
        width: inherit

</style>
