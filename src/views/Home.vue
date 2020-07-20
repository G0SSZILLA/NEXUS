<template>
  <div class="Home Masonry  fluid columnWidth">
    <div class="row container-fluid mt-4 mr-0 pr-0">
        <div class="col-12 pr-0">

      <div class="grid ">
  <div class="grid-sizer"></div>
  <div class="grid-item"></div>
  <div class="grid-item grid-item--width2 grid-item--height2"></div>
  <div class="grid-item grid-item--height3"></div>
  <div class="grid-item grid-item--height2"></div>
  <div class="grid-item grid-item--width3"></div>
  <div class="grid-item"></div>
  <div class="grid-item"></div>
  <div class="grid-item grid-item--height2"></div>
  <div class="grid-item grid-item--width2 grid-item--height3"></div>
  <div class="grid-item"></div>
  <div class="grid-item grid-item--height2"></div>
  <div class="grid-item"></div>
  <div class="grid-item grid-item--width2 grid-item--height2"></div>
  <div class="grid-item grid-item--width2"></div>
  <div class="grid-item"></div>
  <div class="grid-item grid-item--height2"></div>
  <div class="grid-item"></div>
  <div class="grid-item"></div>
  <div class="grid-item grid-item--height3"></div>
  <div class="grid-item grid-item--height2"></div>
  <div class="grid-item"></div>
  <div class="grid-item"></div>
  <div class="grid-item grid-item--height2"></div>
</div>
        
        </div>
    </div>
  
  </div>
</template>

<script>
// import Post from "../components/Post.vue";
export default {
  name: 'Home',

  data() {
    return {};
  },

  computed: {
    
  },

  methods: {
    
  },

  components: {  }
};
</script>


<style scoped>
.row {
    height: 300px;
}
* { box-sizing: border-box; }

body { font-family: sans-serif; }

/* ---- grid ---- */

.grid {
  background: #EEE;
  max-width: 1903px;
}

/* clearfix */
.grid:after {
  content: '';
  display: block;
  clear: both;
}

/* ---- grid-item ---- */

.grid-sizer,
.grid-item {
  width: 15%;
}

.grid-item {
  height: 500px;
  float: left;
  background: #D26;
  border: 2px solid #333;
  border-color: hsla(0, 0%, 0%, 0.5);
  border-radius: 5px;
  margin: 10px;
}

.grid-item--width2 { width:  50%; }
.grid-item--width3 { width:  60%; }

.grid-item--height2 { height: 400px; }
.grid-item--height3 { height: 260px; }
.grid-item--height4 { height: 360px; }
</style>
