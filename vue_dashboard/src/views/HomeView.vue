<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <DashBoard />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import DashBoard from "@/components/DashBoard.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
    DashBoard
},
};
</script>
