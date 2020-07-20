
<template>
  <div class="app">
    <navbar />
    <UserNavbar />
     <router-view />
  </div>
</template>

<script>
import navbar from "./components/navbar";
import UserNavbar from "./components/UserNavbar";


export default {
  name: "app",

  data() {
    return {};
  },

  computed: {},

  methods: {},

  components: { navbar, UserNavbar }
};
</script>


<style scoped>
</style>







