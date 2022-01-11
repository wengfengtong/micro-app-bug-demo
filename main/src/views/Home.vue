<template>
  <div class="home">
    <div class="dialog">
      <micro-app
        name="app1"
        url="http://192.168.108.4:9528/#/dashboard"
      ></micro-app>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
  },
};
</script>

<style  scoped>
.home {
  width: 100vw;
  height: 100vh;
  position: relative;
  background: black;
}
.dialog {
  overflow: hidden;
  width: 1200px;
  height: 820px;
  position: absolute;
  top: 50px;
  left: 200px;
  background: white;
  border-radius: 20px;
  transform: translate(0, 0);
}
</style>