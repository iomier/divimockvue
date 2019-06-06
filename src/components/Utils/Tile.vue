<template>
  <div class="tile">
    <div class="icon">
      <img class="image" :src="icon">
    </div>
    <div class="text-box">
      <h4 class="title">{{title}}</h4>
      <div class="text">{{text}}</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Tile",
  props: ["title", "text", "icon"]
};
</script>

<style lang="sass" scoped>
.tile
  box-shadow: 0px 10px 80px -10px rgba(44, 54, 92, 0.2)
  padding: 15px
  height: 180px
  border-radius: 15px
  background-color: #fff
  display: flex
  .text-box
    padding: 0 0.5em
    .title
      line-height: 1.6em
      font-size: 18px
      padding-bottom: 10px
      color: #333
      font-weight: 500
      margin:0
    .text
      line-height: 2em
      font-family: 'Montserrat',Helvetica,Arial,Lucida,sans-serif
      font-weight: 300
      color: #666
  .icon
    width:32px
    height:auto
    .image
      width:32px
</style>
