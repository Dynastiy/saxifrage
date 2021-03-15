<template>
  <div class="">
    <div class="">
      <div class="top-nav justify-content-around align-items-center py-5 d-flex">
        <img class="img-logo" src="@/assets/saxi.png" alt="Image" width="">
        <div class="top-search">
          <div class="input-group mb-3">
                <input type="text" class="form-control" placeholder="" aria-label="" aria-describedby="basic-addon2">
                <div class="input-group-append">
                  <span class="input-group-text" id="basic-addon2"><i class="fa fa-search" aria-hidden="true"></i></span>
                </div>
        </div>
        </div>
      </div>
      <div class="center-nav">
              <div class="text-center justify-content-center py-4">
                <a class="company-link mr-3" href="#">Saxifrage refinery </a><span class="mr-3">|</span>
                <a class="company-link mr-3" href="#">Human Life care Afrique</a> <span class="mr-3">|</span>
                <a class="company-link mr-3" href="#">Indept prison foundation</a> <span class="mr-3">|</span>
                <a class="company-link" href="#">owoidoikem </a>
              </div>
      </div>
    </div>
     <div class="bottom-nav " id="navbar">
        <nav class="navbar sticky-top navbar-expand-lg navbar-light bg-dark shadow-sm">
          <a class="navbar-brand" href="#"></a>
          <button class="navbar-toggler text-light bg-light" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
            <div class="navbar-nav mr-auto  ml-auto">
              <a class="nav-link" href="#">Home</a>
              <a class="nav-link" href="#">About</a>
              <a class="nav-link" href="#">Services</a>
              <a class="nav-link" href="#">Gallery</a>
              <a class="nav-link" href="#">Projects</a>
              <a class="nav-link" href="#">Blog</a>
            </div>
          </div>
        </nav>
     </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: '',
  components: {
    // HelloWorld
  },
  mounted(){
    window.onscroll = function() {myFunction()};

      var navbar = document.getElementById("navbar");
      var sticky = navbar.offsetTop;

      function myFunction() {
        if (window.pageYOffset >= sticky) {
          navbar.classList.add("sticky")
        } else {
          navbar.classList.remove("sticky");
        }
      }
  }
}
</script>

<style scoped>
.top-search {
  width: 50%;
}
.img-logo {
  width: 4rem;
  height: 4rem;
}
.company-link {
  color: #000 !important;
  font-weight: bold !important;
  text-transform: uppercase;
  /* padding: 1rem 3rem; */
}
.center-nav {
  box-shadow: 0px 0px 2px 0px rgba(24, 24, 24, 0.3);
}
.company-link:hover {
  text-decoration: none;
  transform: translate(4px, -9px);
  color: #e2bb5a !important;
  transition: 1s ease-in-out;
}
.form-control {
  border-radius: 0 !important;
}
.input-group-text {
  background: #27314b ;
  color: #fff;
  border-radius: 0;
  border: none;
}
  .nav-link{
    font-weight: 500;
    font-size: 0.8rem;
    color: #e2bb5a !important;
    text-transform: uppercase;
  }
  .navbar-nav a {
  position: relative;
  overflow: hidden;
  z-index: 1;
}
.navbar-nav a:after {
  display: block;
  position: absolute;
  margin: 0;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  content: '.';
  color: transparent;
  width: 1px;
  height: 1px;
  border-radius: 50%;
  background: transparent;
}
.navbar-nav a:hover:after {
  -webkit-animation: circle 1s ease-in forwards;
  color: #000 !important;
}
.sticky {
  position: fixed;
  top: 0;
  width: 100%;
  z-index: 999;
}

@keyframes circle {
  0% {
    width: 1px;
    top: 0;
    left: 0;
    bottom: 0;
    right: 0;
    margin: auto;
    height: 1px;
    z-index: -1;
    background: #eee;
    border-radius: 100%;
  }
  100% {
    background: #aaa;
    height: 5000%;
    width: 5000%;
    z-index: -1;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    margin: auto;
    border-radius: 0;
  }
}

</style>
