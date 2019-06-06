<template>
 <form>
        <input type="text" name="name" placeholder="Name">
        <input type="email" name="email" placeholder="Email">
        <textarea name="message" id cols="30" rows="10" placeholder="Type your Message"></textarea>
        <button>Send</button>
      </form>   
</template>
<script>
export default {
    name: "ContactForm"
}
</script>
<style lang="sass" scoped>
input,textarea
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


