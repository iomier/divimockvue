<template>
  <div class="wrapper">
    <div class="divider-top"></div>
    <h2>Our Customers</h2>
    <div class="testimony">
      <p>“Curabitur aliquet quam id dui posuere blandit. Nulla quis lorem ut libero malesuada feugiat. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Donec velit neque, auctor sit amet aliquam vel, ullamcorper sit amet ligula. Curabitur aliquet quam id dui posuere.”</p>
      <p>“Curabitur aliquet quam id dui posuere blandit. Nulla quis lorem ut libero malesuada feugiat. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Donec velit neque, auctor sit amet aliquam vel, ullamcorper sit amet ligula. Curabitur aliquet quam id dui posuere.”</p>
      <p>“Curabitur aliquet quam id dui posuere blandit. Nulla quis lorem ut libero malesuada feugiat. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Donec velit neque, auctor sit amet aliquam vel, ullamcorper sit amet ligula. Curabitur aliquet quam id dui posuere.”</p>
    </div>
    <div class="divider-bottom"></div>
    <div class="down">
      <h1>Put You & Your Family in Good Hands</h1>
    </div>
  </div>
</template>

<script>
export default {
  name: "Testimony"
};
</script>

<style lang="sass" scoped>
h2
    text-align: center
h1
    color: #fff
    background-color: #012780
    margin:0
    padding: 1.5em
    text-align: center
.wrapper
    background-color: #eee
    .divider-top
        background-size: 125% 100%
        margin-top: 2em
        display: block
        width: 100%
        height: 249px
        text-align: center
        z-index: 1
        transform: rotateY(180deg) rotateX(180deg)
        background-image: url("data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTAwJSIgaGVpZ2h0PSI0MCUiIHZpZXdCb3g9IjAgMCAxMjgwIDE0MCIgcHJlc2VydmVBc3BlY3RSYXRpbz0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48ZyBmaWxsPSIjZmZmZmZmIj48cGF0aCBkPSJNMTA5My40OCAxMzEuODVMMTczIDk0YTc2Ljg1IDc2Ljg1IDAgMCAxLTM2Ljc5LTExLjQ2TDAgMHYxNDBoMTI4MFYwbC0xMzEuODEgMTExLjY4Yy0xNi40NyAxMy45Ni0zNS40NyAyMC45Ni01NC43MSAyMC4xN3oiLz48L2c+PC9zdmc+")
    .divider-bottom
        background-image: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTAwJSIgaGVpZ2h0PSIxODBweCIgdmlld0JveD0iMCAwIDEyODAgMTQwIiBwcmVzZXJ2ZUFzcGVjdFJhdGlvPSJub25lIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPjxnIGZpbGw9IiMwMTI3ODAiPjxwYXRoIGQ9Ik0xMDkzLjQ4IDEzMS44NUwxNzMgOTRhNzYuODUgNzYuODUgMCAwIDEtMzYuNzktMTEuNDZMMCAwdjE0MGgxMjgwVjBsLTEzMS44MSAxMTEuNjhjLTE2LjQ3IDEzLjk2LTM1LjQ3IDIwLjk2LTU0LjcxIDIwLjE3eiIvPjwvZz48L3N2Zz4=)
        background-size: 100% 180px
        height: 179px
        z-index: 1
        transform: rotateY(0) rotateX(0)
    .testimony
        display: flex
        margin: 0 auto
        width: 80%
        p
            margin: 1em
</style>

