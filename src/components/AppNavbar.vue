<template>
  <div>
    <section>
      <nav class="nav-content">
        <div class="nav-icon">
          <div><img v-bind:src="navLogoOne"  /></div>
          <div class="text">OMG!</div>
        </div>
        <div class="nav-icon">
          <div><img v-bind:src="navLogoTwo" /></div>
          <div class="text">Beaches</div>
        </div>
        <div class="nav-icon">
          <div><img v-bind:src="navLogoThree" /></div>
          <div class="text">Amazing pools</div>
        </div>
        <div class="nav-icon">
          <div><img v-bind:src="navLogoFour" /></div>
          <div class="text">Islands</div>
        </div>
        <div class="nav-icon">
          <div><img v-bind:src="navLogoFive" /></div>
          <div class="text">National parks</div>
        </div>
        <div class="nav-icon">
          <div><img v-bind:src="navLogoSix" /></div>
          <div class="text">Tiny homes</div>
        </div>
        <div class="nav-icon">
          <div><img v-bind:src="navLogoSeven" /></div>
          <div class="text">Design</div>
        </div>
        <div class="nav-icon">
          <div><img v-bind:src="navLogoEight" /></div>
          <div class="text">Camping</div>
        </div>
        <div class="nav-icon">
          <div><img v-bind:src="navLogoNine" /></div>
          <div class="text">Cabins</div>
        </div>
        <div class="nav-icon">
          <div><img v-bind:src="navLogoTen" /></div>
          <div class="text">Lake view</div>
        </div>
      </nav>
    </section>
  </div>
</template>

<script>
export default {
  name: "AppNavbar",
  data() {
    return {
      navLogoOne: require("../assets/nav_logo_1.jpg"),
      navLogoTwo: require("../assets/nav_logo_2.jpg"),
      navLogoThree: require("../assets/nav_logo_3.jpg"),
      navLogoFour: require("../assets/nav_logo_4.jpg"),
      navLogoFive: require("../assets/nav_logo_5.jpg"),
      navLogoSix: require("../assets/nav_logo_6.jpg"),
      navLogoSeven: require("../assets/nav_logo_7.jpg"),
      navLogoEight: require("../assets/nav_logo_8.jpg"),
      navLogoNine: require("../assets/nav_logo_9.jpg"),
      navLogoTen: require("../assets/nav_logo_10.jpg"),
    };
  },
};
</script>

<style scoped>
section {
  width: 100%;
}
.nav-content {
  width: 88%;
  margin: 1.5em auto;
  display: flex;
  justify-content: space-between;
  position: relative;
  z-index: 1;
}
img {
  width: 24px;
  height: 24x;
  
}

.nav-icon {
  padding: 5px;
  text-align: center;
}
.text {
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  font-size: 12px;
  color: lightslategrey;
  margin-top: 5px;
}
</style>
