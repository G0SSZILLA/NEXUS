<template>
  <div class="Home container-fluid">
    <div class="row">
        <div class="col-3">
      <Post />

        </div>
    </div>
    
  </div>
</template>

<script>
import Post from "../components/Post.vue";
export default {
  name: 'Home',

  data() {
    return {};
  },

  computed: {},

  methods: {},

  components: { Post }
};
</script>


<style scoped>
.row {
    height: 300px;
}
</style>
