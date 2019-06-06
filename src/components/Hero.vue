<template>
  <div id="hero-template">
    <div class="heros">
      <div class="column">
        <h2>Are You Covered? Home, Life, & Auto Insurance.</h2>
        <p>
          Proin eget tortor risus. Praesent sapien massa, convallis a
          pellentesque nec, egestas non nisi. Donec rutrum congue leo eget
          malesuada.
        </p>
        <button>TALK WITH AN AGENT</button>
      </div>
      <div class="column column-right">
        <img src="../assets/hero.png" alt>
      </div>
    </div>
    <div class="divider"/>
  </div>
</template>

<script>
export default {
  name: "Hero"
};
</script>

<style lang="sass" scoped>
#hero-template
  background: #50c1fa
  background: linear-gradient(0deg, rgba(80, 193, 250, 1) 0%, rgba(18, 88, 224, 1) 100%)
  .heros
    display: flex
    flex-wrap: 1
    justify-content: center
  .column
    padding: 2em 0
    width: 35%
    max-width: 100%
    img
      width: 100%
    h2
      color: #fff
      font-weight: 600
      line-height: 1em
      font-size: 3.5em
    p
      color: #fff
      font-size: 1.5em
    button
      color: #fff !important
      border-width: 0px !important
      border-radius: 4px
      letter-spacing: 1px
      font-size: 14px
      font-family: 'Montserrat', Helvetica, Arial, Lucida, sans-serif !important
      text-transform: uppercase !important
      background-color: #003bde
      padding-top: 16px !important
      padding-right: 40px !important
      padding-bottom: 16px !important
      padding-left: 40px !important
      cursor: pointer
  .divider
    background-image: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTAwJSIgaGVpZ2h0PSIxMDBweCIgdmlld0JveD0iMCAwIDEyODAgMTQwIiBwcmVzZXJ2ZUFzcGVjdFJhdGlvPSJub25lIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPjxnIGZpbGw9IiNmZmZmZmYiPjxwYXRoIGQ9Ik0xMDkzLjQ4IDEzMS44NUwxNzMgOTRhNzYuODUgNzYuODUgMCAwIDEtMzYuNzktMTEuNDZMMCAwdjE0MGgxMjgwVjBsLTEzMS44MSAxMTEuNjhjLTE2LjQ3IDEzLjk2LTM1LjQ3IDIwLjk2LTU0LjcxIDIwLjE3eiIvPjwvZz48L3N2Zz4=)
    display: block
    background-size: 100% 100px
    bottom: 0
    height: 100px
    z-index: 1
</style>
