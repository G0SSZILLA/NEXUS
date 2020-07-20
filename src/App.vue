
<template>
  <div class="app">
    <navbar />
    <UserNavbar />
    
  </div>
</template>

<script>
import navbar from "./components/navbar";
import UserNavbar from "./components/UserNavbar";
// import Home from "./views/Home";

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







