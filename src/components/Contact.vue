<template>
  <div class="wrapper">
    <div class="box">
      <h2>Get In Touch</h2>
      <p>Cras ultricies ligula sed magna dictum porta. Praesent sapien massa, convallis a pellentesque nec, egestas non nisi. Praesent sapien massa, convallis a</p>
      <ContactForm/>
    </div>
  </div>
</template>
<script>
import ContactForm from "@/components/Utils/ContactForm";
export default {
  name: "Contact",
  components: {
    ContactForm
  }
};
</script>
<style lang="sass" scoped>
.wrapper
    background-color: #012780
    padding-bottom: 120px
    .box
        margin: 0 auto
        width: 60%
        background-color: #ffffff
        border-radius: 10px
        overflow: hidden
        padding: 30px
        box-shadow: 0px 10px 80px -10px rgba(44,54,92,0.2)
</style>
