<template>
  <div>
    <AppHeader />
    <AppNavbar />
    <HolidayHomes />
  </div>
</template>

<script>
import AppHeader from "./components/AppHeader.vue";
import AppNavbar from "./components/AppNavbar.vue";
import HolidayHomes from "./components/HolidayHomes.vue";
export default {
  components: {
    AppHeader,
    AppNavbar,
    HolidayHomes,
  },
};
</script>

<style></style>
