<template>
  <div class="home">
    <HelloWorld msg="Good Morning, John Doe" />
    <ChartManth />

    <!-- last section start now -->
    <div class="row con">
      <div class="col-md-3">
        <div class="man_box">
          <h4>Most Active</h4>
          <div class="single_man">
            <img src="img/m1.jpg" alt="p.pick">
            <div>
              <b>Benny Chagur</b>
              <p>16 hrs</p>
            </div>
          </div>
          <div class="single_man">
            <img src="img/m2.jpg" alt="p.pick">
            <div>
              <b>Benny Chagur</b>
              <p>16 hrs</p>
            </div>
          </div>
          <div class="single_man">
            <img src="img/m3.jpg" alt="p.pick">
            <div>
              <b>Benny Chagur</b>
              <p>16 hrs</p>
            </div>
          </div>
          <div class="single_man">
            <img src="img/m4.jpg" alt="p.pick">
            <div>
              <b>Benny Chagur</b>
              <p>16 hrs</p>
            </div>
          </div>
          <div class="single_man">
            <img src="img/m5.jpg" alt="p.pick">
            <div>
              <b>Benny Chagur</b>
              <p>16 hrs</p>
            </div>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="man_box"></div>
      </div>
      <div class="col-md-3">
        <div class="man_box"></div>
      </div>
      <div class="col-md-3">
        <div class="man_box"></div>
      </div>
    </div>
    <!-- last section The end -->

  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import ChartManth from "@/components/ChartManth.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
    ChartManth
},
};
</script>

<style>
.row.con {
    margin: 20px 10px;
}

.man_box {
    border: 1px solid #f9f9f9;
    border-radius: 4px;
    padding: 15px 10px;
}

.single_man img {
    width: 35px;
    border: 1px solid f9f9f9;
    border-radius: 30px;
}

.single_man {
    display: flex;
}
.single_man p {
    margin: 0;
    font-size: 12px;
}

.single_man b {
    font-size: 14px;
}
</style>
