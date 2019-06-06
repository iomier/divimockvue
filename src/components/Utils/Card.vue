<template>
  <div class="card">
    <div class="thumb">
      <img class="image" :src="image" alt>
    </div>
    <div class="title">
      <h4>{{title}}</h4>
    </div>
    <p class="text">{{text}}</p>
  </div>
</template>

<script>
export default {
  name: "Card",
  props: ["image", "title", "text"]
};
</script>

<style lang="sass" scoped>
.card
    margin:2em
    background-color: #ffffff
    border-radius: 10px
    overflow: hidden
    padding: 30px
    box-shadow: 0px 10px 80px -10px rgba(44,54,92,0.2)
    .thumb
        width:100%
        .image
            width: inherit
</style>
