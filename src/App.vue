<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <transition
      name="router-anim"
      enter-active-class="animated fadeInDown"
      leave-active-class="animated fadeOutDown"
    >
      <router-view />
    </transition>
  </div>
</template>

<style>
/* @import "https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"; */
@import "https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.0.0/animate.compat.css";

body {
  background: rgb(233, 233, 233);
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
html,
body {
  height: 100%;
}
#app {
  background: #fff;
  width: 50%;
  padding: 30px;
  border-radius: 10px;
  margin: 50px auto 0 auto;
  height: calc(60% - 50px);
  /* box-shadow: 0 15px 50px rgba(0, 0, 0, 0.2); */
}

.page {
  position: absolute;
  width: inherit;
}
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
} */
</style>
