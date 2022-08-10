<template>
  <div class="about">
    <HelloWorld msg="This is an about page" />
    <TestCom />
    <DashBoard />
  </div>
</template>
<script>
// @ is an alias to /src
import TestCom from "@/components/TestCom.vue";
import DashBoard from "@/components/DashBoard.vue";
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "HomeView",
  components: {
    TestCom,
    DashBoard,
    HelloWorld
},
};
</script>
