<template>
  <div>
    <AppHeader />
    <AppNavbar />
    <HolidayHomes />
    <AppFooter />
  </div>
</template>

<script>
import AppHeader from "./components/AppHeader.vue";
import AppNavbar from "./components/AppNavbar.vue";
import HolidayHomes from "./components/HolidayHomes.vue";
import AppFooter from "./components/AppFooter.vue"
export default {
  components: {
    AppHeader,
    AppNavbar,
    HolidayHomes,
    AppFooter
  },
};
</script>

<style></style>
