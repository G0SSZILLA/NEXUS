<template>
  <div class="UserNavbar">

<!-- NOTE AVATAR -->
    <div class="row row-1 container-fluid p-0 m-0">
        <div class="col-12">
             <div class="row row-2"><div class="col-1">
        <img
          src="https://mdbootstrap.com/img/Photos/Avatars/avatar-2.jpg"
          class="rounded-circle ml-5 mt-2 avatar z-depth-0 shadow"
          alt="avatar image"/>
      </div>
      <div class="col-10 p-0 "></div></div>
        </div>
       
      
    </div>
   
<!--NOTE Navbar -->
        <nav class="mb-1 navbar navbar-expand-lg p-0 shadow ">
      
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarSupportedContent-555"
        aria-controls="navbarSupportedContent-555"
        aria-expanded="false"
        aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent-555">
        <ul class="navbar-nav mr-auto ml-2">
          <li class="nav-item active">
            <a class="nav-link text-white" href="#">
              Home
              <span class="sr-only">(current)</span>
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-white" href="#">Features</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-white" href="#">Photos</a>
          </li>
          <li class="nav-item dropdown">
            <a
              class="nav-link dropdown-toggle text-white "
              id="navbarDropdownMenuLink-555"
              data-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false">More</a>
            <div
              class="dropdown-menu dropdown-secondary"
              aria-labelledby="navbarDropdownMenuLink-555">
              <a class="dropdown-item" href="#">Action</a>
              <a class="dropdown-item" href="#">Another action</a>
              <a class="dropdown-item" href="#">Something else here</a>
            </div>
          </li>
        </ul>
        
        <!-- <ul>
          <li class="nav-item avatar dropdown mt-1">
            <a
              class="nav-link dropdown-toggle"
              id="navbarDropdownMenuLink-55"
              data-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false">
              <img
                src="https://mdbootstrap.com/img/Photos/Avatars/avatar-2.jpg"
                class="rounded-circle avatar mb-2 z-depth-0"
                alt="avatar image"/>
            </a>
            <div
              class="dropdown-menu dropdown-menu-lg-right dropdown-secondary"
              aria-labelledby="navbarDropdownMenuLink-55">
              <a class="dropdown-item" href="#">Action</a>
              <a class="dropdown-item" href="#">Another action</a>
              <a class="dropdown-item" href="#">Something else here</a>
            </div>
          </li>
        </ul> -->
      </div>
    </nav>
   
  </div>
</template>

<script>
export default {
  name: "UserNavbar",

  data() {
    return {};
  },

  computed: {},

  methods: {},

  components: {}
};
</script>


<style scoped>
.row-1 {
  margin-top: 1rem;
  height: 200px;
  background-color: #182338;
}

.navbar{
    background-color: #273552;
    font-family: 'Syncopate', sans-serif;
    width: 1903px;
    
}

/* .imgbar{
width: 80%;
} */

.row-2{
    height: 168px;
    /* background-color: #fff; */
    background-image: url(https://api.time.com/wp-content/uploads/2014/05/wallpaperfx.jpg);
    background-size: cover;
    /* background-position-x: 90%; */
    background-position-y: 28%;
    
}


.avatar{
    height: 11.5rem;
}

</style>