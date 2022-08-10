<template>
  <div class="about">
    <h1>This is an about page</h1>
    <TestCom />
    <DashBoard />
    <ChartManth />
  </div>
</template>
<script>
// @ is an alias to /src
import TestCom from "@/components/TestCom.vue";
import DashBoard from "@/components/DashBoard.vue";
import ChartManth from "@/components/ChartManth.vue";

export default {
  name: "HomeView",
  components: {
    TestCom,
    DashBoard,
    ChartManth
},
};
</script>
