<template>
  <div class="card">
    <div class="title">
      <h4>{{title}}</h4>
    </div>
    <p class="text">{{text}}</p>
    <form class="login">
      <input type="text" name="username" id="username" placeholder="Username">
      <input type="text" name="password" id="password" placeholder="Password">
      <button>Login</button>
    </form>
  </div>
</template>

<script>
export default {
  name: "CardLogin",
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
    flex-grow: 1
    .thumb
        width:100%
        .image
            width: inherit
    .login
      input
        font-family: 'Montserrat',Helvetica,Arial,Lucida,sans-serif
        font-size: 16px
        font-weight: 400
        padding: 14px 4%
        margin: 0.5em auto
        display: block
        width: 100%
        box-sizing: border-box
        border-radius: 5px
        border-width: 2px
        border-color: rgba(51,51,51,0.06)
      button
          color: #ffffff
          border-width: 10px
          border-color: rgba(0,0,0,0)
          border-radius: 4px
          letter-spacing: 1px
          font-size: 14px
          font-family: 'Montserrat',Helvetica,Arial,Lucida,sans-serif
          text-transform: uppercase
          background-color: #003bde
          width: 100%
          margin-top: 1em
          cursor: pointer
          padding: .3em 1em
</style>
