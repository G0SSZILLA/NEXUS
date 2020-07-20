<template>
  <div class="navbar p-0 container-fluid d-inline">
    <!--NOTE START Navbar -->
    <nav class="mb-1 navbar navbar-expand-lg  p-0 shadow">
      <a class="navbar-brand ml-4  nexus text-white" href="#">N E <span class="X">X</span> U S</a>
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
        <ul class="navbar-nav mr-auto">
          <!-- <li class="nav-item active">
            <a class="nav-link text-white" href="#">
              Home
              <span class="sr-only">(current)</span>
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-white" href="#">Features</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-white" href="#">Pricing</a>
          </li> -->
          <li class="nav-item dropdown">
            <a
              class="nav-link dropdown-toggle text-white ml-4  mt-3"
              id="navbarDropdownMenuLink-555"
              data-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false">Community</a>
            <div
              class="dropdown-menu dropdown-secondary"
              aria-labelledby="navbarDropdownMenuLink-555">
              <a class="dropdown-item" href="#">Action</a>
              <a class="dropdown-item" href="#">Another action</a>
              <a class="dropdown-item" href="#">Something else here</a>
            </div>
          </li>

          <form class="form-inline ml-4">
            <div class="md-form my-0">
              <input
                class="form-control searchbar mr-sm-2"
                type="text"
                placeholder="Search"
                aria-label="Search"/>
            </div>
            <button class="btn btn-md my-2 my-sm-0  bg-white" type="submit">Search</button>
          </form>
        </ul>
        <ul class="navbar-nav ml-auto nav-flex-icons ">
          <li class="nav-item mr-3 mt-1 text-white">
            <a class="nav-link waves-effect waves-light">
              1
              <img class="message text-white mb-1" src="https://img.icons8.com/ios/50/000000/important-mail.png"/>
              <!-- <i class="message fas fa-envelope mt-1"></i> -->
            </a>
          </li>
        </ul>
        <ul>
          <li class="nav-item avatar dropdown mt-1">
            <a
              class="nav-link dropdown-toggle"
              id="navbarDropdownMenuLink-55"
              data-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false">
              <img
                src="https://mdbootstrap.com/img/Photos/Avatars/avatar-2.jpg"
                class="rounded-circle avatar mb- z-depth-0"
                alt="avatar image"/>
            </a>
            <div
              class="dropdown-menu dropArrow dropdown-menu-lg-right dropdown-secondary"
              aria-labelledby="navbarDropdownMenuLink-55">
              <a class="dropdown-item" href="#">Action</a>
              <a class="dropdown-item" href="#">Another action</a>
              <a class="dropdown-item" href="#">Something else here</a>
            </div>
          </li>
        </ul>
      </div>
    </nav>
    <!--NOTE END Navbar -->
  </div>
</template>

<script>
export default {
  name: "navbar",

  data() {
    return {};
  },

  computed: {},

  methods: {},

  components: {}
};
</script>


<style scoped>
.navbar {
  height: 3rem;
  background-color:  #182338;
  font-family: 'Syncopate', sans-serif;
}

.nexus{
  /* color: #7206ff; */
  font-weight: 300;
  font-size: 2rem;
  margin-top: px;
  font-family: 'Syncopate', sans-serif;
}

.NE{
font-size: 1.8;
}

.X{
  font-size: 2.8rem;
}

.US{

}

.navbar-brand{
  /* font-size: 2.25rem;
  margin-bottom: 5px; */
}

.avatar {
  height: 2.5rem;
  margin-bottom: 5px;
   /* font-family: 'Syncopate', sans-serif; */
}

/* .dropArrow{
  color: white;
  background-color: white;
} */

.searchbar{
  width: 980px;
  /* background-color:#273552; */
  /* color: white; */
}

.message {
height: 40px;

}

</style>

