<template>
  <div class="home">
    <div class="hero-section" id="top">
      <div class="container py-5">
        <h1 class="text-white header-text text-center">Saxifrage technol limited</h1>
      </div>
    </div>

    <hr class="divider mt-5">

    <div class="container-fluid mt-5 mb-5">
      <div class="row">
        <div class="col-md-7 col-sm-12">
          <div id="carouselExampleCaptions" class="carousel slide" data-ride="carousel">
            <ol class="carousel-indicators">
              <li data-target="#carouselExampleCaptions" data-slide-to="0" class="active"></li>
              <li data-target="#carouselExampleCaptions" data-slide-to="1"></li>
              <li data-target="#carouselExampleCaptions" data-slide-to="2"></li>
            </ol>
            <div class="carousel-inner">
              <div class="carousel-item active">
                <img src="@/assets/1.jpg" class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block">
                  <h5>First slide label</h5>
                  <p>Some representative placeholder content for the first slide.</p>
                </div>
              </div>
              <div class="carousel-item">
                <img src="@/assets/1.jpg" class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block">
                  <h5>Second slide label</h5>
                  <p>Some representative placeholder content for the second slide.</p>
                </div>
              </div>
              <div class="carousel-item">
                <img src="@/assets/1.jpg" class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block">
                  <h5>Third slide label</h5>
                  <p>Some representative placeholder content for the third slide.</p>
                </div>
              </div>
            </div>
            <a class="carousel-control-prev" href="#carouselExampleCaptions" role="button" data-slide="prev">
              <span class="carousel-control-prev-icon" aria-hidden="true"></span>
              <span class="sr-only">Previous</span>
            </a>
            <a class="carousel-control-next" href="#carouselExampleCaptions" role="button" data-slide="next">
              <span class="carousel-control-next-icon" aria-hidden="true"></span>
              <span class="sr-only">Next</span>
            </a>
          </div>
        </div>
        <div class="col-md-5 col-sm-12">
          <h1>About Us</h1>
          <p class="small-text"> Lorem ipsum dolor sit amet consectetur adipisicing elit. Facilis, iure eum? Dolorum aspernatur beatae error itaque modi iure sed vero, pariatur adipisci voluptate, corporis quod voluptas in. Accusamus, voluptate veritatis.
          Repellendus debitis nisi officiis aliquam assumenda ea inventore similique vitae eaque! Veritatis nulla culpa id rem doloremque provident, similique corrupti illo assumenda consectetur hic eligendi voluptatem ea nesciunt expedita praesentium!
          Et maxime sapiente eligendi animi expedita officia illum laborum dicta, labore, itaque, numquam accusantium corporis nisi totam. </p>
        </div>
      </div>
    </div>

    <!-- Services Section -->
    <div class="mb-5">
      <h1 class="text-center">What we do</h1>
      <hr style="width: 4rem;" class="mb-5">

      <div class="d-flex">
        <div class="img-services1">
          <h3 class="middle text-center">Lorem Ipsum</h3>
        </div>
         <div class="img-services2">
          <h3 class="text-white middle text-center">Lorem Ipsum</h3>
        </div>
      </div>
      <div class="d-flex">
         <div class="img-services3">
         <h3 class="middle text-white text-center">Lorem Ipsum</h3>
        </div>
         <div class="img-services4">
          <h3 class="middle text-center">Lorem Ipsum</h3>
        </div>
      </div>
    </div>

    <!-- Gallery Section  -->
    <div class="mb-5">
      <h1 class="text-center">Gallery</h1>
      <hr style="width: 4rem;" class="mb-5">
      <div id="carouselExampleSlidesOnly" class="carousel slide" data-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active">
              <img src="@/assets/2.jpg" class="d-block carousel-img w-100 " alt="...">
          </div>
          <div class="carousel-item">
            <img src="@/assets/3.jpg" class="d-block w-100 carousel-img" alt="...">
          </div>
          <div class="carousel-item">
            <img src="@/assets/4.jpg" class="d-block w-100 carousel-img" alt="...">
          </div>
          <div class="carousel-item">
            <img src="@/assets/5.jpg" class="d-block w- carousel-img" alt="...">
          </div>
        </div>
      </div>
    </div>

    <!-- Projects Done  -->
    <div></div>

    <!-- Blog -->
    <div class="mb-5 container-fluid">
      <h1 class="text-center">Blog</h1>
      <hr style="width: 4rem;" class="mb-5">

     <div class="d-md-flex d-sm-block">
       <div class="card-pattern p-2 mb-3 text-center mr-3">
         <img src="@/assets/1.jpg"  alt="" srcset="" width="100%" height="200">
         <h5 class="text-left mt-3">This is the title of the blog/News</h5>
         <p class="text-left small-text">Lorem ipsum dolor sit amet, consectetu
           epturi quae soluta unde, ullam amet! Error, nam qui fugiat est sunt, 
           ut cum quia modi facilis, corporis quae nihil maiores tempore.
         </p>
         <div class="text-left">
           <i class="fa fa-thumbs-up mr-3 text-primary" aria-hidden="true"></i>
           <i class="fa fa-comment text-success" aria-hidden="true"></i>
         </div>
       </div>
       <div class="card-pattern p-2 mb-3 text-center mr-3">
         <img src="@/assets/1.jpg"  alt="" srcset="" width="100%" height="200">
         <h5 class="text-left mt-3">This is the title of the blog/News</h5>
         <p class="text-left small-text">Lorem ipsum dolor sit amet, consectetu
           epturi quae soluta unde, ullam amet! Error, nam qui fugiat est sunt, 
           ut cum quia modi facilis, corporis quae nihil maiores tempore.
         </p>
         <div class="text-left">
           <i class="fa fa-thumbs-up mr-3 text-primary" aria-hidden="true"></i>
           <i class="fa fa-comment text-success" aria-hidden="true"></i>
         </div>
       </div>
       <div class="card-pattern p-2 mb-3 text-center mr-3">
         <img src="@/assets/1.jpg"  alt="" srcset="" width="100%" height="200">
         <h5 class="text-left mt-3">This is the title of the blog/News</h5>
         <p class="text-left small-text">Lorem ipsum dolor sit amet, consectetu
           epturi quae soluta unde, ullam amet! Error, nam qui fugiat est sunt, 
           ut cum quia modi facilis, corporis quae nihil maiores tempore.
         </p>
         <div class="text-left">
           <i class="fa fa-thumbs-up mr-3 text-primary" aria-hidden="true"></i>
           <i class="fa fa-comment text-success" aria-hidden="true"></i>
         </div>
       </div>
       <div class="card-pattern p-2 mb-3 text-center mr-3">
         <img src="@/assets/1.jpg"  alt="" srcset="" width="100%" height="200">
         <h5 class="text-left mt-3">This is the title of the blog/News</h5>
         <p class="text-left small-text">Lorem ipsum dolor sit amet, consectetu
           epturi quae soluta unde, ullam amet! Error, nam qui fugiat est sunt, 
           ut cum quia modi facilis, corporis quae nihil maiores tempore.
         </p>
         <div class="text-left">
           <i class="fa fa-thumbs-up mr-3 text-primary" aria-hidden="true"></i>
           <i class="fa fa-comment text-success" aria-hidden="true"></i>
         </div>
       </div>
       
     </div>

     <div class="d-md-flex d-sm-block">
       <div class="card-pattern p-2 mb-3 text-center mr-3">
         <img src="@/assets/1.jpg"  alt="" srcset="" width="100%" height="200">
         <h5 class="text-left mt-3">This is the title of the blog/News</h5>
         <p class="text-left small-text">Lorem ipsum dolor sit amet, consectetu
           epturi quae soluta unde, ullam amet! Error, nam qui fugiat est sunt, 
           ut cum quia modi facilis, corporis quae nihil maiores tempore.
         </p>
         <div class="text-left">
           <i class="fa fa-thumbs-up mr-3 text-primary" aria-hidden="true"></i>
           <i class="fa fa-comment text-success" aria-hidden="true"></i>
         </div>
       </div>
       <div class="card-pattern p-2 mb-3 text-center mr-3">
         <img src="@/assets/1.jpg"  alt="" srcset="" width="100%" height="200">
         <h5 class="text-left mt-3">This is the title of the blog/News</h5>
         <p class="text-left small-text">Lorem ipsum dolor sit amet, consectetu
           epturi quae soluta unde, ullam amet! Error, nam qui fugiat est sunt, 
           ut cum quia modi facilis, corporis quae nihil maiores tempore.
         </p>
         <div class="text-left">
           <i class="fa fa-thumbs-up mr-3 text-primary" aria-hidden="true"></i>
           <i class="fa fa-comment text-success" aria-hidden="true"></i>
         </div>
       </div>
       <div class="card-pattern p-2 mb-3 text-center mr-3">
         <img src="@/assets/1.jpg"  alt="" srcset="" width="100%" height="200">
         <h5 class="text-left mt-3">This is the title of the blog/News</h5>
         <p class="text-left small-text">Lorem ipsum dolor sit amet, consectetu
           epturi quae soluta unde, ullam amet! Error, nam qui fugiat est sunt, 
           ut cum quia modi facilis, corporis quae nihil maiores tempore.
         </p>
         <div class="text-left">
           <i class="fa fa-thumbs-up mr-3 text-primary" aria-hidden="true"></i>
           <i class="fa fa-comment text-success" aria-hidden="true"></i>
         </div>
       </div>
       <div class="card-pattern p-2 mb-3 text-center mr-3">
         <img src="@/assets/1.jpg"  alt="" srcset="" width="100%" height="200">
         <h5 class="text-left mt-3">This is the title of the blog/News</h5>
         <p class="text-left small-text">Lorem ipsum dolor sit amet, consectetu
           epturi quae soluta unde, ullam amet! Error, nam qui fugiat est sunt, 
           ut cum quia modi facilis, corporis quae nihil maiores tempore.
         </p>
         <div class="text-left">
           <i class="fa fa-thumbs-up mr-3 text-primary" aria-hidden="true"></i>
           <i class="fa fa-comment text-success" aria-hidden="true"></i>
         </div>
       </div>
       
     </div>
     
    </div>

  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  components: {
  }
}
</script>

