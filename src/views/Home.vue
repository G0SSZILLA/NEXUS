<template>
 <!-- `eslint-disable-next-line -->
  <div class="Home">
    <div class="row container-fluid mt-4 mr-0 pr-0">
        <div class="col-12 pr-0">

 <div class="grid">
  <div class="grid-sizer"></div>
  <div class="grid-item grid-item--width2"></div>
  <div class="grid-item grid-item--height2"></div>
  <Post class="grid-item"/>
  <div class="grid-item"></div>
  <div class="grid-item grid-item--width2 grid-item--height2"></div>
  <div class="grid-item grid-item--width2"></div>
  <div class="grid-item grid-item--width2"></div>
  <div class="grid-item grid-item--height2"></div>
  <div class="grid-item"></div>
  <div class="grid-item grid-item--width2"></div>
  <div class="grid-item grid-item--height2"></div>
  <div class="grid-item"></div>
  <div class="grid-item"></div>
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

  mounted() {
       this.grid.isotope({
  itemSelector: '.grid-item',
  percentPosition: true,
  masonry: {
    columnWidth: '.grid-sizer'
  }
});
  },

  computed: {


  },

  methods: {
    
  },

  components: {}
};
</script>


<style scoped>
* { box-sizing: border-box; }

/* force scrollbar, prevents initial gap */
html {
  overflow-y: scroll; 
}

body {
  font-family: sans-serif;
}

/* ---- grid ---- */

.grid {
  background: #DDD;
}

/* clear fix */
.grid:after {
  content: '';
  display: block;
  clear: both;
}

/* ---- .element-item ---- */

/* 5 columns, percentage width */
.grid-item,
.grid-sizer {
  width: 20%;
  border-radius: 5px;
}

.grid-item {
  float: left;
  height: 425px;
  background: #0D8;
  border: 2px solid #333;
  border-color: hsla(0, 0%, 0%, 0.7);
  margin: 12px;
  width: 385px;
}

.grid-item--width2 { width: 55%; }
.grid-item--height2 { height: 300px; }

</style>
