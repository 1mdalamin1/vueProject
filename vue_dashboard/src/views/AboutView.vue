<template>
  <div class="about">
    <HelloWorld msg="This is an about page" />
    <ChartDay />
    
    <!-- last section start now -->
    <div class="row con">
      <div class="col-md-3">
        <ActiveUser msg="Most Active" />
      </div>
      <div class="col-md-3">
        <div class="man_box">
          <ActiveUser msg="Top Diamond" />
        </div>
      </div>
      <div class="col-md-3">
        <div class="man_box">
          <ActiveUser msg="Top Level" />
        </div>
      </div>
      <div class="col-md-3">
        <div class="man_box">
          <ActiveUser msg="Top Bean" />
        </div>
      </div>
    </div>
    <!-- last section The end -->

  </div>
</template>
<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import ChartDay from "@/components/ChartDay.vue";
import ActiveUser from "@/components/ActiveUser.vue";

export default {
  name: "AboutView",
  components: {
    HelloWorld,
    ChartDay,
    ActiveUser
},
};
</script>
