<template>
  <div id="app">
    <header id="nav">
      <nav>
        <ul>
          <router-link to="/">Home</router-link>|
          <router-link to="/about">About</router-link>
        </ul>
      </nav>
    </header>
    <router-view/>
  </div>
</template>

<style>
@import url("https://fonts.googleapis.com/css?family=Montserrat&display=swap");
h1,
h2,
h3,
h4,
h5,
p,
li {
  font-family: "Montserrat", Helvetica, Arial, Lucida, sans-serif;
}
p {
  font-family: "Montserrat", Helvetica, Arial, Lucida, sans-serif;
  font-weight: 300;
  font-size: 16px;
  line-height: 2em;
}
h4 {
  font-size: 18px;
  font-family: "Montserrat", Helvetica, Arial, Lucida, sans-serif;
}
body {
  margin: 0 !important;
  font-family: "Montserrat", Helvetica, Arial, Lucida, sans-serif;
}
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
#nav {
  display: flex;
  padding: 20px;
  background-color: #1258e0;
}

#nav a {
  font-weight: bold;
  color: #fff;
}

#nav a.router-link-exact-active {
  color: #1a1a1a;
}
</style>