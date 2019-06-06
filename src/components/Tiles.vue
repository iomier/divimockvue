<template>
  <div id="tiles">
    <Tile
      v-for="post in posts"
      :key="post.id"
      :icon="post.icon"
      :title="post.title"
      :text="post.text"
    ></Tile>
  </div>
</template>


<script>
import Tile from "@/components/Utils/Tile";
import { posts } from "@/data/post";
console.log(posts);
export default {
  name: "Tiles",
  components: {
    Tile
  },
  data() {
    return {
      posts
    };
  }
};
</script>


<style lang="sass" scoped>
#tiles 
    margin: -5em auto 0 auto
    top: -100px
    width: 80%
    display: grid
    grid-gap: 1rem
    grid-template-columns: 1fr 1fr 1fr
    
</style>