<style scoped>
  .hero-section {
    background:  url("../assets/1.jpg");
    background-size: cover;
  }
  .header-text {
    text-transform: uppercase;
    font-size: 3rem;
    font-weight: bold;
    color: #e2bb5a !important;
  }
  .small-text {
    font-size: 0.8rem;
  }
  .img-services1 {
    background: url("../assets/2.jpg");
    width: 100%;
    height: 30rem;
    background-repeat: no-repeat;
    background-size: cover;
  }
  .img-services2 {
    background: url("../assets/3.jpg");
    width: 100%;
    height: 30rem;
    background-repeat: no-repeat;
    background-size: cover;
  }
  .img-services3 {
    background: url("../assets/4.jpg");
    width: 100%;
    height: 30rem;
    background-repeat: no-repeat;
    background-size: cover ;
  }
  .img-services4 {
    background: url("../assets/5.jpg");
    width: 100%;
    height: 30rem;
    background-repeat: no-repeat;
    background-size: cover ;
  }
  .middle {
    opacity: 0;
    
  }
  .img-services1:hover{
    background-color: #e2bb5a9e;
    background-blend-mode: overlay;
    transition: 1s;
   
  }
  .img-services1:hover .middle, .img-services2:hover .middle, .img-services3:hover .middle, .img-services4:hover .middle  {
    opacity: 1;
    transition: 3s;
  }
  .img-services2:hover {
    background-color: rgba(0, 0, 0, 0.597);
    background-blend-mode: overlay;
    transition: 1s;
   
  }
  .img-services3:hover{
    background-color: #27314baf;
    background-blend-mode: overlay;
    transition: 1s;
   
  }
  .img-services4:hover {
    background-color: rgba(255, 255, 255, 0.7);
    background-blend-mode: overlay;
    transition: 1s;
    
  }
  .carousel-img{
    height: 30rem;
  }
  .card-pattern {
    box-shadow: 0px 0px 5px 0px rgba(182, 182, 182, 0.7);
    border-radius: 5px;
  }




  /* Media Queries  */
  @media screen and (max-width: 764px) {
    .img-services1, .img-services2, .img-services3, .img-services4 {
      height: 10rem !important;
    }
    .carousel-img {
      height: 10rem !important;
    }
    .card-pattern {
      margin-right: 0 !important;
    }
  }
</style>