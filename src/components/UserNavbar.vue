<template>
  <div class="UserNavbar">

<!-- NOTE AVATAR -->
    <div class="row row-1 bg-dark">
      <div class="col-1">
        <img
          src="https://mdbootstrap.com/img/Photos/Avatars/avatar-2.jpg"
          class="rounded-circle ml-2 mt-2 avatar z-depth-0"
          alt="avatar image"/>
      </div>
      <div class="col-11 "></div>
    </div>
   
<!--NOTE Navbar -->
        <nav class="mb-1 navbar navbar-expand-lg bg-dark p-0 border">
      <!-- <a class="navbar-brand ml-5 text-white" href="#">N E X U S</a> -->
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
<!-- 
          <form class="form-inline ml-5">
            <div class="md-form my-0">
              <input
                class="form-control searchbar mr-sm-2"
                type="text"
                placeholder="Search"
                aria-label="Search"/>
            </div>
            <button class="btn btn-md my-2 my-sm-0  bg-white" type="submit">Search</button>
          </form> -->
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
  height: 150px;
}

/* .row-2{
    height: 200px;
} */


.avatar{
    height: 8.5rem;
}

</style>