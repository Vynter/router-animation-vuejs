<template>
  <div class="home page">
    <transition name="anim" appear>
      <div class="h">
        <h1>Home page</h1>
        <img alt="Vue logo" src="../assets/logo.png" />
      </div>
    </transition>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {},
};
</script>

<style scoped>
.home {
  text-align: center;
}

.anim-enter-active,
.anim-leave-active {
  transition: 2s;
}
.anim-enter {
  filter: blur(1.5rem);
}
.anom-enter-to {
  filter: blur(0);
}
</style>
